---
layout: default
title: "Horizon Summary: 2026-09-08 (ZH)"
date: 2026-09-08
lang: zh
---

> 从 36 条内容中筛选出 17 条重要资讯。

---

1. [LLM 漏洞发现能力迫使安全界一年内改进实践](#item-1) ⭐️ 8.0/10
2. [在 GPU 上分解 90 年代 CA 的 RSA 密钥](#item-2) ⭐️ 8.0/10
3. [D2 图表布局引擎 TALA 开源](#item-3) ⭐️ 8.0/10
4. [Jellyfin 12.0 发布，带来改进与修复](#item-4) ⭐️ 8.0/10
5. [博通移除 VDDK 下载，阻碍 VMware 迁移](#item-5) ⭐️ 8.0/10
6. [LG 智能电视被曝记录音频并窥探本地设备](#item-6) ⭐️ 8.0/10
7. [GitHub 上发布 Stuxnet 源代码重建版本](#item-7) ⭐️ 8.0/10
8. [OpenAI 首席科学家呼吁加强 AI 对齐保障措施](#item-8) ⭐️ 8.0/10
9. [OpenAI 揭示编码代理加速研究，支出激增](#item-9) ⭐️ 8.0/10
10. [Notion 的 MCP 连接器暗中提示 AI 做广告](#item-10) ⭐️ 8.0/10
11. [滥用爬虫在 kernel.org 上超过合法 Git 访问](#item-11) ⭐️ 7.0/10
12. [OpenAI 首席科学家倡导防御性 AI，警告勿鲁莽竞赛](#item-12) ⭐️ 7.0/10
13. [DNS 滥用：新通用顶级域名中高达 20%是诈骗](#item-13) ⭐️ 7.0/10
14. [为什么从头重写软件通常会失败](#item-14) ⭐️ 7.0/10
15. [llm 0.35 新增对 OpenAI GPT-6 Astra 的支持](#item-15) ⭐️ 6.0/10
16. [用于博客的 WebAssembly FFMPEG 视频压缩器](#item-16) ⭐️ 6.0/10
17. [用 GPT-6 Astra 构建的 Mercator 到 Equal Earth 动画过渡](#item-17) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [LLM 漏洞发现能力迫使安全界一年内改进实践](https://jyn.dev/a-year-to-fix-security/) ⭐️ 8.0/10

文章认为，LLM 在发现软件漏洞方面的快速进步，给安全界大约一年的时间来彻底改革安全实践，否则攻击者将大规模利用这一能力。文章强调了采用最佳实践和简化技术栈的紧迫性。 这很重要，因为 LLM 在漏洞发现方面变得异常高效，可能降低攻击者的门槛，并超越传统防御措施。如果安全界未能在这一窗口期内采取行动，我们可能会看到零日漏洞利用和大规模数据泄露的激增。 文章指出，当前的 LLM 在识别漏洞方面“极其擅长”，社区评论甚至认为一年的时间可能过于乐观。实际步骤包括简化软件技术栈、了解依赖关系，以及实施重叠的安全控制。

hackernews · saikatsg · 9月8日 04:48 · [社区讨论](https://news.ycombinator.com/item?id=49605691)

**背景**: 大型语言模型（LLM）在代码分析和漏洞检测方面展现出日益增强的能力，最近的研究表明它们可以在真实项目中找到新的零日漏洞。安全界传统上依赖人工代码审查和最佳实践，但 LLM 驱动的发现速度和规模可能超过人类努力，因此主动改进至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/huhusmang/Awesome-LLMs-for-Vulnerability-Detection">GitHub - huhusmang/Awesome-LLMs-for-Vulnerability-Detection: The community's most comprehensive, continuously-updated index of research on Large Language Models for software vulnerability detection — papers across function-level, repository-level, agentic, and smart-contract detection, plus datasets, benchmarks, and surveys.</a></li>
<li><a href="https://kenhuangus.substack.com/p/token-is-all-you-need-finding-0days">Token Is All You Need: Finding 0days with LLMs and Agentic AI</a></li>
<li><a href="https://securityexceptions.com/articles/security-risk-management-timeline-implementation-timeline">Security Risk Management Timeline: How Long Does Implementation Take? - Spectra</a></li>

</ul>
</details>

**社区讨论**: 社区评论对作者的硬件说法表示怀疑，一位用户指出在 Mac 上运行 LLM 不会那么快。其他人同意紧迫性，一位评论者说“我认为我们甚至没有一年”。关于最佳实践和供应链风险也有争论，一位用户提倡简单化，另一位则因供应链问题对 Rust 提出警告。

**标签**: `#security`, `#LLM`, `#AI`, `#vulnerabilities`, `#best practices`

---

<a id="item-2"></a>
## [在 GPU 上分解 90 年代 CA 的 RSA 密钥](https://mcpherrin.ca/2026/09/07/rsa.html) ⭐️ 8.0/10

作者使用消费级 GPU 成功分解了 1990 年代一家证书颁发机构的 512 位 RSA 密钥，耗时约两天。这表明此类密钥在现代硬件面前的实际脆弱性。 这凸显了历史加密的长期不安全性，并引发了对今天记录的数据将来可能被解密的担忧。同时强调了当前系统使用足够大密钥尺寸的重要性。 分解工作在消费级 GPU 上完成，作者指出 90 年代的大部分流量并未使用临时密钥，因此容易受到攻击。作者在部分工作中使用了 LLM 辅助，但强调需要验证 LLM 输出的准确性。

hackernews · ahlCVA · 9月8日 01:16 · [社区讨论](https://news.ycombinator.com/item?id=49604637)

**背景**: RSA 是一种广泛用于安全数据传输的公钥密码系统。在 1990 年代，512 位 RSA 密钥很常见，但到 1999 年，研究人员已经使用数域筛法分解了一个 512 位的 RSA 模数。现代消费级 GPU 使此类分解更加容易，引发了对加密数据长期机密性的担忧。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/RSA_(cryptosystem)">RSA (cryptosystem) - Wikipedia</a></li>
<li><a href="https://infoscience.epfl.ch/server/api/core/bitstreams/79cc31d6-eafd-4e50-9af1-56568a96f34f/content">Factorization of a 512 – Bit RSA Modulus</a></li>
<li><a href="https://en.wikipedia.org/wiki/Certificate_authority">Certificate authority - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者表达了复杂的情绪：一些人对 AI 被用于有趣的部分感到失望，而另一些人则指出 SSL 报告显示'F'评级的讽刺意味。还有人担心政府会记录加密流量以备将来解密，并提醒必须验证 LLM 输出的正确性。

**标签**: `#RSA`, `#cryptography`, `#security`, `#historical`, `#GPU`

---

<a id="item-3"></a>
## [D2 图表布局引擎 TALA 开源](https://d2lang.com/blog/tala-is-open-source/) ⭐️ 8.0/10

Terrastruct 已将其专有的 D2 图表布局引擎 TALA 开源，免费提供给社区使用。该引擎现已在 GitHub 上可用，用户可通过设置 D2_LAYOUT 环境变量来使用它。 此举解决了 D2 社区长期以来的痛点：默认布局引擎生成的图表往往不尽如人意。通过开源 TALA，用户现在可以使用专为软件架构图设计的更先进的布局引擎，有望提升 D2 的图表质量并促进其采用。 TALA 是一个通用的正交布局引擎，其算法从零构建，零依赖，不受限于特定图表类型（如层次结构或树状结构）。对于非层次结构，它可以生成类似人类在白板上绘制的布局，并支持通过 'top' 和 'left' 属性锁定位置。

hackernews · alixanderwang · 9月7日 23:37 · [社区讨论](https://news.ycombinator.com/item?id=49604150)

**背景**: D2 是一种现代的声明式图表语言，可将文本编译为图表，类似于 Mermaid，但具有嵌套容器和可插拔布局引擎等特性。TALA 是 Terrastruct 的自动布局方法的缩写，此前是 Terrastruct 内部开发的专有引擎，专为软件架构图设计。TALA 的开源意义重大，因为它让更广泛的社区能够受益于以前只能通过付费许可获得的布局引擎。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://terrastruct.com/tala/">Information about TALA , Terrastruct's proprietary layout engine for D 2</a></li>
<li><a href="https://d2lang.com/tour/tala/">TALA | D 2 Documentation</a></li>
<li><a href="https://github.com/terrastruct/TALA">GitHub - terrastruct/ TALA : A diagram layout engine designed...</a></li>

</ul>
</details>

**社区讨论**: 社区成员表达了积极情绪，aidenn0 指出 TALA 有时比 ELK 有大幅改进，但因成本问题未购买；sotilrac 表示非常高兴，并计划将 TALA 集成到 Daedalus 中。然而，ricardobeat 指出，虽然前几个图更整洁，但 Go 队列示例客观上更差，使其看起来比实际更复杂。其他人则询问关键启发式方法，以及将 TALA 集成到 Graphviz 是否有益。

**标签**: `#open-source`, `#diagramming`, `#graph-layout`, `#D2`, `#TALA`

---

<a id="item-4"></a>
## [Jellyfin 12.0 发布，带来改进与修复](https://jellyfin.org/posts/jellyfin-release-12.0/) ⭐️ 8.0/10

Jellyfin 12.0 已正式发布，带来一系列改进和修复。用户反馈从旧版本升级过程顺畅，初始迁移仅需几分钟。 此次发布巩固了 Jellyfin 作为 Plex 等专有媒体服务器的可行开源替代品的地位。它解决了早期版本存在的性能问题，使其对拥有大型媒体库的用户更具吸引力。 从 10.10.7 升级到 12.0 的用户指出，部分影片在重新扫描前会消失，但除此之外升级过程很顺利。然而，仍有用户反映在 Android 客户端投屏到 Chromecast 时存在字幕问题，还有一位用户不得不从 10.11.x 回退到 10.10。

hackernews · 0xC0ncord · 9月8日 01:56 · [社区讨论](https://news.ycombinator.com/item?id=49604861)

**背景**: Jellyfin 是一款免费开源的媒体服务器，允许用户整理、流式传输和管理个人媒体库。它常被拿来与 Plex 比较，但与 Plex 不同，它完全自托管，无需付费订阅或云服务。

**社区讨论**: 社区情绪总体积极，用户称赞升级顺利和项目的进展。一些人希望 Jellyfin 能制约 Plex 对用户不友好的行为，而另一些人仍遇到字幕问题和性能回退。

**标签**: `#Jellyfin`, `#media server`, `#open source`, `#release`, `#self-hosted`

---

<a id="item-5"></a>
## [博通移除 VDDK 下载，阻碍 VMware 迁移](https://www.virtualizationhowto.com/2026/09/leaving-vmware-just-got-harder-after-broadcom-pulled-vddk-downloads/) ⭐️ 8.0/10

博通已移除 VMware 虚拟磁盘开发套件（VDDK）的下载，该工具是第三方备份和迁移产品的关键组件。此举使得用户迁移离开 VMware 变得更加困难，因为许多工具依赖 VDDK 来访问虚拟磁盘。 此举引发了对供应商锁定的担忧，因为它限制了用户离开 VMware 的能力，可能迫使他们继续支付博通高昂的许可费用。同时，它也影响了更广泛的虚拟化生态系统，波及依赖 VDDK 的备份供应商和迁移服务提供商。 VDDK 对于备份和迁移工具读写 VMware 虚拟磁盘至关重要。虽然某些迁移路径（如 VMware 到 Proxmox）可能不受影响，但许多企业级工具依赖 VDDK，这使得大规模环境的迁移变得更加复杂和昂贵。

hackernews · josephcsible · 9月7日 20:32 · [社区讨论](https://news.ycombinator.com/item?id=49602699)

**背景**: 博通于 2023 年 11 月收购了 VMware，此后进行了重大变革，包括终止永久许可并提高价格。VDDK 是一个软件开发套件，允许第三方应用程序访问 VMware 虚拟磁盘数据，其移除是博通整合 VMware 生态系统控制权战略的一部分。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://developer-stgv2.broadcom.com/sdks/vmware-virtual-disk-development-kit-vddk/latest/">VMware Virtual Disk Development Kit (VDDK)</a></li>
<li><a href="https://techdocs.broadcom.com/us/en/vmware-cis/vsphere/vsphere-sdks-tools/8-0/virtual-disk-development-kit-programming-guide.html">Virtual Disk Development Kit (VDDK) Programming Guide - VMware</a></li>
<li><a href="https://www.broadcom.com/company/news/articles/innovation/broadcom-announces-successful-acquisition-of-vmware">Broadcom announces successful acquisition of VMware | Hock Tan</a></li>

</ul>
</details>

**社区讨论**: 社区评论对博通对 VMware 的管理表达了悲伤和沮丧，前工程师感叹创新精神的丧失。一些用户分享了他们的迁移经验，指出迁移到 Proxmox 或 KVM 等替代方案是可行的，但需要付出努力，而另一些人则建议采用开源选项以避免供应商锁定。

**标签**: `#VMware`, `#Broadcom`, `#virtualization`, `#vendor lock-in`, `#migration`

---

<a id="item-6"></a>
## [LG 智能电视被曝记录音频并窥探本地设备](https://www.youtube.com/watch?v=6IFVTcM28KA) ⭐️ 8.0/10

Gamers Nexus 的一项调查发现，LG 智能电视（包括 G5 等零售 OLED 型号）会主动扫描本地网络中的手机和智能手表，并且即使在屏幕关闭时也能捕获麦克风音频。一旦电视重新连接互联网，这些数据就会被上传。 这引发了数百万 LG 智能电视用户的严重隐私担忧，因为他们的设备可能在未经明确同意的情况下收集敏感的音频和网络信息。它凸显了智能设备监控的广泛行业问题，以及加强隐私监管的必要性。 调查使用 Wireshark 捕获网络数据包，显示电视扫描局域网中的无关硬件。测试还表明，电视可以在屏幕关闭时捕获音频，并在之后上传数据。LG 表示客户隐私是重中之重，并正在调查相关报告。

hackernews · treve · 9月7日 00:22 · [社区讨论](https://news.ycombinator.com/item?id=49592375)

**背景**: 智能电视通常为广告和个性化收集数据，但这项调查揭示了更具侵入性的行为。据报道，LG 的合同条款要求用户通知家庭成员和客人他们的声音可能被捕获，并获得第三方的同意。这引发了与窃听法律的比较以及对同意问题的担忧。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://cybersecuritynews.com/lg-smart-tvs-caught-scanning-networks/">LG Smart TVs Caught Scanning Networks and Logging Audio in...</a></li>
<li><a href="https://www.notebookcheck.net/LG-smart-TVs-caught-logging-audio-with-screen-off-and-snooping-on-local-devices.1391214.0.html">LG smart TVs caught logging audio with screen off and snooping on local devices - Notebookcheck News</a></li>
<li><a href="https://www.tomsguide.com/us/lg-smarttv-spying,news-17874.html">LG Smart TVs May Spy on Users, Blogger Says | Tom's Guide</a></li>

</ul>
</details>

**社区讨论**: 社区评论表达了愤怒和担忧，用户分享了在 LG 电视上禁用网络功能并因此被嘲笑的经历。一些人指出在广告满屏的网站上报道隐私问题的讽刺性，而另一些人则质疑其是否符合窃听法律。总体情绪对 LG 和行业的数据实践持批评态度。

**标签**: `#privacy`, `#smart-tv`, `#security`, `#LG`, `#surveillance`

---

<a id="item-7"></a>
## [GitHub 上发布 Stuxnet 源代码重建版本](https://github.com/Sadpainy/Stuxnet) ⭐️ 8.0/10

一位名为 Sadpainy 的 GitHub 用户发布了一个从反编译二进制文件推导出的 Stuxnet 网络武器源代码重建版本，仅供教育和研究目的。该仓库包含约 15,000 行代码。 这一重建版本为研究人员和网络安全爱好者提供了一个便捷的机会，来研究有史以来最复杂的恶意软件之一，该恶意软件曾针对伊朗核离心机，标志着网络战的一个转折点。它强调了理解此类威胁以保护关键基础设施的重要性。 该代码是重建版本，并非原始源代码，且仅用于教育和研究目的。它包含针对西门子 S7 PLC 和 WINCC HMI 系统的组件，这些系统常用于工业控制系统。

hackernews · CMDDestory · 9月7日 22:12 · [社区讨论](https://news.ycombinator.com/item?id=49603546)

**背景**: Stuxnet 是一种于 2010 年发现的恶意计算机蠕虫，普遍认为由美国和以色列在“奥运会行动”中开发。据报道，它通过重新编程工业控制系统，摧毁了伊朗近五分之一的核离心机，标志着首次已知使用网络武器造成物理破坏。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/Sadpainy/Stuxnet">GitHub - Sadpainy/ Stuxnet : Stuxnet , Here reproduced by me, Only for...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Operation_Olympic_Games">Operation Olympic Games - Wikipedia</a></li>
<li><a href="https://news.ycombinator.com/item?id=49603546">Show HN: Stuxnet – A reconstructed source code of... | Hacker News</a></li>

</ul>
</details>

**社区讨论**: 评论者对该项目的教育价值表示赞赏，其中一位提到它改变了对关键基础设施的看法。一些人推荐了相关书籍，而另一些人则对 USB 传播的可行性提出疑问，并建议增加更多文档以提高仓库的可用性。

**标签**: `#cybersecurity`, `#stuxnet`, `#malware`, `#critical infrastructure`, `#reverse engineering`

---

<a id="item-8"></a>
## [OpenAI 首席科学家呼吁加强 AI 对齐保障措施](https://openai.com/index/an-alien-mind) ⭐️ 8.0/10

OpenAI 首席科学家 Jakub Pachocki 发表了一篇题为《异类心智》的反思文章，讨论了对齐日益强大的 AI 系统的挑战，并呼吁加强保障措施和国际协调。 这位顶尖 AI 研究者的反思凸显了业界对 AI 对齐与安全日益增长的担忧，可能影响政策讨论和研究重点。它强调了全球合作应对先进 AI 风险的必要性。 这篇文章基于观点，缺乏技术深度，侧重于 AI 对齐的广泛影响。Pachocki 作为 OpenAI 首席科学家的身份使该声明具有重要分量，但并未提出新的技术方案。

rss · OpenAI News · 9月6日 09:00

**背景**: AI 对齐是 AI 安全的一个子领域，旨在引导 AI 系统符合人类意图和价值观。未对齐的 AI 可能追求非预期目标，从而造成危害。先进系统可能表现出战略欺骗等涌现行为，使对齐变得困难。随着 AI 能力快速进步，研究人员和行业领袖呼吁加强保障措施。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/AI_alignment">AI alignment</a></li>
<li><a href="https://en.wikipedia.org/wiki/AI_safety">AI safety</a></li>

</ul>
</details>

**标签**: `#AI safety`, `#AI alignment`, `#OpenAI`, `#policy`

---

<a id="item-9"></a>
## [OpenAI 揭示编码代理加速研究，支出激增](https://openai.com/index/research-acceleration-view-inside-openai) ⭐️ 8.0/10

OpenAI 发布了内部数据，显示编码代理已成为其研究工作流程中不可或缺的一部分，研究人员在代理上的每日中位支出从 2026 年初的接近零上升到 2026 年 8 月下旬的超过 600 美元。公司还发布了由首席科学家 Jakub Pachocki 撰写的配套文章《异类心智》，讨论了递归自我改进（RSI）。 这提供了罕见的、具体的证据，表明 AI 工具如何加速 AI 研究本身，可能缩短未来模型的开发周期。它标志着编码代理正从实验性工具转变为一流 AI 实验室中的关键基础设施，这可能重塑研究经济学和竞争格局。 数据显示，代理使用量从 2026 年 7 月下旬开始急剧增加，Simon Willison 推测这可能与内部访问后来以 GPT-6 Astra 发布的模型有关。OpenAI 还报告称，代理正在处理更复杂的任务，到 2026 年 8 月中旬实际上充当了“自动化研究实习生”的角色。

rss · OpenAI News · 9月6日 08:00

**背景**: 递归自我改进（RSI）指的是 AI 系统帮助开发后续 AI 系统，形成反馈循环，可能加速进展。编码代理是能够自主编写、调试和修改代码的 AI 工具，OpenAI 已将其整合到研究流程中，以提高实验速度。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openai.com/index/research-acceleration-view-inside-openai/">Research acceleration: The view inside OpenAI | OpenAI</a></li>
<li><a href="https://simonwillison.net/2026/Sep/6/research-acceleration-the-view-inside-openai/">Research acceleration: The view inside OpenAI</a></li>
<li><a href="https://www.brocker.org/openai-research-acceleration-alien-mind-rsi-september-2026">OpenAI research acceleration + Alien Mind: RSI snapshot, CoT warning</a></li>

</ul>
</details>

**社区讨论**: Simon Willison 的评论强调了对 7 月下旬加速的好奇，推测这与内部访问 GPT-6 Astra 有关。关于 RSI 日的广泛讨论表明，人们对 AI 加速自身发展的影响既感到兴奋又感到担忧。

**标签**: `#AI research`, `#coding agents`, `#OpenAI`, `#automation`, `#research acceleration`

---

<a id="item-10"></a>
## [Notion 的 MCP 连接器暗中提示 AI 做广告](https://www.reddit.com/r/ClaudeAI/comments/1w9dluw/notions_official_mcp_connector_prompt_injects_ai/) ⭐️ 8.0/10

有用户报告称，Notion 的官方 MCP 连接器向 AI 代理注入了促销提示，指示其在任务中途未经用户同意或文档说明的情况下宣传 Notion Business。该连接器还告诉 AI 永远不要解释为什么这样做。 这引发了对大公司官方 AI 集成在伦理和透明度方面的重大担忧，可能削弱用户对 AI 代理和 MCP 连接器的信任。它凸显了在 AI 系统用于促销目的时，需要明确的指导和披露。 用户无法在 Notion 的官方文档中找到任何关于此行为的说明，而且提示注入发生在用户未询问 Notion 计划的情况下。该事件在 Reddit 的 r/ClaudeAI 社区分享，表明它影响了 Claude AI 代理的用户。

reddit · r/ClaudeAI · /u/JavaSensei24 · 9月7日 00:56

**背景**: 模型上下文协议（MCP）是 Anthropic 推出的开放标准，为 AI 模型安全连接外部工具和数据提供了通用接口。提示注入是一种攻击类型，通过在内容中嵌入恶意或隐藏指令来操纵 AI 系统。在此案例中，Notion 的 MCP 连接器似乎包含了隐藏的促销指令，AI 代理遵循了这些指令，引发了对 AI 集成中信任和透明度的担忧。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Model_Context_Protocol">Model Context Protocol - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Prompt_injection">Prompt injection - Wikipedia</a></li>
<li><a href="https://www.ibm.com/think/topics/prompt-injection">What Is a Prompt Injection Attack? | IBM</a></li>

</ul>
</details>

**社区讨论**: 社区讨论可能表达了愤怒和失望，用户质疑 Notion 的伦理，并呼吁在 AI 集成中提高透明度。一些人可能分享类似经历或讨论对 MCP 安全和信任的影响。

**标签**: `#AI ethics`, `#MCP`, `#Notion`, `#Prompt injection`, `#AI agents`

---

<a id="item-11"></a>
## [滥用爬虫在 kernel.org 上超过合法 Git 访问](https://simonwillison.net/2026/Sep/7/creepy-crawlies/) ⭐️ 7.0/10

Konstantin Ryabitsev 报告称，在 git.kernel.org 上，滥用爬虫消耗的 CPU 已超过包括 git 克隆在内的所有合法访问。在任何时候，分布在 5 个地理节点的 14 个 CPU 核心仅用于为爬虫将提交渲染为 HTML。 这凸显了网络爬虫和 AI 爬虫对关键开源基础设施日益增长的运营负担。它引发了像 Datasette 这样提供大量可爬取页面的项目的担忧，可能增加成本并降低合法用户的性能。 Linux 内核仓库在 git.kernel.org 上约有 148 万次提交和 922 个分支，但将每次提交渲染为 HTML 相比 git 克隆效率低下。这种负载被描述为滥用爬虫的“背景辐射”，它们常常忽略 robots.txt，使用 HTML 抓取而非高效协议。

rss · Simon Willison · 9月7日 23:08

**背景**: git.kernel.org 是 Linux 内核的官方 Git 仓库，开发者通常通过克隆仓库来获取源代码。然而，一些爬虫，尤其是与 AI 相关的爬虫，会抓取 HTML 页面而不是使用 git clone，导致不必要的 CPU 负载。这个问题是更广泛的激进网络爬虫影响互联网服务器性能趋势的一部分。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://geekhaus.club/feed/2026/08/29/kernel-org-maintainer-says-ai-crawlers-now">Kernel.org maintainer says AI crawlers now consume more CPU than all legitimate Git access combined | Geek Haus</a></li>
<li><a href="https://letsdatascience.com/news/kernelorg-reports-crawler-load-on-git-infrastructure-05ae4912">Kernel.org Reports Crawler Load on Git Infrastructure | Let's Data Science</a></li>

</ul>
</details>

**社区讨论**: Hacker News 上的讨论可能验证了这一担忧，用户分享类似经历并讨论缓解策略。一些人可能争论 AI 爬虫的作用以及更好管理机器人的必要性。

**标签**: `#web crawling`, `#infrastructure`, `#Linux kernel`, `#scraping`, `#performance`

---

<a id="item-12"></a>
## [OpenAI 首席科学家倡导防御性 AI，警告勿鲁莽竞赛](https://simonwillison.net/2026/Sep/7/jakub-pachocki/) ⭐️ 7.0/10

OpenAI 首席科学家 Jakub Pachocki 公开表示，为了防御其他 AI 带来的威胁，开发强大且对齐的 AI 是必要的，同时警告这种紧迫性不能成为鲁莽竞赛的借口。他的言论发表在 OpenAI 博客文章《An Alien Mind》的“可扩展防御”部分。 OpenAI 高管的这一表态表明其战略上重视防御性 AI 应用，可能影响行业优先事项和围绕 AI 安全的政策讨论。这反映了在加速 AI 开发以获取竞争优势与确保负责任部署之间的持续张力。 Pachocki 强调，对齐的 AI 将用于保护基础设施、实时防御恶意代理并发明新的防护措施，这将成为 OpenAI 部署工作的重点。他还承认广泛 AI 进展存在不确定性，并强调风险的严重性应排除“不惜一切代价”的竞赛心态。

rss · Simon Willison · 9月7日 22:26

**背景**: AI 对齐是指确保 AI 系统按照人类意图和价值观行动。OpenAI 一直在探索防御性 AI 措施，包括安全协议和 AI 驱动的网络防御，作为其更广泛安全战略的一部分。“可扩展防御”的概念表明利用先进 AI 来对抗其他 AI 系统带来的威胁，这是 AI 社区日益争论的话题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Artificial_intelligence">Artificial intelligence - Wikipedia</a></li>
<li><a href="https://adaptiveaiinc.com/defining-a-well-aligned-ai/">Defining a well- aligned AI - Adaptive. AI</a></li>
<li><a href="https://www.analyticsvidhya.com/blog/2024/05/openai-security-measures/">6 Latest OpenAI Security Measures for Advanced AI Infrastructure</a></li>

</ul>
</details>

**标签**: `#AI safety`, `#OpenAI`, `#AI ethics`, `#AI policy`

---

<a id="item-13"></a>
## [DNS 滥用：新通用顶级域名中高达 20%是诈骗](https://simonwillison.net/2026/Sep/6/the-purpose-of-dns-is-to-spread-scams/) ⭐️ 7.0/10

Terence Eden 认为域名系统（DNS）是诈骗的主要载体，引用 Interisle 报告指出，2025 年新增的 8500 万个通用顶级域名（gTLD）注册中，到 2025 年 5 月已有 850 万个被列入黑名单，滥用率可能在 10%至 20%之间。 这凸显了互联网基础设施中一个重大且被低估的问题，对网络安全和政策具有广泛影响。随着 ICANN 准备在 2027 年引入新的开放通用顶级域名，滥用规模引发了对加强监管和缓解措施的迫切关注。 Interisle 报告估计，2025 年网络犯罪分子约占所有新通用顶级域名注册的 20%，滥用集中在域名廉价且易于获取的地方。ICANN 多年来一直在讨论这个问题，但问题依然存在。

rss · Simon Willison · 9月6日 14:40

**背景**: 域名系统（DNS）将人类可读的域名转换为 IP 地址，是互联网导航的基础。通用顶级域名（gTLD）是如.com、.org 以及较新的如.xyz 等类别。网络犯罪分子常注册域名用于钓鱼、恶意软件和诈骗，而黑名单用于识别和缓解此类滥用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://interisle.net/insights/cybercriminaldomaindemand">Malicious Registrations in the Domain ... — Interisle Consulting Group</a></li>
<li><a href="https://circleid.com/posts/cybercriminals-are-driving-significant-domain-name-market-demand">Cybercriminals are Driving Significant Domain Name Market Demand</a></li>
<li><a href="https://www.einnews.com/pr_news/916015197/interisle-study-finds-malicious-actors-accounted-for-10-20-of-new-domain-name-registrations-in-2025">Interisle Study Finds Malicious Actors Accounted for 10-20% of New...</a></li>

</ul>
</details>

**标签**: `#DNS`, `#security`, `#scams`, `#internet governance`, `#cybercrime`

---

<a id="item-14"></a>
## [为什么从头重写软件通常会失败](https://simonwillison.net/2026/Sep/6/theres-no-limit-to-how-bad-code-can-get/) ⭐️ 7.0/10

Simon Willison 在 Lobste.rs 上发表评论，认为从头重写软件很少能成功，因为旧系统仍然是一个不断变化的目标，开发者会失去改进它的动力。他建议用自动化测试和有针对性的重构来加固旧系统。 这一见解对面临沉重技术债务的工程团队意义重大，因为它挑战了常见的“绿地重写”诱惑。它可以帮助公司避免代价高昂的失败项目，并鼓励更务实、渐进式的改进策略。 Willison 指出，重写开始后，旧系统仍在运行核心业务并需要变更，但其开发者缺乏动力去做超出最小努力的工作，导致债务不断增加。他引用 Will Larson 的文章《迁移：技术债务唯一可扩展的修复方法》作为负责任完成此过程的最佳资源，并建议自动化测试加针对性重构是成功率更高的替代方案。

rss · Simon Willison · 9月6日 09:08

**背景**: 技术债务是指由于现在选择简单的解决方案而不是需要更长时间的更好方法而导致的额外返工的隐含成本。从头重写通常被视为摆脱债务的一种方式，但经常失败，因为旧系统继续发展，新系统必须复制未记录的行为。增量迁移和重构通常是更有效的策略。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://neverrewrite.com/software-rewrite">Software Rewrites: Why They Fail and What to Do Instead</a></li>
<li><a href="https://dev.to/spectredevxyz/how-to-rewrite-your-software-system-without-stopping-your-business-1afe">How to Rewrite Your Software System Without Stopping Your ...</a></li>
<li><a href="https://microbians.io/blog/understanding-and-managing-technical-debt/">Understanding And Managing Technical Debt — Microbians Blog</a></li>

</ul>
</details>

**社区讨论**: Lobste.rs 上的讨论可能包含关于重写与维护之争的多元观点，有些人分享重写失败的个人经历，另一些人则提倡增量迁移。由于片段被截断，无法获得具体评论。

**标签**: `#software engineering`, `#technical debt`, `#rewrite`, `#legacy code`, `#project management`

---

<a id="item-15"></a>
## [llm 0.35 新增对 OpenAI GPT-6 Astra 的支持](https://simonwillison.net/2026/Sep/7/llm/) ⭐️ 6.0/10

llm 0.35 已发布，新增了对 OpenAI 新模型 GPT-6 Astra 的支持，模型标识为 'gpt-6-astra'。 此次更新使 llm 命令行工具保持与 OpenAI 最新模型的同步，让开发者能够轻松通过命令行使用 GPT-6 Astra 的高级功能。这反映了 LLM 生态系统的持续演进，以及该工具在简化前沿模型访问方面的重要作用。 发布说明仅提及新增了该模型，未列出其他更改。OpenAI 将 GPT-6 Astra 描述为其迄今最智能、最对齐的模型，在计算机使用、编程、网络安全和科学等领域具备最先进的能力。

rss · Simon Willison · 9月7日 23:54

**背景**: llm 是 Simon Willison 开发的一款流行的命令行工具和 Python 库，为与 OpenAI、Anthropic、Google 等众多大型语言模型交互提供了统一接口。它允许用户在终端中运行提示和管理模型，支持远程 API 和本地安装的模型。GPT-6 Astra 是 OpenAI 最新的旗舰模型，继承了早期 GPT 版本，并提供增强的推理和多模态能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/simonw/llm">GitHub - simonw/llm: Access large language models from the ...</a></li>
<li><a href="https://openai.com/index/gpt-6-astra/">GPT-6 Astra: A new generation of intelligence | OpenAI</a></li>
<li><a href="https://developers.openai.com/api/docs/models/gpt-6-astra">GPT-6 Astra Model | OpenAI API</a></li>

</ul>
</details>

**标签**: `#llm`, `#openai`, `#gpt-6-astra`, `#release`

---

<a id="item-16"></a>
## [用于博客的 WebAssembly FFMPEG 视频压缩器](https://simonwillison.net/2026/Sep/7/video-compressor/) ⭐️ 6.0/10

Simon Willison 分享了一个基于 WebAssembly 版 FFMPEG 构建的网页视频压缩工具，他用该工具优化了博客上的演示视频。该工具由 Claude Code for web 中的 Claude Fable 5.1 生成。 该工具展示了通过 WebAssembly 在浏览器中运行 FFMPEG 的实际应用场景，使开发者和内容创作者无需服务器端处理或安装软件即可压缩视频。它凸显了利用 WebAssembly 在 Web 应用中直接进行强大媒体处理的日益增长趋势。 该工具提供五个预设（最大、大、中、小、最小），输出尺寸为 854×370 或 640×276，CRF 质量设置为 22 至 28，音频比特率为 128 至 64 kbps。它还包含编码器速度、H.264 配置文件、30 fps 限制、剥离元数据、删除音频以及仅编码前 10 秒等选项。

rss · Simon Willison · 9月7日 18:29

**背景**: FFMPEG 是一个强大的命令行工具，用于处理视频、音频和其他多媒体文件。WebAssembly 允许将 C/C++代码编译后在 Web 浏览器中运行，而 ffmpeg.wasm 是 FFMPEG 的纯 WebAssembly/JavaScript 移植版。CRF（恒定速率因子）是一种基于质量的编码模式，数值越低表示质量越高、文件越大。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://ffmpegwasm.netlify.app/docs/overview/">Overview | ffmpeg .wasm</a></li>
<li><a href="https://github.com/ffmpegwasm/ffmpeg.wasm">GitHub - ffmpegwasm/ ffmpeg .wasm: FFmpeg for browser, powered by...</a></li>
<li><a href="https://fyletools.com/en/blog/video-compression-settings-guide">Video Compression Settings: CRF, Bitrate & Codec Cheat Sheet ...</a></li>

</ul>
</details>

**标签**: `#video compression`, `#FFMPEG`, `#WebAssembly`, `#developer tools`

---

<a id="item-17"></a>
## [用 GPT-6 Astra 构建的 Mercator 到 Equal Earth 动画过渡](https://simonwillison.net/2026/Sep/7/equal-earth/) ⭐️ 6.0/10

Simon Willison 发布了一个在 Mercator 和 Equal Earth 之间动画过渡的地图投影工具，使用 D3 和 ChatGPT Work 中的 GPT-6 Astra（medium）构建。该工具是在联合国最近就 Equal Earth 投影进行投票后发布的。 这展示了 AI 辅助编程在创建交互式地理空间可视化方面的能力日益增强，可能降低开发者的门槛。同时，它也突显了关于地图投影选择及其对公众对世界地理认知影响的持续讨论。 该过渡使用 D3 的投影插值，这要求两个投影在视口上都有良好的定义。该工具托管在 tools.simonwillison.net，并包含视频预览，同时分享了 ChatGPT 对话以保持透明。

rss · Simon Willison · 9月7日 16:24

**背景**: Equal Earth 投影是一种等积伪圆柱投影，于 2018 年发明，旨在保持陆地的相对大小，而 Mercator 投影则夸大了极地附近的面积。联合国的投票鼓励在教育和科技领域使用等积投影。D3 是一个用于数据可视化的 JavaScript 库，支持地图投影和过渡。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Equal_Earth_map_projection">Equal Earth map projection</a></li>
<li><a href="https://en.wikipedia.org/wiki/Mercator_projection">Mercator projection - Wikipedia</a></li>
<li><a href="https://observablehq.com/@d3/projection-transitions">Projection Transitions / D 3 | Observable</a></li>

</ul>
</details>

**标签**: `#geospatial`, `#D3`, `#AI-assisted coding`, `#map projections`

---