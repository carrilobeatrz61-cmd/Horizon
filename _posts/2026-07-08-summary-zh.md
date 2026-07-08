---
layout: default
title: "Horizon Summary: 2026-07-08 (ZH)"
date: 2026-07-08
lang: zh
---

> 从 52 条内容中筛选出 10 条重要资讯。

---

1. [Tenda 路由器固件发现隐藏后门](#item-1) ⭐️ 8.0/10
2. [1986 年 SICP 视频讲座至今仍有价值](#item-2) ⭐️ 8.0/10
3. [欧盟聊天控制：大规模监控与隐私之争](#item-3) ⭐️ 8.0/10
4. [欧盟强制所有新车安装驾驶员监控摄像头](#item-4) ⭐️ 8.0/10
5. [AI 大语言模型发现 Cloudflare Circl 加密库 7 个漏洞](#item-5) ⭐️ 8.0/10
6. [sqlite-utils 4.0 新增数据库模式迁移功能](#item-6) ⭐️ 8.0/10
7. [卡西欧 F-91W 改装成蓝牙智能手表](#item-7) ⭐️ 8.0/10
8. [GAO：能源部过早排除更便宜的核清理方案](#item-8) ⭐️ 7.0/10
9. [Kokoro：本地、CPU 友好、高质量的 TTS 模型](#item-9) ⭐️ 7.0/10
10. [腾讯发布 Hy3：295B 参数 MoE 模型，Apache 2.0 许可](#item-10) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Tenda 路由器固件发现隐藏后门](https://kb.cert.org/vuls/id/213560) ⭐️ 8.0/10

CERT/CC 披露，多个版本的 Tenda 固件包含一个未记录的认证后门，可授予对 Web 管理界面的管理员访问权限。 该后门使数百万台 Tenda 网络设备面临远程入侵风险，对全球家庭和企业用户构成重大安全威胁。 该后门使用硬编码配置值'sys.rzadmin.password'，明文密码为'rzadmin'，在登录失败时绕过标准 MD5 认证。

hackernews · miniBill · 7月8日 00:08 · [社区讨论](https://news.ycombinator.com/item?id=48825749)

**背景**: Tenda 是一家中国网络设备制造商，生产路由器和交换机等产品。认证后门是固件中故意或无意留下的漏洞，允许未经授权访问设备管理界面。此类漏洞对经常不更新的 IoT 设备尤其危险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://kb.cert.org/vuls/id/213560">VU#213560 - Tenda firmware (multiple versions) contains hidden authentication backdoor</a></li>
<li><a href="https://thehackernews.com/2026/07/certcc-warns-of-hidden-admin-backdoor.html">CERT/CC Warns of Hidden Admin Backdoor in Tenda Router Firmware</a></li>
<li><a href="https://www.bleepingcomputer.com/news/security/hidden-backdoor-in-tenda-router-firmware-grants-admin-access/">Hidden backdoor in Tenda router firmware grants admin access</a></li>

</ul>
</details>

**社区讨论**: 社区评论显示，后门密码'rzadmin'早在 2022 年的一篇文章中就被披露。一些用户表达了对中国网络品牌的不信任，而另一些用户则主张使用通用硬件和 Linux 构建自定义路由器。

**标签**: `#security`, `#backdoor`, `#firmware`, `#vulnerability`, `#IoT`

---

<a id="item-2"></a>
## [1986 年 SICP 视频讲座至今仍有价值](https://ocw.mit.edu/courses/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video_galleries/video-lectures/) ⭐️ 8.0/10

麻省理工学院发布了 1986 年由 Harold Abelson 和 Gerald Jay Sussman 讲授的《计算机程序的构造和解释》（SICP）经典视频讲座。 这些讲座仍然是学习递归、抽象和编程语言设计等计算机科学基础概念的宝贵资源，并且持续吸引着社区的强烈关注。 这些讲座使用 Scheme 编程语言（Lisp 的一种方言），并托管在 MIT OpenCourseWare 上。一条社区评论建议使用 Racket 配合 sicp-manual 包作为 MIT Scheme 的现代替代方案。

hackernews · gjvc · 7月7日 23:57 · [社区讨论](https://news.ycombinator.com/item?id=48825664)

**背景**: SICP 是一本基础性的计算机科学教科书，首次出版于 1984 年，在黑客文化中被称为“魔法书”。它被用作 MIT 的计算机科学入门课程超过二十年。Scheme 是一种极简的函数式语言，支持词法作用域和尾调用优化，非常适合教授编程范式。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/SICP">SICP</a></li>
<li><a href="https://en.wikipedia.org/wiki/Scheme_(programming_language)">Scheme (programming language)</a></li>

</ul>
</details>

**社区讨论**: 一位评论者建议使用 Racket 配合 sicp-manual 包作为学习 SICP 的现代 Scheme 环境，这有助于避免与旧版 MIT Scheme 的兼容性问题。

**标签**: `#SICP`, `#computer science education`, `#programming paradigms`, `#MIT`, `#Scheme`

---

<a id="item-3"></a>
## [欧盟聊天控制：大规模监控与隐私之争](https://fightchatcontrol.eu/chat-control-overview) ⭐️ 8.0/10

欧盟的聊天控制 1.0 于 2026 年 4 月 3 日到期，结束了自愿扫描私人消息的法律依据，但聊天控制 2.0 的谈判仍在继续，旨在强制扫描所有私人通信以查找儿童性虐待材料。 该提案威胁到所有欧盟公民的端到端加密和隐私，可能为全球大规模监控私人通信树立先例，同时引发了安全与公民自由之间的激烈辩论。 聊天控制 1.0 允许在 ePrivacy 指令的临时豁免下进行自愿扫描；聊天控制 2.0 将要求强制扫描，包括加密消息，通过客户端扫描或其他破坏加密的方法。

hackernews · gasull · 7月7日 14:23 · [社区讨论](https://news.ycombinator.com/item?id=48818311)

**背景**: 欧盟的聊天控制法规，正式名称为儿童性虐待法规（CSAR），于 2022 年 5 月提出，旨在打击在线儿童性虐待材料。它从自愿扫描（1.0）演变为拟议的强制扫描制度（2.0），引发了对大规模监控和削弱加密的担忧。批评者认为它可能促成更广泛的监控并侵犯基本权利。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Chat_Control">Chat Control - Wikipedia</a></li>
<li><a href="https://stateofsurveillance.org/news/eu-chat-control-expires-april-3-scanning-ends-whats-next-2026/">Chat Control Is Dead. Long Live Chat Control. - State of ...</a></li>
<li><a href="https://fightchatcontrol.eu/chat-control-overview">Chat Control 1.0 vs 2.0 - Fight Chat Control</a></li>

</ul>
</details>

**社区讨论**: 评论者表示强烈反对，认为该提案是广泛的监控权力扩张，而非针对犯罪者的精准措施。一些人强调技术上的担忧，即它如何影响加密消息，指出客户端扫描可能损害所有用户的隐私。其他人将其与更广泛的民主威胁联系起来，例如试图禁止反对党。

**标签**: `#privacy`, `#surveillance`, `#EU legislation`, `#encryption`, `#civil liberties`

---

<a id="item-4"></a>
## [欧盟强制所有新车安装驾驶员监控摄像头](https://allaboutcookies.org/eu-mandatory-distracted-driver-system) ⭐️ 8.0/10

自 2025 年 7 月起，欧盟《通用安全法规》要求所有在欧盟销售的新车必须配备高级驾驶员分心警告系统，该系统使用驾驶员监控摄像头来追踪驾驶员的注意力。 该法规旨在减少因驾驶员分心导致的事故，每年可能在欧洲挽救数千人的生命。然而，它也引发了驾驶员和汽车爱好者对隐私和可用性的重大担忧。 该系统使用安装在转向柱上的红外摄像头，以每秒 60 帧的速度监控驾驶员的面部和眼睛，检测疲劳或分心迹象。它必须安装在所有新乘用车、卡车和客车上。

hackernews · nickslaughter02 · 7月7日 20:50 · [社区讨论](https://news.ycombinator.com/item?id=48823557)

**背景**: 驾驶员监控系统使用摄像头和传感器追踪驾驶员行为，如眼球运动和头部位置，以检测困倦或注意力不集中。欧盟的《通用安全法规》自 2022 年起分阶段实施，高级驾驶员分心警告要求于 2025 年 7 月对所有新车强制执行。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://eur-lex.europa.eu/eli/reg_impl/2025/1707/oj/eng">Implementing regulation - EU - 2025/1707 - EN - EUR-Lex</a></li>
<li><a href="https://smarteye.se/blog/the-general-safety-regulations-gsr-and-driver-monitoring-systems-dms/">How Driver Monitoring Systems (DMS) Are Being Made Mandatory ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Driver_monitoring_system">Driver monitoring system - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区评论褒贬不一：一些用户报告现有系统（如福特的 Blue Cruise）准确且有用，而另一些用户则抱怨恼人的误报和现代汽车的糟糕用户体验。有评论者将其与波音的警报问题相类比，警告说太多没有明确含义的蜂鸣声可能会让驾驶员感到困惑。

**标签**: `#regulation`, `#privacy`, `#automotive`, `#safety`, `#EU`

---

<a id="item-5"></a>
## [AI 大语言模型发现 Cloudflare Circl 加密库 7 个漏洞](https://blog.zksecurity.xyz/posts/circl-bugs/) ⭐️ 8.0/10

研究人员利用 AI 大语言模型（LLMs）在 Cloudflare 的 Circl 加密库中发现了 7 个漏洞，展示了一种新颖的安全审计方法。 这标志着 AI 在密码学漏洞发现中的实际应用，有望降低安全审计的成本和时间，同时提高覆盖范围。 这些漏洞包括 CP-ABE 访问控制破坏以及加密实现中浮点运算的误用等问题。人工参与的验证环节对于过滤 AI 生成的候选结果中的误报至关重要。

hackernews · duha · 7月7日 18:36 · [社区讨论](https://news.ycombinator.com/item?id=48821749)

**背景**: Cloudflare 的 Circl（Cloudflare 可互操作、可重用加密库）是一个 Go 语言库，提供后量子密码学和椭圆曲线密码学原语。基于 AI 的漏洞发现是一个新兴领域，像 Chai 这样的系统也致力于检测密码学误用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/cloudflare/circl">GitHub - cloudflare/circl: CIRCL: Cloudflare Interoperable ...</a></li>
<li><a href="https://blog.cloudflare.com/introducing-circl/">Introducing CIRCL: An Advanced Cryptographic Library</a></li>
<li><a href="https://arxiv.org/abs/2606.26933v1">[2606.26933v1] Chai: Agentic Discovery of Cryptographic Misuse Vulnerabilities</a></li>

</ul>
</details>

**社区讨论**: 评论者赞赏该工作没有营销炒作，并询问了 AI 生成的候选结果与真实漏洞的比例。一位评论者对加密实现中使用浮点运算表示惊讶。

**标签**: `#AI`, `#cryptography`, `#security`, `#vulnerability discovery`, `#Cloudflare`

---

<a id="item-6"></a>
## [sqlite-utils 4.0 新增数据库模式迁移功能](https://simonwillison.net/2026/Jul/7/sqlite-utils-4/#atom-everything) ⭐️ 8.0/10

2026 年 7 月 7 日发布的 sqlite-utils 4.0 引入了数据库模式迁移、通过新 db.atomic() 方法实现的嵌套事务，以及对复合外键的支持。 这是自 2020 年以来的首个主版本更新，增加了以编程方式管理 SQLite 数据库模式的关键功能，简化了在 Python 中使用 SQLite 的开发者的工作流程。 迁移通过 sqlite-utils 库定义为 Python 函数，利用 table.transform() 方法进行 SQLite 的 ALTER TABLE 无法处理的模式更改。该版本还包含升级指南中记录的破坏性变更。

rss · Simon Willison · 7月7日 19:32

**背景**: SQLite 是一种轻量级、基于文件的数据库引擎，广泛应用于嵌入式系统和应用程序中。模式迁移是一种在不丢失数据的情况下随时间演变数据库结构的方法，这在大型数据库系统中很常见，但之前 SQLite 需要借助外部工具。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://simonwillison.net/2026/Jul/7/sqlite-utils-4/">sqlite-utils 4.0, now with database schema migrations</a></li>
<li><a href="https://sqlite-utils.datasette.io/en/latest/migrations.html">Database migrations - sqlite-utils</a></li>
<li><a href="https://github.com/simonw/sqlite-utils">GitHub - simonw/sqlite-utils: Python CLI utility and library ... Managing Database Versions and Migrations in SQLite SQLite Versioning & Migration Strategies for Evolving Apps sqlite-utils 4.0, now with database schema migrations #Shorts sqlite-utils 4.0rc1 adds migrations and nested transactions</a></li>

</ul>
</details>

**标签**: `#sqlite`, `#python`, `#database`, `#migrations`, `#open source`

---

<a id="item-7"></a>
## [卡西欧 F-91W 改装成蓝牙智能手表](https://www.reddit.com/r/SideProject/comments/1uq1iu0/turned_a_casio_f91w_into_a_bluetooth_watch_with/) ⭐️ 8.0/10

一位创客用定制 PCB 替换了卡西欧 F-91W 的原装模块，该 PCB 包含 TI 蓝牙芯片和 OLED 显示屏，运行自定义固件，通过 Gadgetbridge 支持通知、天气和媒体控制，无需依赖云端。 该项目展示了一种注重隐私、开源的手表设计方法，证明经典手表外壳可以升级现代功能，同时保持数据本地化，避免厂商锁定。 固件运行在 TI-RTOS 上，带有小型屏幕框架，可循环显示时钟、通知、计时器、秒表、音乐遥控、天气、手电筒和查找手机模式。纽扣电池续航超过五周，手表无需手机也可独立使用。

reddit · r/SideProject · /u/F91-Kepler · 7月7日 17:17

**背景**: 卡西欧 F-91W 是一款以耐用和低价著称的经典数字手表。PegorK 的 F91 Kepler 开源项目提供了启发此改装的硬件设计。Gadgetbridge 是一款 Android 应用，可替代厂商专用应用，无需云服务即可控制蓝牙设备。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/PegorK/F91_Kepler">GitHub - PegorK/F91_Kepler</a></li>
<li><a href="https://github.com/Freeyourgadget/Gadgetbridge">GitHub - Freeyourgadget/Gadgetbridge: We are on codeberg.org now! https://codeberg.org/Freeyourgadget/Gadgetbridge - Gadgetbridge - A free and cloudless replacement for your gadget vendors' closed source Android applications. Supports Pebble, Mi Band, Liveview, HPlus and more. · GitHub</a></li>
<li><a href="https://en.wikipedia.org/wiki/TI-RTOS">TI-RTOS</a></li>

</ul>
</details>

**社区讨论**: 制作者正在寻求反馈，询问人们是否会佩戴这样的设备、隐私是否重要以及缺少哪些功能。帖子还提到在德国小批量销售，表明潜在的商业兴趣。

**标签**: `#embedded systems`, `#bluetooth`, `#open source`, `#hardware hacking`, `#wearables`

---

<a id="item-8"></a>
## [GAO：能源部过早排除更便宜的核清理方案](https://www.gao.gov/products/gao-26-108193) ⭐️ 7.0/10

美国政府问责局（GAO）发布报告，批评能源部（DOE）过早排除更便宜的核废料清理方案，指出沟通不畅和成本问题。 该报告揭示了能源部清理策略中潜在的低效问题，可能导致数十亿美元的不必要支出。它还强调在环境修复中需要更好的监督和考虑成本效益替代方案。 GAO 发现，能源部在做出决定前未与利益相关者充分沟通，也未全面评估更便宜的替代方案。报告包含改进清理流程的可操作建议。

hackernews · Jimmc414 · 7月7日 22:23 · [社区讨论](https://news.ycombinator.com/item?id=48824826)

**背景**: 能源部管理着世界上最大的核清理项目之一，处理数十年来核武器生产和能源研究造成的污染。GAO 定期审计联邦项目，以确保效率和问责制。

**社区讨论**: 评论者赞扬 GAO 清晰的沟通和可操作的建议，有人称其为质量审计人员的榜样。其他人则对长期封存的可行性以及核清理的整体经济性表示担忧。

**标签**: `#nuclear cleanup`, `#government oversight`, `#policy`, `#environmental remediation`

---

<a id="item-9"></a>
## [Kokoro：本地、CPU 友好、高质量的 TTS 模型](https://ariya.io/2026/03/local-cpu-friendly-high-quality-tts-text-to-speech-with-kokoro/) ⭐️ 7.0/10

Kokoro 是一个拥有 8200 万参数的开源权重 TTS 模型，无需 GPU 即可在 CPU 上高效运行，实现本地高质量语音合成。 这使得没有专用 GPU 的用户也能使用高质量 TTS，为无障碍产品、内容消费等场景普及语音合成技术。 Kokoro 支持多语言、语音混合以及 EPUB、PDF 等多种输入格式。它还允许手动添加 IPA 发音指南，以纠正同形异义词错误。

hackernews · speckx · 7月7日 18:24 · [社区讨论](https://news.ycombinator.com/item?id=48821576)

**背景**: 传统高质量 TTS 模型通常需要强大的 GPU，限制了在普通硬件上的使用。Kokoro 的 8200 万参数设计在质量和效率之间取得平衡，能够在 CPU 上实现实时或近实时合成。它属于日益增长的轻量级本地 AI 模型趋势的一部分，有助于保护隐私并减少对云端的依赖。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/hexgrad/kokoro">GitHub - hexgrad/kokoro: https://hf.co/hexgrad/Kokoro-82M</a></li>
<li><a href="https://www.explainx.ai/blog/kokoro-local-cpu-tts-openai-compatible-guide-2026">Kokoro TTS — Local CPU Speech Guide 2026 | explainx.ai Blog</a></li>
<li><a href="https://openvoxai.com/blog/run-local-tts-without-gpu-low-end-systems">How to Run Local TTS Without a GPU on Low-End Systems</a></li>

</ul>
</details>

**社区讨论**: 社区成员报告在无障碍产品和文章阅读器中成功使用，称赞其无需 GPU 和 IPA 发音控制功能。有人指出在单词语音和同形异义词消歧方面存在局限，但存在手动 IPA 指南等变通方法。

**标签**: `#TTS`, `#local AI`, `#accessibility`, `#open source`, `#GPU-free`

---

<a id="item-10"></a>
## [腾讯发布 Hy3：295B 参数 MoE 模型，Apache 2.0 许可](https://simonwillison.net/2026/Jul/6/hy3/#atom-everything) ⭐️ 7.0/10

腾讯发布了 Hy3，这是一个 2950 亿参数的混合专家（MoE）模型，拥有 210 亿活跃参数，采用 Apache 2.0 许可证。其性能优于同类模型，并可媲美参数规模大 2-5 倍的模型。 此次发布展示了腾讯在开源 AI 领域的重大投入，提供了一个高效且能与更大规模专有模型竞争的 MoE 模型。鉴于其宽松的许可证，这可能加速 AI 在产品和研究中的应用。 完整模型在 Hugging Face 上为 598GB，FP8 量化版本为 300GB，支持 256K 上下文长度。在 OpenRouter 上可免费使用至 2026 年 7 月 21 日。

rss · Simon Willison · 7月6日 23:57

**背景**: 混合专家（MoE）是一种机器学习技术，每个输入只激活多个专家子网络中的一部分，从而在降低计算成本的同时实现大量总参数。FP8 量化通过使用 8 位浮点数代替更高精度来减小模型大小并加速推理。Apache 2.0 许可证允许自由使用、修改和分发。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mixture_of_experts">Mixture of experts - Wikipedia</a></li>
<li><a href="https://huggingface.co/blog/moe">Mixture of Experts Explained - Hugging Face</a></li>
<li><a href="https://www.spheron.network/blog/fp8-quantization-inference-performance-hardware-explained/">What is FP8 Quantization? AI Inference Performance, Accuracy, and Hardware Support Explained (2026) | Spheron Blog</a></li>

</ul>
</details>

**标签**: `#AI`, `#open-source`, `#LLM`, `#MoE`, `#Tencent`

---