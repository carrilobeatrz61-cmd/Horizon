---
layout: default
title: "Horizon Summary: 2026-07-27 (ZH)"
date: 2026-07-27
lang: zh
---

> 从 35 条内容中筛选出 10 条重要资讯。

---

1. [美国公民因 GrapheneOS 胁迫 PIN 码擦除手机在边境被起诉](#item-1) ⭐️ 8.0/10
2. [证明自动化已到来：编程的未来](#item-2) ⭐️ 8.0/10
3. [欧盟提议浏览器级隐私设置以消灭 Cookie 横幅](#item-3) ⭐️ 8.0/10
4. [调查揭露中国 LLM 代币折扣转售的代理市场](#item-4) ⭐️ 8.0/10
5. [Ruff v0.16.0 将默认 lint 规则从 59 条扩展到 413 条](#item-5) ⭐️ 8.0/10
6. [PGSimCity：PostgreSQL 内部机制的交互式 3D 可视化](#item-6) ⭐️ 7.0/10
7. [Decker 以 1 位图形复兴 HyperCard](#item-7) ⭐️ 7.0/10
8. [Vercel 发布 Scriptc：将 TypeScript 编译为原生代码，无需 JS 引擎](#item-8) ⭐️ 7.0/10
9. [面向数据设计 PDF 引发实用性辩论](#item-9) ⭐️ 7.0/10
10. [用 FFmpeg 模拟磁带音频](#item-10) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [美国公民因 GrapheneOS 胁迫 PIN 码擦除手机在边境被起诉](https://www.techspot.com/news/113236-us-prosecutors-charge-atlanta-man-after-grapheneos-phone.html) ⭐️ 8.0/10

一名美国公民因其配置了胁迫 PIN 码（可擦除设备）的 GrapheneOS 手机在边境搜查中被擦除而遭到起诉。这是首例涉及隐私导向移动操作系统上胁迫 PIN 码功能的法律案件之一。 此案为在美国边境使用胁迫 PIN 码等安全功能的法律后果开创了先例，可能影响注重隐私的个人如何保护数据。它凸显了数字隐私权与政府在入境口岸搜查权之间的紧张关系。 胁迫 PIN 码是 GrapheneOS 的一项功能，允许用户设置一个替代 PIN 码，输入后不可逆地擦除设备及所有已安装的 eSIM。据报道，该用户在搜查期间输入了胁迫 PIN 码，导致手机被擦除并随后被起诉。

hackernews · eecc · 7月26日 22:21 · [社区讨论](https://news.ycombinator.com/item?id=49063022)

**背景**: GrapheneOS 是一个基于 Android 开源项目（AOSP）的、注重安全与隐私的移动操作系统，专为需要强数据泄露和监控防护的用户设计。胁迫 PIN 码功能旨在让记者或活动家等高危人群在胁迫下保护敏感数据。美国边境官员拥有广泛的电子设备搜查权，在搜查期间故意销毁证据可能导致妨碍司法指控。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.androidauthority.com/grapheneos-duress-pin-3584795/">I use a duress PIN to protect my data — here’s how it works and why everyone needs one</a></li>
<li><a href="https://sideofburritos.com/blog/grapheneos-duress-pin-password/">How to set up Duress PIN/Password on GrapheneOS | Side Of Burritos</a></li>
<li><a href="https://grapheneos.org/">GrapheneOS : the private and secure mobile OS</a></li>

</ul>
</details>

**社区讨论**: 评论者就法律影响展开辩论，有人认为用户擦除手机的意图是起诉的关键，而另一些人指出政府在边境的权力很大。一些人建议，像 VeraCrypt 的隐藏卷这样的替代方法可能比胁迫 PIN 码在法律上更具辩护性。

**标签**: `#privacy`, `#security`, `#GrapheneOS`, `#border search`, `#legal`

---

<a id="item-2"></a>
## [证明自动化已到来：编程的未来](https://www.imperialviolet.org/2026/07/26/zstd-lean.html) ⭐️ 8.0/10

一篇博客文章认为，内置定理证明器的编程语言将减少对测试的依赖，社区讨论强调了像 Verus（用于 Rust）这样的实际实现以及使用 LLM 的 AI 辅助证明自动化。 这一转变可能从根本上改变软件工程，使形式化验证更易用，减少错误和安全漏洞，并使 AI 能够生成可证明正确的代码。 该文章以 Zstandard 压缩为例，评论中提到了用于 Rust 的 Verus、用于以太坊虚拟机形式化的 Lean 4，以及用于基准测试自动定理证明器的 Python 包 OpenATP。

hackernews · zdw · 7月26日 20:53 · [社区讨论](https://news.ycombinator.com/item?id=49062291)

**背景**: 定理证明器是检查数学证明正确性的软件工具。当集成到编程语言中时，它们允许开发者形式化地验证代码是否符合规范，从而减少对传统测试的需求。AI（尤其是大型语言模型 LLM）的最新进展在自动化证明编写过程中显示出潜力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Proof_assistant">Proof assistant - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Lean_(proof_assistant)">Lean (proof assistant) - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者大多同意作者的观点，指出像 Verus 和 Lean 4 这样的工具已经取得了进展。一些人讨论了 AI 辅助证明生成的成本，有评论提到一个 Lean 4 形式化的以太坊虚拟机，其 API 令牌成本高达 15 万美元。其他人分享了正在进行的研究，如用于基准测试定理证明器的 OpenATP。

**标签**: `#formal verification`, `#theorem proving`, `#LLM`, `#programming languages`, `#Rust`

---

<a id="item-3"></a>
## [欧盟提议浏览器级隐私设置以消灭 Cookie 横幅](https://killthecookiebanner.eu/) ⭐️ 8.0/10

Cookie 横幅因破坏用户体验且往往无法提供有意义的同意而广受诟病。如果被采纳，这种浏览器级的方法可以简化数百万用户的隐私管理，并为全球隐私监管树立先例。 该提案仍处于早期阶段，需要改变浏览器行为和网站合规框架。加利福尼亚州已通过一项法律，要求类似的浏览器级隐私控制，将于 2027 年 1 月生效。

hackernews · rapnie · 7月26日 11:53 · [社区讨论](https://news.ycombinator.com/item?id=49057175)

**背景**: Cookie 横幅在 2018 年欧盟《通用数据保护条例》（GDPR）生效后变得普遍，要求网站在放置非必要 Cookie 前获得用户同意。然而，许多横幅使用暗黑模式诱导用户接受跟踪，削弱了法律精神。早期的浏览器级隐私控制尝试——隐私偏好平台（P3P）由 W3C 在 1990 年代末开发，但由于缺乏采纳和企业抵制而被放弃。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://sg.style.yahoo.com/europe-needs-back-browser-level-122935980.html">Europe needs to back browser-level controls to fix cookie consent...</a></li>
<li><a href="https://thenai.org/how-to-opt-out/web-browser-privacy-settings/">Web Browser Privacy Settings - The NAI: Network Advertising Initiative</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍支持这一想法，但表示怀疑，指出类似的提案（P3P）过去曾被企业利益扼杀。一些人认为真正的解决方案是彻底停止跟踪用户，而不是创建新的同意机制。其他人则指出加利福尼亚州的法律是更具体的进步。

**标签**: `#privacy`, `#cookie banners`, `#EU regulation`, `#web standards`, `#UX`

---

<a id="item-4"></a>
## [调查揭露中国 LLM 代币折扣转售的代理市场](https://simonwillison.net/2026/Jul/26/relay-market/#atom-everything) ⭐️ 8.0/10

Matt Lenhard 发布了一项调查，揭露了一个中国代理市场，该市场通过滥用免费试用、窃取凭证以及开源代理软件（如 one-api 和 new-api）来转售打折的 LLM 代币。 这一生态系统对 LLM 供应商和开发者构成了重大的安全和财务风险，因为它助长了欺诈、模型蒸馏以及对 API 服务的未授权访问，可能破坏 AI 行业的定价和信任模式。 转售者使用开源 API 代理软件（one-api 及其分支 new-api）汇集来自免费试用、未受保护的支持机器人、被盗信用卡或退款攻击的凭证，向寻求廉价代币、规避地理限制或收集数据进行模型蒸馏的买家提供大幅折扣。

rss · Simon Willison · 7月26日 19:30

**背景**: LLM API 代币通常由 OpenAI 等供应商按代币数量定价。代理市场利用计费系统和安全实践中的漏洞，使转售者能够以官方成本的一小部分提供代币。像 one-api 和 new-api 这样的开源代理工具是用于负载均衡 API 请求的合法产品，但它们可能被滥用来聚合被盗或滥用的凭证。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/Mirrowel/LLM-API-Key-Proxy">GitHub - Mirrowel/LLM-API-Key-Proxy: Universal LLM Gateway: One API, every LLM. OpenAI/Anthropic-compatible endpoints with multi-provider translation and intelligent load-balancing. · GitHub</a></li>
<li><a href="https://aibit.im/blog/post/new-api-the-next-gen-llm-gateway-ai-asset-manager">New API : The Next-Gen LLM Gateway & AI Asset Manager | AIBit</a></li>
<li><a href="https://seven7763.github.io/daoxe-guide/en/daoxe-vs-oneapi/">DaoXE vs One API / New API — managed access vs a self-hosted...</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，类似的转售市场在之前的互联网产品中就已存在，真正的问题是订阅模式激励了滥用。一些人分享了以官方价格 4% 购买打折代币的个人经历，从而获得了无与伦比的竞争优势。其他人指出，LLM 供应商需要更好的支出上限，而硬件成本降低可能是唯一的长期解决方案。

**标签**: `#LLM`, `#security`, `#fraud`, `#API`, `#AI`

---

<a id="item-5"></a>
## [Ruff v0.16.0 将默认 lint 规则从 59 条扩展到 413 条](https://simonwillison.net/2026/Jul/25/ruff/#atom-everything) ⭐️ 8.0/10

Ruff v0.16.0 于 2026 年 7 月 23 日发布，将默认 lint 规则从 59 条增加到 413 条，能够捕获语法错误和运行时错误等更严重的问题。 这一重大扩展意味着 Python 开发者无需任何配置即可自动捕获更多关键问题，显著提高代码质量并减少运行时错误。 此次更新将可用规则总数从 v0.1.0 的 708 条增加到 968 条。新默认规则包括 BLE001（盲目捕获异常）和 DTZ005（datetime.now 未指定时区）等。

rss · Simon Willison · 7月25日 22:44

**背景**: Ruff 是一个用 Rust 编写的极速 Python 代码检查器和格式化工具，由 Astral 开发（现已被 OpenAI 收购）。它旨在替代 Flake8 和 Black 等多个工具，速度提升 10-100 倍。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://docs.astral.sh/ruff/">Ruff</a></li>
<li><a href="https://github.com/astral-sh/ruff">GitHub - astral-sh/ruff: An extremely fast Python linter and code formatter, written in Rust. · GitHub</a></li>

</ul>
</details>

**社区讨论**: 社区反应总体积极，用户赞赏扩展后的默认规则能捕获更多问题。部分用户对未固定依赖导致的 CI 失败表示担忧，但总体认为此次升级是有益的。

**标签**: `#ruff`, `#python`, `#linting`, `#astral`, `#release`

---

<a id="item-6"></a>
## [PGSimCity：PostgreSQL 内部机制的交互式 3D 可视化](https://nikolays.github.io/PGSimCity/) ⭐️ 7.0/10

PGSimCity 是一个可探索的 3D 城市模型，它动态展示了 PostgreSQL 的内部架构，包括进程、内存和 I/O 流程，为理解数据库工作原理提供了一种新颖的方式。 该工具使复杂的数据库内部机制对开发者和学生更加易于理解，有望提高学习和调试效率。其开源特性也允许将其适配到 Kubernetes 等其他系统中。 该可视化是一个模型而非模拟器，可通过浏览器控制台使用 sim、registry、bus 等对象进行控制。社区反馈认为自动导览过于杂乱，建议增加交互控制和减速选项。

hackernews · jonbaer · 7月27日 00:19 · [社区讨论](https://news.ycombinator.com/item?id=49063754)

**背景**: PostgreSQL 采用多进程架构，主进程为每个客户端连接派生一个后端进程。理解其内部机制（如共享缓冲区、WAL 和查询执行）对于性能调优至关重要，但传统图表往往是静态且难以理解的。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/NikolayS/pgsimcity">GitHub - NikolayS/ PGSimCity : An explorable 3D city that shows how...</a></li>
<li><a href="https://blog.algomaster.io/p/postgresql-internal-architecture">How PostgreSQL Works: Internal Architecture Explained</a></li>
<li><a href="https://www.postgresql.org/docs/current/tutorial-arch.html">PostgreSQL: Documentation: 18: 1.2. Architectural Fundamentals</a></li>

</ul>
</details>

**社区讨论**: 评论褒贬不一：一些用户喜欢这个概念，但认为自动导览令人困惑且过于杂乱，建议提供交互式探索和减速按钮。其他人则欣赏其开源潜力，并看到其在数据库之外的应用，例如云计算。

**标签**: `#PostgreSQL`, `#visualization`, `#database internals`, `#educational tool`

---

<a id="item-7"></a>
## [Decker 以 1 位图形复兴 HyperCard](https://beyondloom.com/decker/) ⭐️ 7.0/10

Decker 是一个现代平台，它重现了 HyperCard 的体验，采用 1 位图形和自包含环境来构建交互式应用程序。它旨在通过类似原始 HyperCard 的直观、基于卡片的开发模型赋能非程序员。 这次复兴意义重大，因为 HyperCard 是一款开创性的工具，它使最终用户编程和小型企业及爱好者的快速应用开发成为可能。Decker 可以在现代背景下重新引入这种易用性，可能引发新一轮用户创建软件的浪潮。 Decker 使用 1 位图形，将颜色限制为黑白，这唤起了早期 Macintosh 和复古计算的美学。它是开源的，并建立在 HyperCard 的遗产之上，HyperCard 最初于 1987 年发布，并于 2004 年停止销售。

hackernews · tosh · 7月26日 18:23 · [社区讨论](https://news.ycombinator.com/item?id=49060856)

**背景**: HyperCard 是 Apple Macintosh 的一款软件应用和开发工具包，它将平面文件数据库与图形化、用户可修改的界面相结合。它包含一种名为 HyperTalk 的脚本语言，允许用户为各种目的创建交互式堆栈，从游戏到商业数据库。HyperCard 是最早成功的超媒体系统之一，并被非程序员广泛使用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/HyperCard">HyperCard</a></li>

</ul>
</details>

**社区讨论**: 评论者表达了对 HyperCard 的怀旧之情，一位用户回忆起小时候用基本构件创建个人英语单词集合的经历。其他人质疑这类界面在今天是否还有用武之地，指出 FileMaker 和 Access 等工具曾为许多小型企业应用提供动力。一些人欣赏这个项目，但希望减少“古怪”的设计方面以提高实用性。

**标签**: `#HyperCard`, `#end-user programming`, `#retro computing`, `#visual programming`, `#open source`

---

<a id="item-8"></a>
## [Vercel 发布 Scriptc：将 TypeScript 编译为原生代码，无需 JS 引擎](https://github.com/vercel-labs/scriptc) ⭐️ 7.0/10

Vercel Labs 发布了 Scriptc，这是一个将 TypeScript 编译为原生可执行文件的编译器，生成的二进制文件无需 Node 或 V8 等 JavaScript 引擎。该项目已在 GitHub 和 npm 上发布，版本号为 0.0.9。 如果成功，Scriptc 将使 TypeScript 开发者能够构建高性能、自包含的应用程序，无需 JavaScript 运行时的开销。这挑战了 TypeScript 始终需要 JS 引擎的假设，可能扩展其在系统编程和边缘计算中的应用。 Scriptc 使用类型化的中间表示（IR），并支持 LLVM 和 C 后端。目前，macOS arm64 是主要平台，Linux 和 Windows 二进制文件通过交叉编译生成。

hackernews · maxloh · 7月26日 22:46 · [社区讨论](https://news.ycombinator.com/item?id=49063175)

**背景**: TypeScript 是 JavaScript 的类型化超集，通常编译为 JavaScript 并在 V8 等 JS 引擎中运行。在没有 JS 引擎的情况下将 TypeScript 编译为原生代码具有挑战性，因为 TypeScript 依赖于 JavaScript 语义和 npm 生态系统，而后者通常包含无类型的 JavaScript 包。类似的项目如 Porffor 和 Perry 也曾尝试实现类似目标，但尚未完全兼容 JavaScript 规范（Test262）。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/vercel-labs/scriptc">GitHub - vercel -labs/ scriptc : TypeScript -to- Native Compiler · GitHub</a></li>
<li><a href="https://news.ycombinator.com/item?id=49063175">Scriptc by Vercel : TypeScript -to- Native compiler , no... | Hacker News</a></li>
<li><a href="https://www.npmjs.com/package/@scriptc/compiler">scriptc / compiler - npm</a></li>

</ul>
</details>

**社区讨论**: 社区成员对 Scriptc 相比现有项目（如 Porffor，仅通过约 68% 的 Test262 测试）的快速进展表示怀疑。一些人指出，没有 JS 引擎，Scriptc 无法使用大多数 npm 包，限制了其实用性。另一些人认为 TypeScript 的强类型使其成为原生编译的良好候选，但对项目的范围和可行性提出了质疑。

**标签**: `#TypeScript`, `#compiler`, `#native`, `#Vercel`, `#JavaScript`

---

<a id="item-9"></a>
## [面向数据设计 PDF 引发实用性辩论](https://www.gamedevs.org/uploads/introduction-to-data-oriented-design.pdf) ⭐️ 7.0/10

Mike Acton 的一篇关于面向数据设计（DoD）的基础 PDF 重新引起关注，强调以数据为先的算法设计以提升性能，作者还在 GitHub 上发布了一个面向数据编程的 LLM 技能。 这场讨论凸显了 DoD 在理论上的性能优势与在代码库演进中的实际挑战之间的持续张力，影响着为现代 CPU 缓存进行优化的游戏开发者和软件工程师。 该 PDF 倡导通过首先定义数据布局来设计算法，以最大化缓存效率，通常使用并行数组（结构体数组）。社区评论质疑 DoD 在实践中是否与缓存感知编程或数组编程有本质区别。

hackernews · tosh · 7月26日 18:11 · [社区讨论](https://news.ycombinator.com/item?id=49060724)

**背景**: 面向数据设计是一种性能优化方法，优先考虑数据布局和访问模式而非传统的面向对象设计，旨在减少缓存未命中。它广泛应用于对性能要求苛刻的游戏开发中。该方法与面向对象编程的结构体数组形成对比，更倾向于使用数组结构体。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Data-oriented_design">Data-oriented design</a></li>
<li><a href="https://www.dataorienteddesign.com/dodmain/">Richard Fabian - Data-oriented design</a></li>
<li><a href="https://github.com/dbartolini/data-oriented-design">GitHub - dbartolini/data-oriented-design: A curated list of data oriented design resources. · GitHub</a></li>

</ul>
</details>

**社区讨论**: 评论者就 DoD 的实用性展开辩论：有人认为在需求频繁变化时难以应用，而另一些人则认为它只是缓存感知或数组编程的重新包装。作者的 LLM 技能链接为这一经典话题增添了现代色彩。

**标签**: `#data-oriented design`, `#performance optimization`, `#game development`, `#software engineering`

---

<a id="item-10"></a>
## [用 FFmpeg 模拟磁带音频](https://github.com/AARomanov1985/Audio-Cassette-Simulation) ⭐️ 7.0/10

一个新的 GitHub 工具 Audio-Cassette-Simulation 利用 FFmpeg 模拟不同磁带类型的音频特性，包括嘶声、抖晃和频率响应。 该工具通过重现磁带的独特声音，为音频修复和怀旧项目提供了可能，对音乐人、档案管理员和复古计算爱好者很有价值。 该工具应用了磁带噪声、抖晃音高调制、带宽限制和均衡器调整，并包含特定磁带类型（如 BASF LH Extra C90）的配置文件。

hackernews · xterminal · 7月26日 20:02 · [社区讨论](https://news.ycombinator.com/item?id=49061887)

**背景**: 磁带是模拟磁性录音介质，存在嘶声（背景噪声）、抖晃（速度变化导致音高不稳定）和有限的频率响应等缺陷。FFmpeg 是一个强大的开源命令行工具，用于处理音频和视频文件，能够应用复杂滤镜来模拟这些模拟特性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/AARomanov1985/Audio-Cassette-Simulation">GitHub - AARomanov1985/Audio-Cassette-Simulation: This project simulates cassette tape audio profiles using ffmpeg · GitHub</a></li>
<li><a href="https://en.wikipedia.org/wiki/FFmpeg">FFmpeg - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Compact_Cassette_tape_types_and_formulations">Compact Cassette tape types and formulations - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区讨论显示出对技术细节的浓厚兴趣：用户询问如何确定每种磁带类型的效果，询问 Dolby B 编码/解码，并讨论多次处理带来的多代损失。一位用户表示对该工具用于自己的项目感到兴奋。

**标签**: `#audio`, `#FFmpeg`, `#cassette simulation`, `#signal processing`, `#retro computing`

---