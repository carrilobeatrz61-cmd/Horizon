---
layout: default
title: "Horizon Summary: 2026-07-03 (ZH)"
date: 2026-07-03
lang: zh
---

> 从 43 条内容中筛选出 12 条重要资讯。

---

1. [美国禁止人口普查数据中的差分隐私](#item-1) ⭐️ 9.0/10
2. [弗吉尼亚州禁止出售地理位置数据](#item-2) ⭐️ 8.0/10
3. [crustc：将整个 rustc 编译器翻译为 C 语言](#item-3) ⭐️ 8.0/10
4. [Linux 6.9 LUKS 挂起漏洞导致加密密钥留在内存中](#item-4) ⭐️ 8.0/10
5. [Podman v6.0.0 发布，带来重大网络改进](#item-5) ⭐️ 8.0/10
6. [Immich 3.0 重大更新引发加密讨论](#item-6) ⭐️ 8.0/10
7. [Postgres 事务：分布式系统的超能力](#item-7) ⭐️ 8.0/10
8. [zkGolf：LLM 竞赛优化形式化验证的零知识电路](#item-8) ⭐️ 8.0/10
9. [理解才能参与：AI 协作的关键](#item-9) ⭐️ 8.0/10
10. [Claude Code v2.1.198：后台子代理、Chrome 集成正式发布](#item-10) ⭐️ 7.0/10
11. [使用 DSPy 优化 Datasette Agent 的 SQL 提示](#item-11) ⭐️ 7.0/10
12. [Simon Willison 发布 llm-coding-agent 0.1a0](#item-12) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [美国禁止人口普查数据中的差分隐私](https://scottaaronson.blog/?p=9902) ⭐️ 9.0/10

2026 年 6 月 4 日，美国商务部长发布指令（DAO 216-26），禁止在人口普查局所有统计产品中使用差分隐私和噪声注入，将披露避免限制为仅粗化处理。 该指令威胁到用于资源分配和选区划分等关键决策的公共统计数据的可靠性，削弱了数十年的隐私研究，并可能使个人面临重新识别的风险。 该禁令明确禁止噪声注入（差分隐私的核心技术），并将披露避免限制为粗化处理——一种不添加噪声而降低数据粒度的方法。

hackernews · flowercalled · 7月3日 00:01 · [社区讨论](https://news.ycombinator.com/item?id=48768992)

**背景**: 差分隐私是一种数学框架，通过向数据中添加精心校准的噪声来保护个人隐私，同时保持统计准确性。人口普查局在 2020 年人口普查中使用了差分隐私，以防止受访者被重新识别。噪声注入在官方统计中已使用数十年，包括人口普查局的季度劳动力指标。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Differential_privacy">Differential privacy - Wikipedia</a></li>
<li><a href="https://www.census.gov/library/working-papers/2014/adrm/ces-wp-14-30.html">Noise Infusion As A Confidentiality Protection Measure For Graph-Based Statistics</a></li>

</ul>
</details>

**社区讨论**: 评论者表示震惊，有人称之为‘隐私紧急事件’，并敦促读者联系立法者。其他人质疑该指令背后的政治动机，怀疑其有不可告人的目的，少数人批评该帖子的语气过于夸张。

**标签**: `#privacy`, `#differential privacy`, `#census`, `#government policy`, `#data science`

---

<a id="item-2"></a>
## [弗吉尼亚州禁止出售地理位置数据](https://www.hunton.com/privacy-and-cybersecurity-law-blog/virginia-bans-sale-of-geolocation-data) ⭐️ 8.0/10

2026 年 4 月 13 日，弗吉尼亚州州长 Abigail Spanberger 签署了 S.B. 388 法案，修订了《弗吉尼亚消费者数据保护法》（VCDPA），禁止出售精确地理位置数据，该禁令于 2026 年 7 月 1 日生效。 这使得弗吉尼亚州成为第三个禁止出售精确地理位置数据的州，反映了州级隐私立法的增长趋势，可能对依赖基于位置的广告和分析的数据经纪商及科技公司产生重大影响。 该禁令适用于能识别个人位置在 1750 英尺以内的精确地理位置数据，但不禁止出售较不精确或模糊的位置数据。执法挑战依然存在，特别是对于在弗吉尼亚州没有实体存在的州外公司。

hackernews · toomuchtodo · 7月2日 21:03 · [社区讨论](https://news.ycombinator.com/item?id=48767347)

**背景**: 《弗吉尼亚消费者数据保护法》（VCDPA）是一项全面的隐私法律，赋予消费者对其个人数据的权利。精确地理位置数据在许多隐私框架中被视为敏感个人信息。该修正案专门针对此类数据的出售，效仿了加利福尼亚州和其他州的类似法律。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.hunton.com/privacy-and-cybersecurity-law-blog/virginia-bans-sale-of-geolocation-data">Virginia Bans Sale of Geolocation Data</a></li>
<li><a href="https://advocacy.consumerreports.org/press_release/virginia-governor-signs-landmark-location-privacy-bill-into-law/">Virginia Governor signs landmark location privacy bill into law</a></li>
<li><a href="https://www.regulatoryoversight.com/2026/04/virginia-becomes-third-state-to-ban-sale-of-consumers-precise-geolocation-data/">Virginia Becomes Third State to Ban Sale of Consumers' Precise Geolocation Data | Regulatory Oversight</a></li>

</ul>
</details>

**社区讨论**: 社区评论指出了执法漏洞，例如在特拉华州注册的公司从州外出售在弗吉尼亚收集的数据，并指出该禁令仅涵盖 1750 英尺内的精确数据，允许出售模糊位置数据。一些评论者将该法律与加州法律进行比较，希望它能对数据经纪商施加真正的限制，而不仅仅是混淆视听。

**标签**: `#privacy`, `#geolocation data`, `#legislation`, `#data brokers`, `#Virginia`

---

<a id="item-3"></a>
## [crustc：将整个 rustc 编译器翻译为 C 语言](https://github.com/FractalFir/crustc) ⭐️ 8.0/10

一个名为 crustc 的项目旨在将整个 Rust 编译器（rustc）翻译为 C 语言，从而在没有 LLVM 或 GCC 支持的平台上实现自举。这项工作已持续三年，据称是此类转译的第 14 次尝试。 该项目可以解决 Rust 在稀有或老旧硬件上的自举问题，并支持诸如多样化双编译（DDC）等编译器验证技术来检查后门。它增强了 Rust 的可移植性和可信度。 该项目托管在 GitHub 上的 FractalFir/crustc。作者指出，转译为 C 比转译为 LLVM IR 更容易，并且让 GCC 优化可能带来实用的性能。LLVM 的 C 后端曾被移除但正在恢复，不过 crustc 采用了不同的方法。

hackernews · Philpax · 7月2日 22:57 · [社区讨论](https://news.ycombinator.com/item?id=48768464)

**背景**: 自举是使用编译器编译自身的过程。Rust 目前需要预构建的 rustc 二进制文件或 LLVM/GCC 后端才能从源码构建，这为新平台带来了先有鸡还是先有蛋的问题。将 rustc 转译为 C 打破了这一依赖，因为 C 编译器几乎在所有平台上都可用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://rustc-dev-guide.rust-lang.org/building/bootstrapping/what-bootstrapping-does.html?trk=public_post_comment-text">What Bootstrapping does - Rust Compiler Development Guide</a></li>
<li><a href="https://doc.rust-lang.org/unstable-book/compiler-environment-variables/RUSTC_BOOTSTRAP.html">RUSTC _ BOOTSTRAP - The Rust Unstable Book</a></li>

</ul>
</details>

**社区讨论**: 社区参与度很高，评论赞扬了作者的奉献精神，并指出该项目在 DDC 验证方面的潜力。一些人讨论了 LLVM C 后端作为替代方案，另一些人则对实现细节和作者的幽默轶事表示好奇。

**标签**: `#rust`, `#compiler`, `#bootstrapping`, `#transpilation`, `#systems programming`

---

<a id="item-4"></a>
## [Linux 6.9 LUKS 挂起漏洞导致加密密钥留在内存中](https://mathstodon.xyz/@iblech/116769502749142438) ⭐️ 8.0/10

Linux 内核 6.9 中的一个漏洞导致 LUKS 挂起操作未能从内存中清除磁盘加密密钥，可能在挂起到 RAM 期间暴露密钥。 这一回归破坏了 LUKS 挂起的安全保证（该功能旨在在笔记本电脑挂起时保护磁盘加密密钥），可能让拥有物理访问权限的攻击者从内存中提取密钥。 该漏洞影响 Linux 内核 6.9.0 至 6.9.8 版本，cryptsetup luksSuspend 命令在进入挂起到 RAM 前不再正确地从内存中移除主密钥。

hackernews · IngoBlechschmid · 7月2日 15:25 · [社区讨论](https://news.ycombinator.com/item?id=48763035)

**背景**: LUKS（Linux 统一密钥设置）是一种磁盘加密规范。luksSuspend 命令用于在系统挂起前临时锁定 LUKS 设备并从内存中清除其加密密钥，确保密钥在睡眠期间不在 RAM 中。这对于可能在挂起时被盗的笔记本电脑尤其重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://sesamedisk.com/linux-luks-suspend-regression-security/">Linux LUKS Suspend Regression: Keys Stay - Sesame Disk</a></li>
<li><a href="https://manpages.ubuntu.com/manpages/stonking/man7/cryptsetup-suspend.7.html">Ubuntu Manpage: cryptsetup- suspend - automatically suspend LUKS ...</a></li>
<li><a href="https://wiki.gentoo.org/wiki/Suspend_and_hibernate">Suspend and hibernate - Gentoo wiki</a></li>

</ul>
</details>

**社区讨论**: 社区讨论包括关于这是内核还是发行版责任的辩论，一些人指出 luksSuspend 功能最初是 Debian 的扩展。其他人认为对普通用户风险很小，少数人则怀疑是否存在故意后门。

**标签**: `#Linux`, `#security`, `#LUKS`, `#encryption`, `#kernel`

---

<a id="item-5"></a>
## [Podman v6.0.0 发布，带来重大网络改进](https://blog.podman.io/2026/07/introducing-podman-v6-0-0/) ⭐️ 8.0/10

Podman v6.0.0 已发布，引入了网络方面的重大改进，包括新的网络后端和性能提升。该更新还增强了对 Docker Compose 及其他容器工具的兼容性。 此版本巩固了 Podman 作为 Docker 主要替代方案的地位，尤其适合需要无守护进程、无根容器运行时的用户。网络改进解决了关键痛点，使 Podman 更适用于生产环境和复杂部署。 新的网络后端 Netavark 取代了旧的基于 CNI 的系统，提供更好的性能和更简单的配置。Podman v6.0.0 还包括用于 systemd 集成的 Quadlet，并改进了对无根容器的支持。

hackernews · soheilpro · 7月2日 14:23 · [社区讨论](https://news.ycombinator.com/item?id=48762098)

**背景**: Podman 是一个开源容器引擎，提供与 Docker 兼容的命令行界面，但无需中央守护进程。它允许用户以无根模式运行容器，增强安全性。该项目作为 Docker 的安全、轻量级替代方案而日益流行。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://1hometheatreprojector.com/connectivity-networking/podman-v6-0-0/">Podman V 6 . 0 . 0 - 1st Home Theatre Projector</a></li>
<li><a href="https://www.linode.com/docs/guides/podman-vs-docker/">Podman vs Docker : Comparing the Two... | Linode Docs</a></li>
<li><a href="https://github.com/containers/podman/blob/main/docs/tutorials/basic_networking.md">podman /docs/tutorials/basic_ networking .md at main...</a></li>

</ul>
</details>

**社区讨论**: 社区评论总体积极，用户称赞 Podman 从 Docker 迁移的简便性以及新的网络功能。部分用户报告了 macOS 上的问题，但总体情绪良好，许多人分享了成功的迁移经验和技巧。

**标签**: `#Podman`, `#containers`, `#Docker alternative`, `#networking`, `#open source`

---

<a id="item-6"></a>
## [Immich 3.0 重大更新引发加密讨论](https://github.com/immich-app/immich/discussions/29439) ⭐️ 8.0/10

自托管照片管理平台 Immich 发布了 3.0 重大版本，引入了新功能和改进，但值得注意的是并未包含端到端加密。 此次发布凸显了加密等隐私功能与易用性之间的持续矛盾，因为 Immich 正将自己定位为 Google Photos 和 Apple Photos 的可行开源替代品。 社区讨论揭示了强烈的观点分歧：一些用户优先考虑端到端加密并选择 Ente Photos 等替代方案，而另一些用户则认为加密对于自托管设置没有必要，并且会使共享和搜索等功能复杂化。

hackernews · hashier · 7月2日 14:13 · [社区讨论](https://news.ycombinator.com/item?id=48761944)

**背景**: Immich 是一个开源、自托管的照片和视频管理解决方案，提供面部识别和智能搜索等 AI 驱动功能。它旨在提供 Google Photos 等云服务的隐私优先替代方案，让用户完全控制自己的数据。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://immich.app/">Immich</a></li>
<li><a href="https://github.com/immich-app/immich">GitHub - immich-app/immich: High performance self-hosted photo and ...</a></li>
<li><a href="https://aicybr.com/blog/immich-complete-self-hosting-guide">Immich Complete Self-Hosting Guide: From Installation to Advanced ...</a></li>

</ul>
</details>

**社区讨论**: 评论意见不一：一些用户称赞 Immich 是云服务的无脑替代品，而另一些用户则对缺乏端到端加密表示失望，并已转向 Ente Photos 等替代方案。少数人认为自托管设置不需要加密，并引用了设备丢失后恢复照片等实际场景。

**标签**: `#self-hosting`, `#photo management`, `#open source`, `#privacy`, `#immich`

---

<a id="item-7"></a>
## [Postgres 事务：分布式系统的超能力](https://www.dbos.dev/blog/co-locating-workflow-state-with-your-data) ⭐️ 8.0/10

DBOS 的一篇博客文章解释了如何将工作流状态与应用程序数据共置于同一个 Postgres 数据库中，从而利用数据库事务简化分布式模式（如事务性发件箱）。 这种方法通过消除对分布式事务或两阶段提交的需求，降低了架构复杂性，使已经使用 Postgres 的团队更容易实现可靠的工作流执行。 该技术将每个工作流步骤与单个数据库提交对齐，从而能够原子性地更新应用程序数据和工作流状态。这种紧密耦合简化了发件箱模式，但可能使将来分离数据库和工作流逻辑变得更加困难。

hackernews · KraftyOne · 7月2日 18:38 · [社区讨论](https://news.ycombinator.com/item?id=48765639)

**背景**: 在分布式系统中，事务性发件箱模式确保数据库更新和向消息代理发送消息原子性地发生。传统上，这需要协调两个独立的系统（数据库和消息队列），往往导致复杂性。将工作流状态与数据共置于单个 Postgres 实例中，可以利用数据库内置的 ACID 事务来保证原子性，无需外部协调。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.dbos.dev/blog/co-locating-workflow-state-with-your-data">The Case for Co-Locating Workflow State with Your Data | DBOS</a></li>
<li><a href="https://microservices.io/patterns/data/transactional-outbox.html">Pattern : Transactional outbox</a></li>
<li><a href="https://www.milanjovanovic.tech/blog/implementing-the-outbox-pattern">Implementing the Outbox Pattern</a></li>

</ul>
</details>

**社区讨论**: 评论者讨论了其中的权衡：一些人称赞原子性的好处并分享了实际成功案例，而另一些人质疑这是否真正构成分布式系统，或者只是一个带有互斥锁的集中式数据库。有人担心数据库与工作流逻辑之间的紧密耦合，但许多人指出在实践中很少需要分离。

**标签**: `#PostgreSQL`, `#distributed systems`, `#workflow`, `#transactions`, `#outbox pattern`

---

<a id="item-8"></a>
## [zkGolf：LLM 竞赛优化形式化验证的零知识电路](https://zk.golf/) ⭐️ 8.0/10

zkGolf 是一个竞赛平台，让 LLM 生成经过形式化验证的零知识证明电路，从 SHA-256 开始，目标是优化电路约束。该项目展示了 LLM（Opus 4.7）能够生成一个在 SHA-256 压缩上超越人工优化最先进水平的电路。 这种方法通过自动化电路优化并保证形式化正确性，可能降低 ZKP 开发的门槛。它可能加速 ZKP 在区块链扩容、隐私和可验证计算中的应用。 这些电路针对 R1CS 算术化和大域，成本指标基于约束数量。LLM 有时会提出不安全的优化，但在无法证明时会回溯，从而确保正确性。

hackernews · rot256 · 7月2日 15:40 · [社区讨论](https://news.ycombinator.com/item?id=48763246)

**背景**: 零知识证明（ZKP）允许证明者在不泄露输入的情况下说服验证者计算正确。计算必须表示为有限域上的多项式方程（约束）电路；每个约束都会增加证明时间。Lean 是一个用于形式化验证的证明助手和函数式编程语言。R1CS（秩-1 约束系统）是 ZK-SNARK 中常用的算术化方案。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://emirsoyturk.medium.com/hello-arithmetization-55e57c8e5471">Hello Arithmetization — R1CS | by Emir Soytürk | Medium</a></li>
<li><a href="https://en.wikipedia.org/wiki/Lean_theorem_prover">Lean theorem prover</a></li>
<li><a href="https://fractalyze.gitbook.io/intro/zk/arithmetization/r1cs">R1CS | Fractalyze - GitBook</a></li>

</ul>
</details>

**社区讨论**: 社区评论积极，称赞该倡议并表示期待参与。有评论者质疑该项目是否为收集 Lean 证明的数据集钓鱼操作，但未得到回应。

**标签**: `#zero-knowledge proofs`, `#formal verification`, `#LLM`, `#circuit optimization`, `#Lean`

---

<a id="item-9"></a>
## [理解才能参与：AI 协作的关键](https://simonwillison.net/2026/Jul/2/understand-to-participate/#atom-everything) ⭐️ 8.0/10

Simon Willison 强调了 Geoffrey Litt 的观点：开发者必须深入理解 AI 代理所做的代码变更，以避免认知债务并保持有效的参与。 这一概念解决了 AI 辅助编程中的关键挑战：代码生成速度可能超过人类理解，导致认知债务并削弱有意义贡献的能力。 Geoffrey Litt 在 AIE 会议上提出了这一观点，他的演讲已录制并将在 YouTube 上发布。他还在 Twitter 上发布了相关讨论串。

rss · Simon Willison · 7月2日 17:07

**背景**: 认知债务指的是开发者对系统的理解与实际运行方式之间的差距，这会使变更风险增加。随着 AI 代理生成更多代码，如果开发者不跟上变更，就可能积累认知债务。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://simonwillison.net/2026/jul/2/understand-to-participate/">Understand to participate | Simon Willison’s Weblog</a></li>
<li><a href="https://mathiesen.dev/writing/cognitive-debt">Cognitive Debt | Jarle Mathiesen</a></li>
<li><a href="https://unrollnow.com/status/2072522251300409556">Thread By @geoffreylitt - Hot take: I think it's still...</a></li>

</ul>
</details>

**标签**: `#AI-assisted coding`, `#cognitive debt`, `#human-AI collaboration`, `#software engineering`

---

<a id="item-10"></a>
## [Claude Code v2.1.198：后台子代理、Chrome 集成正式发布](https://github.com/anthropics/claude-code/releases/tag/v2.1.198) ⭐️ 7.0/10

Claude Code v2.1.198 默认让子代理在后台运行，将 Chrome 集成正式发布，并引入了代理通知钩子和新的 /dataviz 技能。 这些更新通过支持并行任务执行和无缝浏览器集成，显著提高了开发者的生产力，同时通知钩子允许更好地自动化代理工作流。 后台子代理现在在完成工作树中的代码工作后会自动提交、推送并打开草稿 PR。Explore 代理继承主会话的模型（上限为 opus），而非运行在 haiku 上，并且子代理继承扩展思考配置。

rss · Claude Code Releases · 7月2日 22:55

**背景**: Claude Code 是 Anthropic 的 AI 编程助手，运行在终端中。子代理是可以被委派任务的专门代理，钩子允许自定义脚本响应代理生命周期事件。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://docs.anthropic.com/en/docs/claude-code/hooks">Hooks reference - Anthropic</a></li>
<li><a href="https://openclawradar.com/article/claude-code-v2-1-198">Claude Code v2.1.198: Chrome GA, Agent Notifications, / dataviz</a></li>
<li><a href="https://www.reddit.com/r/ClaudeAI/comments/1mdyc60/whats_your_best_way_to_use_subagents_in_claude/">What's your best way to use Sub-agents in Claude Code so far? - Reddit</a></li>

</ul>
</details>

**社区讨论**: 社区讨论强调子代理是复杂工作流的强大功能，用户分享创建专门子代理和管理超时的最佳实践。新的后台执行解决了之前关于阻塞行为的抱怨。

**标签**: `#Claude Code`, `#release notes`, `#AI coding assistant`, `#subagents`, `#Chrome integration`

---

<a id="item-11"></a>
## [使用 DSPy 优化 Datasette Agent 的 SQL 提示](https://simonwillison.net/2026/Jul/2/dspy-datasette-agent-prompts/#atom-everything) ⭐️ 7.0/10

Simon Willison 使用 DSPy 框架评估并改进了 Datasette Agent 的 SQL 查询生成系统提示，发现了列名猜测和错误重试循环等问题，并提出了具体修复方案。 这展示了一种使用 DSPy 优化 LLM 系统提示的实用迭代工作流，可帮助开发者提高数据工具中 AI 驱动 SQL 生成的可靠性和准确性。 实验使用 GPT-4.1 mini 和 nano 作为测试模型，发现将列名包含在模式列表中或软化“不要调用 describe_table”的建议可以减少错误。该研究是使用 Claude Fable 5 在 Claude Code 中作为异步任务进行的。

rss · Simon Willison · 7月2日 18:25

**背景**: DSPy（声明式自改进 Python）是一个通过编写结构化签名而非脆弱提示来构建 AI 系统的框架，支持自动优化。Datasette Agent 是 Datasette 的开源 AI 助手，可执行只读 SQL 查询以回答用户关于数据的问题。系统提示优化对于改善 LLM 在特定任务中的行为至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://dspy.ai/">DSPy</a></li>
<li><a href="https://github.com/stanfordnlp/dspy">GitHub - stanfordnlp/ dspy : DSPy : The framework for...</a></li>
<li><a href="https://datasette.io/blog/2026/datasette-agent/">Datasette Agent, an extensible AI assistant for Datasette - Datasette Blog</a></li>

</ul>
</details>

**标签**: `#DSPy`, `#prompt engineering`, `#LLM`, `#SQL`, `#Datasette`

---

<a id="item-12"></a>
## [Simon Willison 发布 llm-coding-agent 0.1a0](https://simonwillison.net/2026/Jul/2/llm-coding-agent/#atom-everything) ⭐️ 6.0/10

Simon Willison 发布了 llm-coding-agent 的早期 alpha 版本 (0.1a0)，这是一个基于他的 LLM 库构建的简单编码代理，灵感来自 Claude Code。该代理提供读取、编辑文件和执行命令的工具，可通过 'uvx --prerelease=allow --with llm-coding-agent llm code' 运行。 此次发布展示了 LLM 库如何演变为一个代理框架，使开发者能够构建自定义编码代理。它降低了创建 AI 辅助编码工具的门槛，并可能激发开源社区的进一步实验。 该代理包含 edit_file、execute_command、list_files、read_file 和 search_files 等工具，并提供了基于 CodingAgent 类的 Python API。它使用 Claude Code for web 开发，规范和提交记录已在 GitHub 上公开。

rss · Simon Willison · 7月2日 19:33

**背景**: Simon Willison 的 LLM 库是一个开源命令行工具和 Python 库，用于与大型语言模型交互。它最近被重构以支持多模态输入和流式传输，演变为一个代理框架。Anthropic 的 Claude Code 是一个代理式编码工具，可通过自然语言读取代码库、编辑文件和运行命令。此次发布是 Willison 的 Fable 5 实验系列的一部分。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://simonwillison.net/2026/Jul/2/llm-coding-agent/">Release: llm -coding-agent 0.1a0 | Simon Willison ’s Weblog</a></li>
<li><a href="https://claude.com/product/claude-code">Claude Code by Anthropic | AI Coding Agent , Terminal, IDE</a></li>
<li><a href="https://docs.anthropic.com/en/docs/agents-and-tools/claude-code/overview">Claude Code overview - Anthropic</a></li>

</ul>
</details>

**标签**: `#coding agent`, `#LLM`, `#Python`, `#open source`

---