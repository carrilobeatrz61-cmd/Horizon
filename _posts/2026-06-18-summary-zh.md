---
layout: default
title: "Horizon Summary: 2026-06-18 (ZH)"
date: 2026-06-18
lang: zh
---

> 从 48 条内容中筛选出 15 条重要资讯。

---

1. [GLM-5.2：新的开源权重 LLM 领导者](#item-1) ⭐️ 9.0/10
2. [Epic Games 开源面向大型二进制文件的版本控制系统 Lore](#item-2) ⭐️ 8.0/10
3. [美国推迟将 DeepSeek 列入黑名单，标记超 100 家中国公司](#item-3) ⭐️ 8.0/10
4. [Glojure：在 Go 上运行 Clojure，实现完全互操作](#item-4) ⭐️ 8.0/10
5. [Adam (YC W25) 推出开源 AI CAD 平台](#item-5) ⭐️ 8.0/10
6. [马德里如何低成本建造地铁](#item-6) ⭐️ 8.0/10
7. [RFC 10008 引入 HTTP QUERY 方法](#item-7) ⭐️ 8.0/10
8. [乐购因博通定价将迁移 4 万个工作负载离开 VMware](#item-8) ⭐️ 8.0/10
9. [美国科学陷入危机：资金削减与签证限制](#item-9) ⭐️ 8.0/10
10. [搭载 GPT-5.4 的 AI 化学家改进药物合成反应](#item-10) ⭐️ 8.0/10
11. [OpenAI 推出 LifeSciBench，评估 AI 在生命科学中的表现](#item-11) ⭐️ 8.0/10
12. [Charity Majors：AI 让代码变成一次性用品，要求更高工程纪律](#item-12) ⭐️ 8.0/10
13. [Datasette 1.0a34 新增 CRUD 界面](#item-13) ⭐️ 7.0/10
14. [Georgi Gerganov 认可 Qwen3.6-27B 用于本地编程](#item-14) ⭐️ 7.0/10
15. [Codex v0.141.0 新增加密中继通道](#item-15) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [GLM-5.2：新的开源权重 LLM 领导者](https://simonwillison.net/2026/Jun/17/glm-52/#atom-everything) ⭐️ 9.0/10

Z.ai 发布了 GLM-5.2，这是一个 753B 参数的混合专家模型，拥有 40 个活跃专家和 100 万 token 的上下文窗口，采用 MIT 许可证。 GLM-5.2 在 Artificial Analysis Intelligence Index 上成为领先的开源权重模型，超越了 MiniMax-M3 和 DeepSeek V4 Pro，并在 Code Arena WebDev 上排名第二，使前沿水平的 AI 更加易于获取。 该模型每个任务平均使用 43k 输出 token，高于竞争对手，通过 OpenRouter 的定价为输入 $1.40/M、输出 $4.40/M，远低于 GPT-5.5 和 Claude Opus。

rss · Simon Willison · 6月17日 23:58

**背景**: 混合专家（MoE）是一种架构，每个 token 只激活一部分参数（专家），使得大型模型能够高效运行。开源权重模型公开发布训练好的参数，允许任何人使用或修改，但不一定包含训练数据或代码。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://artificialanalysis.ai/articles/glm-5-2-is-the-new-leading-open-weights-model-on-the-artificial-analysis-intelligence-index">GLM-5.2 is the new leading open weights model on the Artificial Analysis Intelligence Index</a></li>
<li><a href="https://huggingface.co/zai-org/GLM-5.2">zai-org/GLM-5.2 · Hugging Face</a></li>
<li><a href="https://developer.nvidia.com/blog/applying-mixture-of-experts-in-llm-architectures/">Applying Mixture of Experts in LLM Architectures | NVIDIA Technical...</a></li>

</ul>
</details>

**社区讨论**: 社区成员称赞该模型的性能和低成本，有人指出它可与 Opus 等专有模型相媲美。但也有人对推理效率表示担忧，一位用户报告称一个简单的编程任务需要 15 分钟的推理时间，另一位用户则指出其 token 使用量高于竞争对手。

**标签**: `#LLM`, `#open-weights`, `#AI`, `#GLM-5.2`, `#benchmarks`

---

<a id="item-2"></a>
## [Epic Games 开源面向大型二进制文件的版本控制系统 Lore](https://lore.org/) ⭐️ 8.0/10

Epic Games 宣布并开源了 Lore，这是一个专为处理大型二进制文件而设计、面向游戏开发可扩展的新型版本控制系统，直接与 Perforce 竞争。 Lore 填补了游戏开发领域开源版本控制系统的长期空白——Git 难以处理二进制文件，而 Perforce 是专有且昂贵的。这可能降低独立工作室的门槛，并促进游戏资产协作方面的创新。 Lore 完全采用 MIT 许可证开源，托管在 GitHub 的 EpicGames/lore 仓库中。它具备可变键值存储、子仓库链接和按目录访问控制等特性，针对 Unreal Engine 工作流进行了优化。

hackernews · regnerba · 6月17日 14:30 · [社区讨论](https://news.ycombinator.com/item?id=48571081)

**背景**: 版本控制系统（VCS）用于跟踪文件随时间的变化。Git 擅长处理基于文本的代码，但在处理纹理、3D 模型等大型二进制文件时表现不佳，而这些在游戏开发中很常见。Perforce（Helix Core）因其对大型文件、文件锁定和权限的支持而成为游戏工作室的行业标准，但它是专有的且管理复杂。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/EpicGames/lore">GitHub - EpicGames/ lore : Lore is a next-generation, open source...</a></li>
<li><a href="https://www.phoronix.com/news/Epic-Games-Lore-VCS">Epic Games Announces Lore Open-Source Version Control System</a></li>
<li><a href="https://epicgames.github.io/lore/explanation/system-design/">The Lore Version Control System - Lore Developer Documentation</a></li>

</ul>
</details>

**社区讨论**: Hacker News 社区普遍欢迎 Lore，认为它是 Perforce 急需的挑战者，尤其对于 Unreal Engine 开发。评论者指出 Git 的用户界面不友好，Perforce 也显露出年代感，而 Lore 的开源性质和对游戏特定需求的关注被视为主要优势。

**标签**: `#version control`, `#game development`, `#open source`, `#scalability`, `#Perforce`

---

<a id="item-3"></a>
## [美国推迟将 DeepSeek 列入黑名单，标记超 100 家中国公司](https://www.reuters.com/world/china/us-holds-off-blacklisting-chinas-deepseek-more-than-100-firms-deemed-security-2026-06-17/) ⭐️ 8.0/10

美国商务部推迟将 DeepSeek 列入实体清单，但将超过 100 家中国公司列为安全风险，可能限制它们获取美国技术和商品。 这一决定影响全球 AI 格局，因为 DeepSeek 的廉价模型被开发者广泛使用；进一步限制可能扰乱访问并加剧美中科技紧张局势。 实体清单自 2025 年 10 月以来未更新，是十多年来最长的间隔；被列入并不禁止所有贸易——美国公司仍可从被列实体购买，但向它们销售需要许可证。

hackernews · giuliomagnifico · 6月17日 03:55 · [社区讨论](https://news.ycombinator.com/item?id=48565498)

**背景**: 实体清单是美国贸易限制工具，限制向指定组织出口商品、软件和技术，除非获得政府许可证。DeepSeek 是一家中国 AI 公司，以开发成本效益高、可与西方同行竞争的大型语言模型而闻名。美国出于国家安全考虑，越来越多地针对中国科技公司，尤其是在 AI 和半导体领域。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek">DeepSeek - Wikipedia</a></li>
<li><a href="https://slguardian.org/us-delays-blacklisting-deepseek-and-more-than-100-chinese-firms-flagged-as-security-risks/">US Delays Blacklisting DeepSeek and More Than 100 Chinese ...</a></li>
<li><a href="https://www.malaymail.com/news/world/2026/06/18/deepseek-cxmt-among-chinese-firms-awaiting-us-entity-list-action-as-washington-weighs-trade-risks/224127">DeepSeek, CXMT among Chinese firms awaiting US Entity List ...</a></li>

</ul>
</details>

**社区讨论**: 评论者表达了不同观点：一些人称赞 DeepSeek 的实用性和经济性，另一些人批评美国的执法虚伪或无效。有人质疑封锁中国 AI 服务的可行性，并担心出现“美国版防火墙”。

**标签**: `#AI`, `#geopolitics`, `#DeepSeek`, `#US-China`, `#regulation`

---

<a id="item-4"></a>
## [Glojure：在 Go 上运行 Clojure，实现完全互操作](https://github.com/glojurelang/glojure) ⭐️ 8.0/10

Glojure 是一个托管在 Go 上的 Clojure 解释器，提供与 Go 代码的完全互操作，使开发者能够从 Clojure 利用 Go 的运行时和生态系统。 这使得 Clojure 开发者能够利用 Go 的性能、并发模型和丰富的库生态系统，可能拓宽 Clojure 在系统编程和云原生应用中的使用场景。 Glojure 是一个解释器而非编译器，意味着它不将 Clojure 编译为 Go 字节码，而是直接解释执行，这可能影响 REPL 性能。该项目在两个仓库中维护：glojurelang/glojure 和 gloathub/glojure，保持同步。

hackernews · dnlo · 6月17日 23:14 · [社区讨论](https://news.ycombinator.com/item?id=48578326)

**背景**: Clojure 是一种函数式 Lisp 方言，运行在 JVM、CLR 和 JavaScript 上。Go 是一种静态类型编译语言，以其简单性和并发性著称。将 Clojure 托管在 Go 上，可以结合 Clojure 的表达力与 Go 的性能和生态系统，类似于 ClojureScript 针对 JavaScript 的方式。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/glojurelang/glojure">GitHub - glojurelang/glojure: Clojure interpreter hosted on Go , with...</a></li>
<li><a href="https://github.com/chr15m/awesome-clojure-likes">GitHub - chr15m/awesome- clojure -likes: Curated list of Clojure -like...</a></li>
<li><a href="https://thecodersblog.com/clojure-like-language-in-go-with-7ms-boot-time-2026/">Clojure -like Language in Go Boasts Blazing... | The Coders Blog | Home</a></li>

</ul>
</details>

**社区讨论**: 社区成员称赞 Glojure 是最有前景的 Clojure-on-Go 实现，因为它具有完全的互操作性。有人质疑 REPL 机制，指出 Go 的 REPL 通常很慢，因为需要编译。其他人则提到了替代项目，如 let-go 和 Lisette，用于在 Go 上进行类型化函数式编程。

**标签**: `#Clojure`, `#Go`, `#language implementation`, `#interop`, `#functional programming`

---

<a id="item-5"></a>
## [Adam (YC W25) 推出开源 AI CAD 平台](https://github.com/Adam-CAD/CADAM) ⭐️ 8.0/10

Adam (YC W25) 发布了 CADAM，这是一个开源的文本转 CAD 网络应用，能够通过基于代码的范式（使用 OpenSCAD）从自然语言提示生成参数化 3D 模型。 这代表了机械 CAD 设计的一种新方法，可能降低快速原型制作的门槛，使非专业人士能够通过简单的文本描述创建 3D 模型，从而加速 3D 打印和工程社区的设计工作流程。 CADAM 生成带有自动提取参数的 OpenSCAD 代码，这些参数以交互式滑块形式呈现，可即时调整尺寸，并支持多种导出格式，包括 STL、SCAD、OBJ、GLB/GLTF、FBX 和 DXF。该系统通过将 OpenSCAD 编译为 WebAssembly 并在浏览器中完全运行，使用 React Three Fiber 通过 Three.js 进行渲染。

hackernews · zachdive · 6月17日 16:14 · [社区讨论](https://news.ycombinator.com/item?id=48572553)

**背景**: 传统的 CAD 软件需要使用复杂的界面进行手动建模，既耗时又学习曲线陡峭。基于代码的 CAD 方法（如 OpenSCAD）允许用户通过编程方式定义模型，提供精确性和参数化控制。CADAM 将这种方法与 AI 结合，从自然语言生成代码，使其对更广泛的用户群体更加易用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/Adam-CAD/CADAM">GitHub - Adam- CAD / CADAM : CADAM is the open source ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/CADAM">CADAM - Wikipedia</a></li>
<li><a href="https://sourceforge.net/projects/cadam.mirror/">CADAM download | SourceForge.net</a></li>

</ul>
</details>

**社区讨论**: 社区讨论显示出不同的反应：一些工程师对 AI 在精密机械设计中的可靠性表示怀疑，认为手动建模更快且更可靠。然而，其他用户报告了特定提示的成功结果，并且对照片转 CAD 功能以及与现有工具的集成表现出兴趣。

**标签**: `#AI`, `#CAD`, `#open-source`, `#mechanical-design`, `#YC`

---

<a id="item-6"></a>
## [马德里如何低成本建造地铁](https://worksinprogress.co/issue/how-madrid-built-its-metro-cheaply/) ⭐️ 8.0/10

2024 年的一项分析揭示，马德里通过依靠内部工程团队和稳定的项目领导层，以低成本扩建了地铁系统，避免了美国和英国常见的昂贵咨询模式。 这种方法为困扰美国交通项目的成本超支和延误提供了经过验证的替代方案，表明公共机构可以建立专业知识并高效交付基础设施。 马德里地铁扩建在多个项目中保持核心团队不变，从而实现了学习和流程改进。内部工程师主导设计和施工，减少对外部顾问的依赖。

hackernews · trymas · 6月17日 19:59 · [社区讨论](https://news.ycombinator.com/item?id=48575997)

**背景**: 美国和英国的许多大型基础设施项目严重依赖外部顾问进行规划、设计和管理，这往往导致成本更高和知识碎片化。相比之下，马德里的模式将专业知识集中在公共机构内部，促进了连续性和问责制。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://cayimby.org/blog/when-the-bay-area-plans-public-transit-more-is-less/">When the Bay Area Plans Public Transit , We Want More for Less...</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，美国工资是马德里的 2-3 倍，部分解释了成本差异。其他人则指出湾区交通系统的碎片化以及新自由主义在私有化公共资产方面的历史影响，这削弱了内部专业知识。

**标签**: `#infrastructure`, `#public transit`, `#engineering`, `#cost efficiency`, `#urban planning`

---

<a id="item-7"></a>
## [RFC 10008 引入 HTTP QUERY 方法](https://www.rfc-editor.org/info/rfc10008/) ⭐️ 8.0/10

RFC 10008 正式定义了 HTTP QUERY 方法，这是一种安全且幂等的 GET 替代方案，允许携带请求体，从而在不产生 POST 副作用的情况下实现复杂查询。 这填补了 HTTP 在安全、幂等且带请求体的请求方面的长期空白，改善了现代 Web 服务的缓存、重试语义和 API 设计。 QUERY 类似于 POST，但保证安全性和幂等性，使其适合缓存和自动重试。RFC 建议支持最长 8000 八位字节的 URI。

hackernews · schappim · 6月17日 10:51 · [社区讨论](https://news.ycombinator.com/item?id=48568502)

**背景**: HTTP GET 请求安全且幂等，但不能携带请求体，复杂查询只能通过 URL 参数实现。POST 请求允许请求体，但不安全也不幂等，导致缓存和重试问题。QUERY 通过提供既安全又幂等且支持请求体的方法，弥补了这一空白。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.rfc-editor.org/info/rfc10008/">RFC 10008 : The HTTP QUERY Method | RFC Editor</a></li>
<li><a href="https://httpwg.org/http-extensions/draft-ietf-httpbis-safe-method-w-body.html">The HTTP QUERY Method</a></li>
<li><a href="https://news.ycombinator.com/item?id=48568502">RFC 10008 : The new HTTP Query Method | Hacker News</a></li>

</ul>
</details>

**社区讨论**: 评论者讨论了需要强有力的示例、HTML 表单采用 QUERY 以避免重新提交警告的可能性，以及历史上使用带请求体的 GET 的做法。一些人指出，将请求体纳入缓存键对缓存策略构成了挑战。

**标签**: `#HTTP`, `#RFC`, `#web standards`, `#API design`, `#networking`

---

<a id="item-8"></a>
## [乐购因博通定价将迁移 4 万个工作负载离开 VMware](https://arstechnica.com/information-technology/2026/06/tesco-moving-40000-server-workloads-off-vmware-amid-broadcoms-abusive-conduct/) ⭐️ 8.0/10

英国最大的连锁超市乐购宣布，由于博通收购 VMware 后大幅提价并削减支持，该公司正在将 4 万个服务器工作负载从 VMware 迁移出去。 此举标志着大型企业拒绝博通收购后的策略，可能引发一波类似的迁移浪潮，并重塑虚拟化市场格局。 此次迁移涉及 4 万个工作负载，是公开已知的最大规模 VMware 迁移之一。乐购可能转向 Proxmox 或微软 Hyper-V 等替代方案，这些方案自博通调价以来已获得更多关注。

hackernews · Bender · 6月17日 21:00 · [社区讨论](https://news.ycombinator.com/item?id=48576838)

**背景**: 博通于 2023 年收购 VMware，随后将 VMware 的许可改为强制订阅制，设置 72 核最低要求，并取消了许多渠道合作伙伴，导致许多企业成本飙升。这些变化促使企业开始探索替代虚拟化平台。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://hystax.com/how-vmware-prices-and-policies-changed-after-broadcoms-acquisition/">How the Broadcom VMware Acquisition Changed VMware Pricing</a></li>
<li><a href="https://trilio.io/resources/vmware-license-cost/">VMware License Cost Changes: What You Need to Know</a></li>

</ul>
</details>

**社区讨论**: 社区评论指出博通惯于收购老牌企业、削减支持并提价。有人提到博通对 Proxmox 的营销很有效，且该公司正专注于 AI 交易，同时压榨传统客户。

**标签**: `#VMware`, `#Broadcom`, `#enterprise IT`, `#cloud migration`, `#vendor lock-in`

---

<a id="item-9"></a>
## [美国科学陷入危机：资金削减与签证限制](https://www.scientificamerican.com/article/americas-compact-between-science-and-politics-is-broken/) ⭐️ 8.0/10

美国科学研究因资金削减、签证限制和政治干预而严重受阻，导致人才外流和学术界危机。 这威胁到美国在科技领域的领导地位，削弱长期创新能力，并迫使有才华的研究人员离开美国。 资助项目因政治标准被取消或延迟，例如禁止涉及多样性、公平和包容（DEI）的表述，同时签证限制阻碍了外国研究生的招聘。

hackernews · presspot · 6月17日 09:54 · [社区讨论](https://news.ycombinator.com/item?id=48568058)

**背景**: 美国长期以来依赖科学与政治之间的契约，研究资助基本不受党派影响。近期的政治动荡打破了这一契约，资助决策日益政治化。

**社区讨论**: 评论者分享了研究人员离开美国、资助枯竭以及普遍危机感的个人故事。许多人表示情况近期恶化，一些科学家完全放弃了学术界。

**标签**: `#science policy`, `#research funding`, `#academia`, `#brain drain`, `#US politics`

---

<a id="item-10"></a>
## [搭载 GPT-5.4 的 AI 化学家改进药物合成反应](https://openai.com/index/ai-chemist-improves-reaction) ⭐️ 8.0/10

OpenAI 与 Molecule.one 展示了一款由 GPT-5.4 驱动的近乎自主的 AI 化学家，成功改进了药物化学中一项具有挑战性的反应。 这标志着向自动化药物发现迈出了重要一步，有望加速新药研发并降低成本。 该系统将 GPT-5.4 的推理能力与 Molecule.one 的逆合成预测软件相结合，自主设计并测试反应条件。

rss · OpenAI News · 6月17日 10:00

**背景**: 药物化学通常需要优化复杂的反应，这既耗时又依赖专家直觉。GPT-5.4 是 OpenAI 于 2026 年 3 月发布的大型语言模型，具备更强的推理和计算机使用能力。Molecule.one 开发用于逆合成预测的 AI——即预测如何从简单前体合成目标分子。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GPT-5.4">GPT-5.4</a></li>
<li><a href="https://molecule.one/">molecule . one - Making Molecules . Discovering Chemistry</a></li>

</ul>
</details>

**标签**: `#AI`, `#drug discovery`, `#chemistry`, `#GPT-5.4`, `#autonomous systems`

---

<a id="item-11"></a>
## [OpenAI 推出 LifeSciBench，评估 AI 在生命科学中的表现](https://openai.com/index/introducing-life-sci-bench) ⭐️ 8.0/10

OpenAI 推出了 LifeSciBench，这是一个包含 750 个专家编写任务的基准测试，旨在评估 AI 系统在真实世界生命科学研究中的表现，包括多步推理和决策。 LifeSciBench 提供了一个严格且经专家验证的评估框架，可推动 AI 辅助科学发现的进展，有望加速药物开发、基因组学和个性化医疗等领域的研究。 79% 的任务需要多步推理或决策，平均每个任务包含四个步骤，该基准同时评估最终答案的准确性和推理过程。目前测试过的最强 AI 模型仅通过了 36.1% 的任务。

rss · OpenAI News · 6月17日 00:00

**背景**: 像 MMLU 和 GPQA 这样的 AI 基准测试评估的是通用知识和推理能力，但很少有专注于生命科学中常见的复杂多步工作流。LifeSciBench 通过使用专家编写的评分标准来评估 AI 在真实研究任务（如实验规划和数据分析）上的表现，填补了这一空白。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.marktechpost.com/2026/06/17/openai-releases-lifescibench-a-750-task-benchmark-grading-ai-models-on-real-life-science-research-with-expert-written-rubric/">OpenAI Releases LifeSciBench, a 750-Task Benchmark Grading AI Models on Real Life-Science Research With Expert-Written Rubric - MarkTechPost</a></li>

</ul>
</details>

**标签**: `#AI`, `#benchmark`, `#life sciences`, `#OpenAI`, `#evaluation`

---

<a id="item-12"></a>
## [Charity Majors：AI 让代码变成一次性用品，要求更高工程纪律](https://simonwillison.net/2026/Jun/17/charity-majors/#atom-everything) ⭐️ 8.0/10

Charity Majors 认为，2025 年 AI 彻底改变了代码生产的经济学：生成代码变得几乎免费且即时，代码从珍贵的资产变成了可丢弃的商品。 这一转变要求更高的工程纪律，而非更少，因为开发者现在必须专注于系统设计、测试和集成，而不是逐行编写代码。 Majors 强调，代码现在可以再生和丢弃，这意味着价值在于架构和理解，而非代码本身。

rss · Simon Willison · 6月17日 17:12

**背景**: 历史上，编写代码是劳动密集且昂贵的，因此代码被精心制作和重用。随着生成式 AI 的出现，代码可以快速生成，开发者的角色从编写者转变为策展人和系统思考者。

**标签**: `#ai-assisted-programming`, `#software-engineering`, `#generative-ai`, `#economics-of-code`

---

<a id="item-13"></a>
## [Datasette 1.0a34 新增 CRUD 界面](https://simonwillison.net/2026/Jun/16/datasette/#atom-everything) ⭐️ 7.0/10

Datasette 1.0a34 在网页界面中直接引入了插入、编辑和删除行的功能，可在表格页面和行页面上使用。 这一期待已久的功能显著提升了易用性，让用户无需 SQL 知识即可管理数据，其灵感来自 Datasette Agent AI 助手。 该功能是 alpha 版本（1.0a34）的一部分，其动机是 Datasette Agent 已通过聊天支持 SQL 写入，使得缺乏 UI CRUD 操作的问题变得突出。

rss · Simon Willison · 6月16日 21:31

**背景**: Datasette 是一个开源工具，用于将数据作为交互式网站和 API 进行探索和发布。此前，网页界面仅允许只读操作，如过滤和查询；数据修改需要直接使用 SQL 或外部工具。Datasette Agent 是一个 AI 助手插件，可以通过自然语言执行 SQL 写入，这凸显了原生 CRUD 界面的缺失。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://agent.datasette.io/">Datasette Agent: an AI assistant for Datasette to help explore and analyze data in SQLite</a></li>
<li><a href="https://datasette.io/">Datasette : An open source multi-tool for exploring and publishing data</a></li>

</ul>
</details>

**标签**: `#datasette`, `#open-source`, `#database`, `#web-interface`, `#release`

---

<a id="item-14"></a>
## [Georgi Gerganov 认可 Qwen3.6-27B 用于本地编程](https://simonwillison.net/2026/Jun/16/georgi-gerganov/#atom-everything) ⭐️ 7.0/10

llama.cpp 的创建者 Georgi Gerganov 公开认可 Qwen3.6-27B 是一款非常强大的本地编程模型，并分享他几乎每天都在 M2 Ultra 或 RTX 5090 机器上使用它，配合极简的 pi agent 配置。 来自本地 LLM 生态关键人物的认可，验证了 Qwen3.6-27B 作为开发者实用工具的价值，可能加速本地编程助手的采用，减少对云端 AI 服务的依赖。 Gerganov 使用轻量级框架，配合离线模式的 pi agent（pi -nc --offline）和简短的系统提示词来对齐模型的编程风格。Qwen3.6-27B 是一个 270 亿参数的密集模型，在编程基准测试上优于更大的 MoE 模型。

rss · Simon Willison · 6月16日 16:04

**背景**: Qwen3.6-27B 是阿里巴巴 Qwen 团队于 2026 年 4 月发布的密集开源权重模型，以强大的编程和推理能力著称。llama.cpp 由 Georgi Gerganov 创建，是本地 LLM 推理的事实标准，能够在消费级硬件上高效运行。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://rits.shanghai.nyu.edu/ai/qwen3-6-27b-a-dense-27b-model-that-beats-a-397b-moe-on-coding">Qwen 3 . 6 - 27 B : A Dense 27 B Model That Beats a 397B MoE on Coding</a></li>
<li><a href="https://en.wikipedia.org/wiki/Llama.cpp">Llama.cpp</a></li>
<li><a href="https://github.com/ggml-org/llama.cpp">GitHub - ggml-org/llama.cpp: LLM inference in C/C++ · GitHub</a></li>

</ul>
</details>

**社区讨论**: Hacker News 的讨论强调了本地模型在编程中的实用价值，用户分享了各自的设置和经验。一些评论者指出 Qwen3.6-27B 在编程任务上的表现令人印象深刻，另一些人则讨论了密集架构与 MoE 架构之间的权衡。

**标签**: `#local LLM`, `#coding assistant`, `#Qwen`, `#llama.cpp`, `#AI tools`

---

<a id="item-15"></a>
## [Codex v0.141.0 新增加密中继通道](https://github.com/openai/codex/releases/tag/rust-v0.141.0) ⭐️ 6.0/10

Codex v0.141.0 为远程执行器引入了经过身份验证的端到端加密 Noise 中继通道，并通过保留本机工作目录和 Shell 改进了跨平台远程执行。 此版本增强了 Codex 中远程执行的安全性，这是使用 OpenAI 工具进行自动化编码任务的开发人员的关键功能，并提高了不同操作系统之间的兼容性。 Noise 协议为中继通道提供经过身份验证的加密，确保数据完整性和机密性。跨平台改进包括在应用服务器和执行服务器边界之间保留文件系统权限路径。

rss · OpenAI Codex Releases · 6月18日 04:44

**背景**: Codex 是 OpenAI 用于自动代码生成和执行的工具。远程执行器允许 Codex 在远程机器上运行代码，这需要安全的通信通道。Noise 协议是一个用于构建加密协议的框架，提供强大的安全保证。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://developers.openai.com/codex/remote-connections">Remote connections – Codex | OpenAI Developers</a></li>

</ul>
</details>

**标签**: `#remote execution`, `#security`, `#cross-platform`, `#openai`, `#codex`

---