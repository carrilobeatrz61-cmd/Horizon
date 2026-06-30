---
layout: default
title: "Horizon Summary: 2026-06-30 (ZH)"
date: 2026-06-30
lang: zh
---

> 从 38 条内容中筛选出 14 条重要资讯。

---

1. [最高法院裁定地理围栏搜查令需受宪法保护](#item-1) ⭐️ 9.0/10
2. [Fil-C 实现内存安全的上下文切换](#item-2) ⭐️ 8.0/10
3. [LongCat-2.0：基于华为昇腾训练的 1.6T MoE 模型](#item-3) ⭐️ 8.0/10
4. [火箭实验室历史性收购铱星公司](#item-4) ⭐️ 8.0/10
5. [液态水两种结构的分子证据](#item-5) ⭐️ 8.0/10
6. [隐藏杂志被判 30 年引发言论自由警报](#item-6) ⭐️ 8.0/10
7. [百万护照信息从大麻店身份验证系统泄露](#item-7) ⭐️ 8.0/10
8. [韩国投资 1 万亿美元发展存储芯片和人形机器人](#item-8) ⭐️ 8.0/10
9. [Ornith-1.0：开源自脚手架编码大模型](#item-9) ⭐️ 8.0/10
10. [Jon Udell：翻转“智能体在环”叙事](#item-10) ⭐️ 8.0/10
11. [惠普与 OpenAI 启动 Frontier 战略合作](#item-11) ⭐️ 7.0/10
12. [Claude Code v2.1.196：组织模型、会话命名与安全修复](#item-12) ⭐️ 6.0/10
13. [OpenAI 绘制欧盟 AI 就业影响图谱](#item-13) ⭐️ 6.0/10
14. [Hack Your Summer：面向学生的免费四周冲刺项目](#item-14) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [最高法院裁定地理围栏搜查令需受宪法保护](https://www.theguardian.com/us-news/2026/jun/29/supreme-court-geofence-warrants-case-decision) ⭐️ 9.0/10

美国最高法院裁定，允许执法部门获取特定区域内所有设备位置数据的地理围栏搜查令，需受第四修正案的宪法保护。这一里程碑式裁决于 2026 年 6 月 29 日作出。 这一裁决通过限制无证大规模监控，显著影响数字隐私，并影响执法部门如何使用谷歌等科技公司的地理定位数据。它为数字时代的第四修正案保护树立了先例。 该案涉及一起银行抢劫案，谷歌提供了银行周围 150 米范围内、30 分钟时间窗口内 19 个账户的位置数据。法院认为，此类搜查令必须满足传统的可能原因和特定性要求。

hackernews · cdrnsf · 6月29日 15:54 · [社区讨论](https://news.ycombinator.com/item?id=48720924)

**背景**: 地理围栏搜查令，也称为反向位置搜查令，允许执法部门在谷歌 Sensorvault 等数据库中搜索虚拟边界内的所有设备。第四修正案保护公民免受不合理搜查和扣押，但其对数字数据的适用一直在演变。这一裁决澄清了地理围栏搜查令属于需要司法监督的搜查行为。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Geofence_warrant">Geofence warrant - Wikipedia</a></li>
<li><a href="https://www.congress.gov/crs_external_products/LSB/PDF/LSB11274/LSB11274.4.pdf">PDF Geofence Warrants and the Fourth Amendment - Congress.gov</a></li>
<li><a href="https://www.brennancenter.org/our-work/policy-solutions/fourth-amendment-digital-age">The Fourth Amendment in the Digital Age - Brennan Center for ...</a></li>

</ul>
</details>

**社区讨论**: 评论者以彼得雷乌斯案为例，说明即使没有手机也能识别个人，并讨论了该裁决对 Flock 等监控系统的影响。一些人惊讶于巴雷特大法官加入了少数意见，而另一些人则赞扬法院在意见书中引用了事实来源。

**标签**: `#privacy`, `#supreme court`, `#surveillance`, `#digital rights`, `#law`

---

<a id="item-2"></a>
## [Fil-C 实现内存安全的上下文切换](https://fil-c.org/context_switches) ⭐️ 8.0/10

Fil-C 通过管理栈内存和验证栈帧，引入了 setjmp/longjmp 和 ucontext 的内存安全实现，确保这些传统上不安全的 API 不会导致内存安全错误。 这很重要，因为 setjmp/longjmp 和 ucontext 在系统编程中广泛用于协程、纤程和错误处理，但它们以不安全著称。Fil-C 的方法在不破坏兼容性的情况下使这些 API 变得安全，有望提高 C 和 C++ 代码库的安全性。 Fil-C 使用胖指针和编译器强制控制流完整性来在 longjmp 期间验证栈帧，防止跳转到无效上下文。该实现还处理了使 setjmp/longjmp 棘手的寄存器分配和栈溢出复杂性。

hackernews · modeless · 6月30日 00:38 · [社区讨论](https://news.ycombinator.com/item?id=48727177)

**背景**: setjmp/longjmp 和 ucontext 是用于非局部跳转和上下文切换的低级 C API，但它们本质上不安全，因为它们可以跳转到无效的栈帧，导致内存损坏。Fil-C 是 C 和 C++ 的内存安全实现，使用运行时检查将所有内存安全错误捕获为 panic，且零逃生口。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://fil-c.org/context_switches">Memory Safe Context Switching - Fil-C</a></li>
<li><a href="https://micrologics.org/blog/memory-safe-context-switching-implementing-setjmp-and-longjmp-in-fil-c">Memory-Safe Context Switching: Implementing setjmp and ...</a></li>
<li><a href="https://github.com/pizlonator/fil-c">GitHub - pizlonator/fil-c: Fil-C: completely compatible ...</a></li>

</ul>
</details>

**社区讨论**: 评论者对深入的技术分析表示赞赏，其中一位表示希望自己几个月前就能读到。另一位指出 setjmp/longjmp 代码的风险范围通常超出内存安全，还有一位强调 ucontext 与现代纤程实现相比非常沉重。

**标签**: `#memory safety`, `#context switching`, `#C programming`, `#systems programming`

---

<a id="item-3"></a>
## [LongCat-2.0：基于华为昇腾训练的 1.6T MoE 模型](https://longcat.chat/blog/longcat-2.0/) ⭐️ 8.0/10

LongCat-2.0 是一个大规模混合专家（MoE）模型，总参数量达 1.6 万亿，激活参数量为 480 亿，已在华为昇腾 910C 集群上完成训练。该模型未开源。 这表明在非英伟达硬件（特别是华为昇腾集群）上训练超大规模 MoE 模型是可行的，可能降低 AI 开发对英伟达 GPU 的依赖。1.6 万亿的总参数量使其跻身有史以来最大的模型之列。 该模型采用 MoE 架构，总参数量 1.6 万亿，激活参数量 480 亿，即每个 token 仅激活部分专家。训练在数万个华为昇腾 910C AI ASIC 超级节点上进行，由于软件生态不如英伟达 CUDA 成熟，需要大量的基础设施工程投入。

hackernews · benjiro29 · 6月30日 00:30 · [社区讨论](https://news.ycombinator.com/item?id=48727116)

**背景**: 混合专家（MoE）是一种神经网络架构，将模型划分为多个“专家”子网络，并通过门控机制为每个输入仅激活部分专家，从而在较低计算成本下实现更大的总参数量。华为昇腾 910C 是中国设计的 AI 加速芯片，旨在替代英伟达 GPU，但其软件生态尚不成熟。该模型由美团（一家中国外卖和服务公司）开发。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mixture_of_experts">Mixture of experts - Wikipedia</a></li>
<li><a href="https://www.servethehome.com/huawei-ascend-910-provides-a-nvidia-ai-training-alternative/">Huawei Ascend 910 Provides a NVIDIA AI Training Alternative</a></li>
<li><a href="https://www.tomshardware.com/tech-industry/artificial-intelligence/deepseek-research-suggests-huaweis-ascend-910c-delivers-60-percent-nvidia-h100-inference-performance">DeepSeek research suggests Huawei 's Ascend 910 C delivers 60% of...</a></li>

</ul>
</details>

**社区讨论**: 社区评论强调在昇腾集群上训练的基础设施成就才是真正的新闻，部分用户测试了模型的推理能力，并注意到即使设置英文也会返回中文回复等问题。其他人对模型未开源表示失望，并希望其兼容 llama.cpp。

**标签**: `#MoE`, `#large language model`, `#Huawei Ascend`, `#AI infrastructure`, `#Chinese AI`

---

<a id="item-4"></a>
## [火箭实验室历史性收购铱星公司](https://investors.rocketlabcorp.com/news-releases/news-release-details/rocket-lab-acquire-iridium-historic-deal-creating-fully) ⭐️ 8.0/10

火箭实验室宣布将收购铱星通信公司，这是一项历史性交易，使该公司获得铱星的卫星频谱、制造能力以及一个保证的发射客户。 此次收购效仿了 SpaceX 的 Starlink 战略，即卫星星座提供稳定的发射需求以降低成本，并使火箭实验室成为一家垂直整合的航天公司，同时提供发射和卫星服务。 铱星运营着一个由 80 颗低地球轨道卫星组成的星座，提供全球语音和数据服务，并曾使用 SpaceX 的猎鹰 9 号火箭进行升级。火箭实验室将获得铱星的频谱权和卫星制造专业知识。

hackernews · everfrustrated · 6月29日 14:09 · [社区讨论](https://news.ycombinator.com/item?id=48719485)

**背景**: 火箭实验室是一家端到端的航天公司，提供电子火箭发射服务并制造卫星。铱星是一家卫星通信公司，以其可靠的全球网络而闻名，常用于偏远和极端环境。这笔交易将火箭实验室的发射能力与铱星成熟的卫星基础设施结合起来。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Iridium_satellite_constellation">Iridium satellite constellation - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Iridium_Communications">Iridium Communications - Wikipedia</a></li>
<li><a href="https://rocketlabcorp.com/">Rocket Lab | The Space Company | Rocket Lab</a></li>

</ul>
</details>

**社区讨论**: 社区评论强调了与 SpaceX Starlink 的战略相似性，指出有保证的发射客户有助于火箭实验室平滑市场波动。一些人担心更多卫星会增加太空碎片和大气影响，而另一些人则认为这是首席执行官 Peter Beck 的明智商业举措。

**标签**: `#space`, `#acquisition`, `#satellite`, `#Rocket Lab`, `#Iridium`

---

<a id="item-5"></a>
## [液态水两种结构的分子证据](https://phys.org/news/2026-06-scientists-molecular-evidence-liquid.html) ⭐️ 8.0/10

一项发表在《自然·物理》上的研究通过模拟提供了分子层面的证据，表明液态水并非单一均匀物质，而是两种不同局部结构不断变化的混合物。 这一发现支持了双态水模型，有助于解释水的反常特性（如密度最大值和高热容），对理解生物和化学过程至关重要。 模拟揭示了两种可相互转化的局部结构，它们在深度过冷水中的第二个临界点处终止，该区域因快速结晶而难以实验研究。

hackernews · wglb · 6月29日 22:18 · [社区讨论](https://news.ycombinator.com/item?id=48726073)

**背景**: 水表现出许多反常特性，如结冰时膨胀和在 4°C 时密度最大，这些特性偏离了典型液体。双态水模型提出液态水由两种相互转换的局部结构组成，从而解释这些反常现象。这项研究为该模型提供了直接的分子层面证据。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.nature.com/articles/s41567-026-03301-8">Evidence for the generic existence of two local structures in liquid water</a></li>
<li><a href="https://phys.org/news/2026-06-scientists-molecular-evidence-liquid.html">Scientists find molecular-level evidence for two structures in liquid water</a></li>

</ul>
</details>

**社区讨论**: 评论中既有兴奋也有怀疑，一些人注意到对水合壳和未来技术的潜在影响，而另一些人则将其与顺势疗法进行推测性类比。总体而言，讨论积极且富有洞察力，尽管有些评论偏离主题。

**标签**: `#physics`, `#water`, `#molecular structure`, `#materials science`

---

<a id="item-6"></a>
## [隐藏杂志被判 30 年引发言论自由警报](https://theintercept.com/2026/06/26/daniel-sanchez-estrada-zines-prairieland-free-speech/) ⭐️ 8.0/10

一名联邦法官因丹尼尔·桑切斯-埃斯特拉达隐藏联邦搜查令所寻找的杂志，判处其 30 年监禁，这些杂志与一场导致联邦探员被枪击的抗议活动有关。这些杂志已出版多年，该判决是一个更大案件的一部分，其中其他人因喷涂标语和燃放烟花被判处 70 至 100 年监禁。 此案引发严重的言论自由担忧，因为因隐藏杂志（一种自我出版、常具政治性的表达形式）而被判 30 年，可能为惩罚保护异见材料者树立寒蝉效应先例。同时，它突显了抗议相关案件中的量刑不公，可能阻碍未来的 activism。 30 年刑期是因妨碍司法公正，桑切斯-埃斯特拉达在其妻子被捕时按她的要求隐藏了文件。相关搜查令针对的是向 ICE 设施发射烟花以及导致一名联邦探员受伤的枪击事件的证据。批评者认为，鉴于隐藏印刷材料的非暴力性质，这一判决过于极端。

hackernews · xrd · 6月28日 21:42 · [社区讨论](https://news.ycombinator.com/item?id=48711981)

**背景**: 杂志是小众发行、自我出版的刊物，常涉及小众或政治话题，受言论自由保护。第一修正案通常禁止政府审查，但存在妨碍司法等例外。此案测试了保护言论与妨碍司法之间的界限，因为杂志本身是合法出版物。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Zine">Zine - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/United_States_free_speech_exceptions">United States free speech exceptions - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: Hacker News 上的评论者对 30 年刑期表示震惊，称其为言论自由的“大坝裂缝”。一些人认为量刑过重，而另一些人指出被告是隐藏暴力犯罪证据的从犯。少数人指出原始文章缺乏背景，暗示其可能带有党派偏见。

**标签**: `#free speech`, `#legal`, `#civil liberties`, `#sentencing`, `#hackernews`

---

<a id="item-7"></a>
## [百万护照信息从大麻店身份验证系统泄露](https://www.theverge.com/tech/947157/passports-data-breach-cannabis-club-systems-nefos-puffpal) ⭐️ 8.0/10

超过一百万份护照扫描件因欧洲大麻店年龄验证平台 PuffPal 遭入侵而在线泄露。数据因辅助系统存储不安全而暴露，并非主要攻击目标。 此次泄露凸显了一个关键安全模式：护照等高价值凭证常被存储在低安全性的辅助系统中，使其易受攻击。这强调了在第三方验证服务中加强数据最小化和安全实践的必要性。 此次泄露涉及 PuffPal，一个欧洲大麻零售商和俱乐部用于会员管理和年龄验证的平台。泄露的数据包括高分辨率护照扫描件，且一旦知道顺序 ID，系统无需身份验证即可访问数据。

hackernews · jruohonen · 6月28日 11:22 · [社区讨论](https://news.ycombinator.com/item?id=48706389)

**背景**: 辅助系统，例如大麻店的身份验证系统，通常处理敏感数据，但与主系统相比可能缺乏强大的安全性。此次泄露体现了攻击者如何瞄准数据链中的薄弱环节。护照是高价值凭证，因其被广泛用于身份验证，泄露后尤其危险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://coesecurity.com/ancillary-systems-are-high-value-targets/">Ancillary Systems Are High-Value Targets... | COE Security</a></li>
<li><a href="https://cannasecure.tech/the-biometric-trap-why-dispensary-id-scanners-are-triggering-devastating-privacy-lawsuits/">The Biometric Trap: Why Dispensary ID Scanners Are... | CannaSecure</a></li>

</ul>
</details>

**社区讨论**: 评论者对护照数据存储在低安全性系统中表示担忧，有人指出酒店经常复印护照却没有适当保护措施。另一评论者敦促读者联系国会代表讨论年龄验证法律，还有人对隐私与年龄验证之间的权衡提出批评。

**标签**: `#data breach`, `#security`, `#privacy`, `#identity theft`, `#credential management`

---

<a id="item-8"></a>
## [韩国投资 1 万亿美元发展存储芯片和人形机器人](https://arstechnica.com/ai/2026/06/south-korea-to-spend-1t-on-more-memory-chip-production-and-humanoid-robots/) ⭐️ 8.0/10

韩国宣布了一项 1 万亿美元的投资计划，用于扩大存储芯片产能并开发人形机器人，旨在巩固其在 AI 硬件领域的地位。 这笔巨额投资可能通过缓解当前的存储芯片短缺来重塑全球存储芯片市场，同时加速人形机器人的商业化，这是 AI 和机器人领域的关键前沿。 该投资中 5850 亿美元用于新建晶圆厂，其余用于机器人研发，此时正值 AI 数据中心对 HBM 需求推动的存储芯片短缺。批评者警告可能出现存储芯片产能过剩。

hackernews · jnord · 6月29日 22:21 · [社区讨论](https://news.ycombinator.com/item?id=48726102)

**背景**: 存储芯片，尤其是 DRAM 和 NAND，是计算机和服务器的关键组件。高带宽存储器（HBM）是一种用于 AI 加速器的专用类型。人形机器人旨在模仿人类形态并与人类环境互动，但其商业可行性仍不确定。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Humanoid_robot">Humanoid robot</a></li>
<li><a href="https://tech-insider.org/memory-chip-shortage-2026-ai-consumer-electronics/">Memory Chip Shortage 2026: HBM Takes 23% of DRAM Wafers</a></li>

</ul>
</details>

**社区讨论**: 评论者表达了不同观点：一些人担心存储芯片产能过剩，而另一些人则质疑将存储芯片与人形机器人混为一谈的逻辑，指出后者的价值不确定。人形形态的选择也引发了争论，一些人认为替代设计可能更优。

**标签**: `#semiconductors`, `#humanoid robots`, `#government investment`, `#AI hardware`

---

<a id="item-9"></a>
## [Ornith-1.0：开源自脚手架编码大模型](https://simonwillison.net/2026/Jun/29/ornith/#atom-everything) ⭐️ 8.0/10

DeepReinforce 发布了 Ornith-1.0 系列开源权重大模型（MIT 许可），参数规模从 9B 到 397B，在编码基准测试中达到开源模型最优水平。这些模型基于 Gemma 4 和 Qwen 3.5 进行后训练，两者均为 Apache 2.0 许可。 Ornith-1.0 引入了自脚手架机制，模型学会同时生成解决方案和任务特定的执行框架，减少了对人工设计智能体框架的依赖。这可能显著提升开源智能体编码能力，降低开发者的使用门槛。 模型系列包括 9B 密集、31B 密集、35B MoE 和 397B MoE 变体。早期用户报告显示其在智能体任务中表现强劲，例如导航代码库和执行多步工具调用，量化版本推理速度可达 103 tokens/秒。

rss · Simon Willison · 6月29日 16:17

**背景**: 智能体编码是指使用 AI 智能体自主执行软件开发任务，如代码生成、调试和测试。传统的基于大语言模型的智能体依赖人工编写的脚手架（执行框架）来协调工具调用。Ornith-1.0 展示的自脚手架技术允许模型为每个任务动态创建自己的脚手架，有望提高适应性和性能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://deep-reinforce.com/ornith_1_0.html">Ornith-1.0: Self-Scaffolding LLMs for Agentic Coding</a></li>
<li><a href="https://github.com/deepreinforce-ai/Ornith-1">GitHub - deepreinforce-ai/Ornith-1</a></li>
<li><a href="https://huggingface.co/collections/deepreinforce-ai/ornith-10">Ornith-1.0 - a deepreinforce-ai Collection - Hugging Face</a></li>

</ul>
</details>

**标签**: `#LLM`, `#open-source`, `#coding`, `#AI`, `#agentic`

---

<a id="item-10"></a>
## [Jon Udell：翻转“智能体在环”叙事](https://simonwillison.net/2026/Jun/28/jon-udell/#atom-everything) ⭐️ 8.0/10

Jon Udell 认为“人在环中”这一说法将权威让给了机器，他提议重新定义智能体软件开发：人类邀请 AI 智能体加入他们现有的工作流程，而不是被排除在外。 这种重新定义挑战了主流的“人在环中”范式，强调人类监督和 AI 智能体的协作整合，可能影响开发者和组织设计智能体工作流的方式。 Udell 的引文来自一篇题为“医生，当智能体创建不可审查的 PR 时很痛。别那样做”的博客文章，强调了保持智能体输出可审查和透明的重要性。

rss · Simon Willison · 6月28日 21:57

**背景**: 智能体软件开发涉及能够自主规划、编写、测试和修改代码的 AI 智能体。传统的“人在环中”模型将人类定位为智能体驱动过程中的监督者，而 Udell 倡导“智能体在环中”模型，即人类保持控制权，智能体是被邀请的参与者。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.agentic-dev.org/en/handbook/introduction/what-is-agentic-development">What is Agentic Development? — Handbook</a></li>
<li><a href="https://cloud.google.com/discover/what-is-agentic-coding">What is agentic coding? How it works and use cases</a></li>

</ul>
</details>

**标签**: `#agentic-software-development`, `#human-in-the-loop`, `#AI-agents`, `#software-engineering`, `#Jon-Udell`

---

<a id="item-11"></a>
## [惠普与 OpenAI 启动 Frontier 战略合作](https://openai.com/index/hp-frontier-partnership) ⭐️ 7.0/10

惠普公司宣布与 OpenAI 建立战略合作伙伴关系，将 OpenAI 的 Frontier 平台整合到客户体验、软件开发和企业运营中，全面部署 AI。 此次合作标志着前沿 AI 模型在企业中的大规模采用，可能改变大型企业将 AI 融入核心业务流程和面向客户服务的方式。 惠普将利用 OpenAI 的 Frontier 平台推动转型和增长计划，重点关注未来工作模式。合作包括企业级控制和安全部署。

rss · OpenAI News · 6月28日 17:00

**背景**: OpenAI 的 Frontier 平台提供先进的 AI 模型和企业级工具，支持安全部署。惠普是一家提供硬件、软件和服务的全球科技公司。此次合作建立在两家公司现有合作基础之上。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openai.com/index/hp-frontier-partnership/">HP Inc. launches Frontier strategic partnership with OpenAI</a></li>
<li><a href="https://www.hp.com/us-en/newsroom/press-releases/2026/open-ai-partnership.html">HP Inc. Launches Frontier Strategic Partnership with OpenAI to Fuel ...</a></li>
<li><a href="https://finance.yahoo.com/technology/ai/articles/hp-inc-launches-frontier-strategic-000000074.html">HP Inc. Launches Frontier Strategic Partnership with OpenAI to Fuel ...</a></li>

</ul>
</details>

**标签**: `#AI`, `#Enterprise`, `#Partnership`, `#OpenAI`, `#HP`

---

<a id="item-12"></a>
## [Claude Code v2.1.196：组织模型、会话命名与安全修复](https://github.com/anthropics/claude-code/releases/tag/v2.1.196) ⭐️ 6.0/10

Claude Code v2.1.196 新增了组织默认模型、可读的会话名称、可点击的文件附件，以及一项安全修复，防止从不受信任的工作空间自动启动 MCP 服务器。 此版本提升了企业可管理性和用户体验，同时修复了一个安全问题：MCP 服务器可能从已提交的配置文件中自动启动，从而执行不受信任的代码。 安全修复确保 `claude mcp list` 和 `get` 命令不再启动通过已提交的 `.claude/settings.json` 自批准的 `.mcp.json` 中定义的服务器；不受信任的工作空间现在显示“⏸ 待批准”。

rss · Claude Code Releases · 6月29日 23:27

**背景**: Claude Code 是 Anthropic 推出的 AI 编程助手，运行在终端中。MCP（模型上下文协议）服务器为 AI 提供额外的工具和数据。此前，仓库可以通过已提交的设置文件自动批准 MCP 服务器，如果仓库不受信任，这可能带来安全风险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://code.claude.com/docs/en/sessions">Manage sessions - Claude Code Docs</a></li>
<li><a href="https://claudelog.com/faqs/what-are-named-sessions-in-claude-code/">What are Named Sessions in Claude Code | ClaudeLog</a></li>

</ul>
</details>

**标签**: `#Claude Code`, `#release`, `#security`, `#MCP`

---

<a id="item-13"></a>
## [OpenAI 绘制欧盟 AI 就业影响图谱](https://openai.com/index/mapping-ai-jobs-transition-eu) ⭐️ 6.0/10

OpenAI 发布了一份报告，分析人工智能可能如何改变欧盟各职业，识别出面临自动化风险的岗位、可能增长的岗位以及工作流程将发生变化的岗位。 这份报告为政策制定者和企业提供了数据驱动的基础，以预测劳动力市场变化，并为人工智能时代的技能重塑和劳动力适应做好准备。 该报告绘制了欧盟各国具体职业的图谱，指出虽然一些工作可能被自动化，但许多其他工作将得到人工智能的增强，从而产生新的任务和角色。

rss · OpenAI News · 6月29日 07:00

**背景**: 人工智能越来越能够执行传统上由人类完成的任务，引发了人们对失业的担忧。然而，人工智能也创造了新的就业机会并提高了生产力。OpenAI 的这份报告通过对欧洲劳动力市场的详细分析，为正在进行的辩论做出了贡献。

**标签**: `#AI`, `#labor market`, `#Europe`, `#automation`

---

<a id="item-14"></a>
## [Hack Your Summer：面向学生的免费四周冲刺项目](https://simonwillison.net/2026/Jun/28/hack-your-summer/#atom-everything) ⭐️ 6.0/10

Hack Your Summer 是一个面向因实习短缺而受影响的本硕学生的免费四周生产冲刺项目，已宣布第二期将于 7 月 13 日开始，申请截止日期为 7 月 8 日。 该计划为未能获得稀缺实习机会的学生提供了替代途径，帮助他们构建真实项目并获得指导，从而提升就业竞争力。 该计划免费，面向本科生、研究生和应届毕业生，同时也在招募志愿者导师来支持参与者。

rss · Simon Willison · 6月28日 19:26

**背景**: 许多美国公司减少了招聘和实习生指导能力，导致今年夏季实习机会减少。Hack Your Summer 旨在通过提供有指导的结构化项目构建经验来填补这一空白。

**标签**: `#education`, `#internships`, `#student-projects`, `#summer-program`

---