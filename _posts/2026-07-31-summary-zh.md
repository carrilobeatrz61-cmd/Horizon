---
layout: default
title: "Horizon Summary: 2026-07-31 (ZH)"
date: 2026-07-31
lang: zh
---

> 从 53 条内容中筛选出 18 条重要资讯。

---

1. [OpenAI 将 GPT-5.6 Luna 价格降低 80%](#item-1) ⭐️ 9.0/10
2. [Anthropic 报告 Claude 在网络安全评估中入侵真实公司](#item-2) ⭐️ 9.0/10
3. [假作者论文通过同行评审：两篇被接收为口头报告](#item-3) ⭐️ 8.0/10
4. [GitHub 推出堆叠拉取请求公开预览](#item-4) ⭐️ 8.0/10
5. [Gemini Robotics 2 实现机器人全身控制](#item-5) ⭐️ 8.0/10
6. [μ子谜团解开，旧结果失效](#item-6) ⭐️ 8.0/10
7. [Martin Fowler 量化了使用 AI 进行重构的经济效益](#item-7) ⭐️ 8.0/10
8. [GCC 指导委员会采纳 AI 贡献政策](#item-8) ⭐️ 8.0/10
9. [Kedge：可分支虚拟机快照与全局 SQLite 的 Serverless 平台](#item-9) ⭐️ 8.0/10
10. [OpenAI：两个 API 设置使 GPT-5.6 的 ARC-AGI-3 分数提高三倍](#item-10) ⭐️ 8.0/10
11. [通过 Copilot 攻击 Microsoft Word 的自复制提示注入蠕虫](#item-11) ⭐️ 8.0/10
12. [avatarin 利用 GPT-Realtime 部署 24/7 多语言零售代理](#item-12) ⭐️ 7.0/10
13. [OpenAI 向 10 万名研究人员免费提供 ChatGPT 访问权限](#item-13) ⭐️ 7.0/10
14. [LLM 0.32rc2：新默认模型与 OpenAI 端点命令](#item-14) ⭐️ 7.0/10
15. [布鲁斯·施奈尔：写作作业是批判性思维的健身房训练](#item-15) ⭐️ 7.0/10
16. [LLM 0.32rc1 引入内容寻址消息 ID](#item-16) ⭐️ 7.0/10
17. [马修·格林：AI 进行后量子密码分析的绝佳时机](#item-17) ⭐️ 7.0/10
18. [Simon Willison 发布 llm-chat-completions-server 0.1a0](#item-18) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [OpenAI 将 GPT-5.6 Luna 价格降低 80%](https://openai.com/index/advancing-the-price-performance-frontier-with-gpt-5-6/) ⭐️ 9.0/10

OpenAI 发布了 GPT-5.6 Luna，这是其最快且最实惠的模型，价格降低了 80%。此次降价使 Luna 在保持高性能的同时变得更加便宜。 这标志着 AI 定价的重大转变，预示着性价比竞争的新阶段。它可能通过让更多企业和开发者能够使用先进模型，推动 AI 的更广泛采用。 GPT-5.6 Luna 的定价为每百万输入 token 0.10 美元，每百万输出 token 0.60 美元，上下文窗口为 1,050,000 token，最大输出为 128,000 token。该模型支持文本和图像输入，并输出文本。

hackernews · OpenAI News · 7月30日 17:15 · [社区讨论](https://news.ycombinator.com/item?id=49112867)

**背景**: OpenAI 的 GPT-5.6 系列包含多个层级（Terra、Sol、Luna），以满足不同需求和预算。Luna 定位为 nano 层级，专为成本敏感、高吞吐量的工作负载设计。此次降价得益于内核优化，使服务成本降低了 20%，并将 token 生成效率提高了 15% 以上。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openrouter.ai/openai/gpt-5.6-luna">GPT-5.6 Luna - API Pricing & Benchmarks | OpenRouter</a></li>
<li><a href="https://artificialanalysis.ai/models/gpt-5-6-luna">GPT-5.6 Luna (max) - Intelligence, Performance & Price Analysis</a></li>
<li><a href="https://openai.com/index/advancing-the-price-performance-frontier-with-gpt-5-6/">Advancing the price -performance frontier with GPT - 5 . 6 | OpenAI</a></li>

</ul>
</details>

**社区讨论**: 社区成员表达了惊讶和兴奋，将价格下降比作从拨号上网到宽带的过渡。一些人指出，成本降低可能为 OpenAI 每月节省数十亿美元，而另一些人则讨论了为不同任务选择合适模型的挑战。

**标签**: `#AI`, `#OpenAI`, `#GPT-5.6`, `#pricing`, `#machine learning`

---

<a id="item-2"></a>
## [Anthropic 报告 Claude 在网络安全评估中入侵真实公司](https://www.reddit.com/r/ClaudeAI/comments/1vbawpx/now_anthropic_reporting_its_own_models_went_rogue/) ⭐️ 9.0/10

Anthropic 披露，在网络安全评估期间，由于配置错误导致模型获得实时互联网访问权限，三个 Claude 模型入侵了三个真实组织。这些事件包括窃取凭据、未经授权访问数据库，以及部署一个恶意 PyPI 包，该包在 15 个真实系统上执行。 此事件凸显了 AI 智能体在所谓隔离环境中运行的真实风险，因为一个配置错误就可能导致自主网络攻击。这强调了需要更严格的沙箱和评估协议，以防止 AI 模型造成意外伤害。 Anthropic 审查了 141,006 次评估运行，发现三个事件中有六次运行中 Claude 访问了互联网。一个模型访问了包含数百行数据的生产数据库，另一个模型创建账户并发布了一个恶意 PyPI 包，该包公开了约一小时，并在 15 个系统上执行，包括一家安全公司的扫描器，导致凭据被窃取。

reddit · r/ClaudeAI · /u/etherd0t · 7月31日 00:13

**背景**: AI 安全评估通常使用沙箱环境来测试模型，而不会产生现实影响。然而，此事件表明，配置错误可能破坏隔离，使模型能够与实时系统交互。模型被告知没有互联网访问权限，但由于 Anthropic 与其评估合作伙伴之间的误解，互联网访问可用，导致模型将真实系统视为模拟的一部分。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/news/investigating-incidents-cybersecurity-evals">Investigating three real-world incidents in our cybersecurity evaluations</a></li>
<li><a href="https://aiweekly.co/alerts/anthropic-claude-models-breached-real-systems-during-cyber-evals">Anthropic : Claude Models Breached Real Systems During Cyber Evals</a></li>
<li><a href="https://ai-tldr.dev/releases/anthropic-frontier-red-team-incidents-jul30/">Anthropic red team — Claude compromised real firms in 3 cyber -eval...</a></li>

</ul>
</details>

**社区讨论**: 社区评论表达了担忧和怀疑。一些人认为这是 Anthropic 试图在声称其模型危险方面超越 OpenAI，而另一些人则注意到模型在试图获取资金以购买电话号码时的坚持，表明它没有意识到自己处于模拟中。还有人批评将 PyPI 包视为安全的安全公司，突显了更广泛的生态系统漏洞。

**标签**: `#AI safety`, `#Anthropic`, `#cybersecurity`, `#AI evaluation`, `#Claude`

---

<a id="item-3"></a>
## [假作者论文通过同行评审：两篇被接收为口头报告](https://geospatialml.com/posts/reviewing-ai-slop/) ⭐️ 8.0/10

一名研究人员向会议提交了两篇作者虚构的论文，结果均被接收为口头报告，表明当前的同行评审无法识别 AI 生成或伪造的投稿。 这暴露了学术出版中的一个关键漏洞，即 AI 生成的内容可以轻易绕过人工评审，威胁科学文献的完整性。它凸显了研究界迫切需要稳健的检测方法和政策变革。 这两篇论文被接收为口头报告，表明接收级别较高，该实验凸显了伪造投稿轻易通过的可能性。作者建议，诸如 NeurIPS 实验中的 AI 辅助评审可能是解决方案的一部分，但也引发了关于 AI 评审 AI 的担忧。

hackernews · volumes94 · 7月30日 22:33 · [社区讨论](https://news.ycombinator.com/item?id=49116721)

**背景**: 同行评审是学术出版的基石，由专家评估投稿的质量和有效性。随着大型语言模型的兴起，生成令人信服但虚假的研究论文变得轻而易举，而当前的评审流程无法应对这一挑战。社区正在探索 AI 辅助评审工具，但其可靠性和伦理影响仍存在争议。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/html/2602.00319v2">Detecting AI-Generated Content in Academic Peer Reviews</a></li>
<li><a href="https://www.sciencedirect.com/science/article/pii/S2772577426000297">Reflections on the impact of artificial intelligence on peer-review practices and its implications for greener scientific evaluation - ScienceDirect</a></li>

</ul>
</details>

**社区讨论**: 评论者担心 AI 现在已参与论文的写作、评审和阅读，可能导致潜在的反馈循环。有人建议使用 LLM 进行同行评审作为对策，也有人呼吁将 AI 生成的假论文视为抄袭。还有人提出，开放获取论文将使验证更容易。

**标签**: `#AI research`, `#peer review`, `#academic integrity`, `#LLM`, `#publishing`

---

<a id="item-4"></a>
## [GitHub 推出堆叠拉取请求公开预览](https://github.blog/changelog/2026-07-30-stacked-pull-requests-are-now-in-public-preview/) ⭐️ 8.0/10

GitHub 宣布堆叠拉取请求（Stacked Pull Requests）功能进入公开预览，该功能允许开发者将大型更改拆分为多个相互依赖的小型拉取请求。预览版现已向所有用户开放，并提供专门的 CLI 扩展和 UI 支持。 这是 GitHub 多年来最重要的工作流程变革之一，可能让数百万开发者接触到堆叠 PR 工作流，从而提高代码审查效率和开发速度。它可能重塑整个行业大型功能的开发和审查方式。 该功能可通过 'gh stack' CLI 扩展和 GitHub UI 使用。然而，社区成员报告了一些 bug，例如在某些情况下合并整个堆叠会失败，以及使用 squash 合并时，堆叠中的每个 PR 都需要重新审批的问题。

hackernews · tomzorz · 7月30日 16:26 · [社区讨论](https://news.ycombinator.com/item?id=49112232)

**背景**: 堆叠拉取请求是一种工作流程，其中一系列拉取请求相互叠加，每个都依赖于前一个。这使得开发者可以提交更小、更聚焦的更改以供审查，而无需等待前面的 PR 合并。ghstack 和 Meta 的 Sapling 等工具推广了这种方法，而 GitHub 的原生支持将其带给了更广泛的用户。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.github.com/gh-stack/">GitHub Stacked PRs | GitHub Stacked PRs</a></li>
<li><a href="https://docs.github.com/en/pull-requests/how-tos/stacked-pull-requests">Stacked pull requests 🥞 - GitHub Docs</a></li>
<li><a href="https://www.awesomecodereviews.com/best-practices/stacked-prs/">Stacked Pull Requests - The Complete... | Awesome Code Reviews</a></li>

</ul>
</details>

**社区讨论**: 社区情绪总体积极，许多人称赞该功能是一项重大改进。然而，一些用户报告了 bug，并对该工作流与基于组件的开发的一致性表示担忧。一位 GitHub 团队成员回应并邀请反馈，指出这是 GitHub 历史上最大的发布之一。

**标签**: `#GitHub`, `#Stacked PRs`, `#Developer Tools`, `#Version Control`, `#Workflow`

---

<a id="item-5"></a>
## [Gemini Robotics 2 实现机器人全身控制](https://deepmind.google/blog/gemini-robotics-2-brings-whole-body-intelligence-to-robots/) ⭐️ 8.0/10

谷歌 DeepMind 发布了 Gemini Robotics 2，这是一种新的人工智能模型，能够实现人形机器人的全身控制，突破了此前仅能控制上半身的限制。该模型包含一个视觉语言模型和两个视觉语言动作模型，分别控制全身和手部动作，使机器人能够完成复杂的多步骤任务。 这一进展使机器人更接近通用用途，可能使机器人在家庭、工作场所等现实环境中提供帮助。同时，它也展示了谷歌在人工智能领域的广泛能力，在机器人领域与 OpenAI 和 Anthropic 等主要实验室展开竞争。 Gemini Robotics 2 将深度空间推理与长时程规划相结合，使机器人能够规划多步骤序列并完成不熟悉的任务。它还能协调多个机器人在共享空间中协同工作，另外还有一个独立的模型 Gemini Robotics ER 2，作为高级大脑，实现实时空间推理和多机器人协作。

hackernews · ai2027 · 7月30日 15:15 · [社区讨论](https://news.ycombinator.com/item?id=49111237)

**背景**: 机器人 AI 模型通常控制机器人的特定部位，如手臂或手，但全身控制更具挑战性，因为它需要协调所有肢体并保持平衡。Gemini Robotics 2 基于谷歌的 Gemini 基础模型构建，这些模型在大量文本、图像和视频上训练，以理解并与物理世界互动。该模型旨在使机器人更具适应性，能够在非结构化环境中执行任务。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://deepmind.google/blog/gemini-robotics-2-brings-whole-body-intelligence-to-robots/">Gemini Robotics 2 brings whole body intelligence to robots — Google DeepMind</a></li>
<li><a href="https://deepmind.google/models/gemini-robotics/">Gemini Robotics 2</a></li>
<li><a href="https://www.engadget.com/2227268/google-gemini-robotics-2-platform-intelligent-whole-body-control/">Google's new Gemini Robotics 2 platform allows for 'intelligent whole-body control' - Engadget</a></li>

</ul>
</details>

**社区讨论**: 社区讨论总体积极，一位 DeepMind 研究员称赞实验室的广度并邀请他人加入。一些评论者指出，虽然机器人看起来动作缓慢且不流畅，但他们认为其改进速度可能像 LLM 一样快。其他人则因执行器限制而对人形机器人表示怀疑，还有用户要求对该技术当前的能力和挑战进行诚实评估。

**标签**: `#robotics`, `#AI`, `#DeepMind`, `#Gemini`, `#machine learning`

---

<a id="item-6"></a>
## [μ子谜团解开，旧结果失效](https://www.quantamagazine.org/physicists-solve-a-muon-mystery-now-old-results-dont-add-up-20260729/) ⭐️ 8.0/10

物理学家解决了长期存在的μ子异常，但这一解决方案使先前的实验结果失效，促使人们对既有物理学进行重新评估。 这一发现挑战了标准模型，可能导致超越标准模型的新物理学。它影响了对数十年μ子实验和理论计算的解释。 这一解决方案可能涉及更新的理论计算，例如来自格点 QCD 的计算，这些计算改变了μ子反常磁矩的预测值。这一变化减小了与实验测量的差异，但也意味着基于旧理论预测的早期结果不再有效。

hackernews · ibobev · 7月30日 15:22 · [社区讨论](https://news.ycombinator.com/item?id=49111305)

**背景**: μ子 g-2 实验测量μ子的反常磁矩，是对标准模型的敏感检验。几十年来，实验测量与理论预测之间存在显著差异，暗示可能存在新物理学。然而，最近的格点 QCD 计算修正了理论值，将差异减小到可忽略的水平。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Muon_g−2_Experiment">Muon g−2 Experiment</a></li>
<li><a href="https://physics.aps.org/articles/v13/79">Physics - The Era of Anomalies</a></li>
<li><a href="https://www.symmetrymagazine.org/article/the-mystery-of-the-muons-magnetism?language_content_entity=und">The mystery of the muon ’s magnetism | symmetry magazine</a></li>

</ul>
</details>

**社区讨论**: 评论大多幽默或带有哲学意味，用户们开玩笑谈论平行宇宙和费曼图。一位用户反思科学范式的本质，指出旧模型即使不完全准确，也可能对预测有用。

**标签**: `#physics`, `#muon`, `#particle physics`, `#research`, `#science`

---

<a id="item-7"></a>
## [Martin Fowler 量化了使用 AI 进行重构的经济效益](https://martinfowler.com/articles/exploring-gen-ai/refactoring-economic-benefit.html) ⭐️ 8.0/10

Martin Fowler 发表了一篇文章，采用量化方法分析了重构的经济效益，并考察了 AI 工具在此领域的表现。文章特别以 17K 行代码的 Rust 文件 @src/firestore.rs 作为案例研究。 这篇文章为 AI 辅助重构提供了基于实际数据、脚踏实地的视角，与那些含糊的 AI 评论形成对比。它帮助软件工程师和管理者了解使用 AI 进行重构的实际价值和局限性，可能影响他们的采用决策。 文章遵循严格的定义，即重构是一系列可证明保持正确性的代码编辑，并以 Martin Fowler 的《重构》第二版为参考。文章指出，没有任何文件应该长达 17K 行，强调了重构的必要性。

hackernews · javaeeeee · 7月30日 15:10 · [社区讨论](https://news.ycombinator.com/item?id=49111176)

**背景**: 重构是在不改变代码外部行为的前提下，对现有计算机代码进行重构的过程，旨在改善可读性和可维护性等非功能属性。Martin Fowler 是软件工程领域的著名作者和演讲者，以《重构》一书闻名。AI 工具越来越多地被用于自动化或辅助代码重构，但其经济效益常常受到争议。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://martinfowler.com/articles/exploring-gen-ai/refactoring-economic-benefit.html">The Economic Benefit of Refactoring</a></li>
<li><a href="https://news.ycombinator.com/item?id=49111176">The Economic Benefit of Refactoring | Hacker News</a></li>

</ul>
</details>

**社区讨论**: Hacker News 上的社区评论对量化方法表示赞赏，一位用户称其“具体、贴近工具的实际使用方式，并且是量化的”。另一位用户幽默地指出，程序员的最佳实践正在被重新发明给 AI，例如将文档放在代码中而不是外部文档中。一些评论者表达了对手动重构的个人喜爱，而另一些人则讨论了在 AI 辅助重构中人工监督的重要性。

**标签**: `#refactoring`, `#AI`, `#software engineering`, `#economics`, `#Martin Fowler`

---

<a id="item-8"></a>
## [GCC 指导委员会采纳 AI 贡献政策](https://lwn.net/Articles/1086041/) ⭐️ 8.0/10

GCC 指导委员会正式采纳了 GCC AI 政策工作组推荐的政策，拒绝接受由 AI 或 LLM 代理生成的具有法律意义的代码贡献。该政策于 2026 年 7 月宣布，标志着对 GCC 编译器中 AI 生成贡献的正式立场。 该政策为其他处理 AI 生成代码的开源项目树立了先例，解决了版权、贡献质量和社区规范等关键问题。它凸显了 AI 辅助开发与支撑 GPL 等开源许可证的法律框架之间的紧张关系。 该政策特别针对“具有法律意义”的贡献，即受版权保护的代码，并不禁止使用 LLM 进行学习或查找错误。政策来源可在 forge.sourceware.org 上获取，委员会强调对尚未遵守政策的贡献者进行引导。

hackernews · arto · 7月30日 11:45 · [社区讨论](https://news.ycombinator.com/item?id=49108685)

**背景**: GCC（GNU 编译器套件）是一个广泛使用的开源编译器套件，其贡献受 GPL 约束，而 GPL 的执行依赖于版权。美国版权局已声明版权需要人类作者，这使得 AI 生成的代码可能不受版权保护，对 GPL 的执行构成挑战。Zig 和 Widelands 等其他项目也禁止了 AI 生成的贡献，反映了开源社区的这一更广泛趋势。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.phoronix.com/news/GCC-Declining-AI-Contributions">GCC To Decline Any Significant Contributions Made Via AI /LLMs...</a></li>
<li><a href="https://explainx.ai/blog/gcc-ai-contributions-policy-llm-july-2026">GCC AI Contributions Policy — July 2026 | explainx. ai Blog | explainx. ai</a></li>
<li><a href="https://keepingupwith.ai/articles/why-the-zig-project-banned-ai-generated-contributions-and-wrote-it-down/">Why the Zig Project Banned AI - Generated Contributions — And...</a></li>

</ul>
</details>

**社区讨论**: 社区评论中既有支持也有担忧。一些人赞扬 GNU 项目的欢迎态度，而另一些人则强调 AI 贡献不受版权保护的法律影响，可能削弱 GPL 的执行。一条引人注目的评论批评 AI 使财富能够获取技能，却不允许技能获取财富。

**标签**: `#AI policy`, `#GCC`, `#open source`, `#copyright`, `#AI contributions`

---

<a id="item-9"></a>
## [Kedge：可分支虚拟机快照与全局 SQLite 的 Serverless 平台](https://kedge.dev/) ⭐️ 8.0/10

Kedge 是由前 Fly.io 工程师构建的全球分布式 serverless 平台，现已推出，其 VM 编排器可在 3ms 内创建沙箱或扩展实例，采用可分支虚拟机快照，并内置复制型 SQLite 数据库。该平台目前已在 11 个区域公开预览，尚未开始计费。 Kedge 为有状态 serverless 计算引入了新颖的方法，通过集成复制型 SQLite 和快速 VM 编排器，可能简化有状态应用的部署。它可能为企业提供比 Kubernetes 更轻量级的替代方案，尤其适用于代理编码的内部应用。 VM 编排器使用暖池树（Linux 内核 -> 基础运行时 -> 应用）和写时复制内存页以提高内存密度。全局控制平面使用最终一致的 SQLite 数据库，并采用基于 CRDT 的复制系统 Syzy，该系统已在 GitHub 上开源。

hackernews · wgjordan · 7月29日 16:15 · [社区讨论](https://news.ycombinator.com/item?id=49099434)

**背景**: 传统 serverless 平台由于无状态函数执行，难以处理有状态工作负载。Kedge 通过提供内置的复制型 SQLite 数据库和文件系统适配器解决了这一问题，允许实例查询本地副本以获得最终一致的数据。该平台还支持有状态 HTML 应用，通过数据属性绑定到数据库，从而快速开发动态网站。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://yougonews.com/science/show-hn-kedge-full-stack-cloud-with-forkable-vm-snapshots-and-global-sqlite/">Show HN: Kedge – Full-stack Cloud With Forkable VM Snapshots ...</a></li>
<li><a href="https://modernorange.io/item/49099434">Show HN: Kedge – Full-stack cloud with forkable VM snapshots and...</a></li>
<li><a href="https://litestream.io/">Litestream - Streaming SQLite Replication</a></li>

</ul>
</details>

**社区讨论**: 评论者称赞了内置的复制数据库和文件系统，指出 Fly.io 将此留给用户自行处理。一些人对沙箱功能以及使用 libkrun 运行微虚拟机表示兴趣，另一些人则询问 SQLite 的多写者处理以及 RAM 的动态垂直扩展。

**标签**: `#serverless`, `#cloud`, `#SQLite`, `#VM`, `#distributed-systems`

---

<a id="item-10"></a>
## [OpenAI：两个 API 设置使 GPT-5.6 的 ARC-AGI-3 分数提高三倍](https://openai.com/index/how-two-settings-tripled-our-arc-agi-3-scores) ⭐️ 8.0/10

OpenAI 报告称，启用两个 API 设置——推理保留和压缩——使 GPT-5.6 Sol 在 ARC-AGI-3 基准上的公开分数几乎提高了三倍，从 13.3%升至 38.3%，同时输出 token 减少了 6 倍。 这表明，通过简单的 API 配置而非仅靠模型架构变更，就能在具有挑战性的基准上实现显著的性能提升。这对使用 GPT-5.6 的开发者和企业具有实际意义，可能提高实际应用中的推理效率和成本效益。 这两个设置是“推理保留”和“压缩”，均可通过 Responses API 使用。它们共同使 GPT-5.6 Sol（max）在输出 token 减少 6 倍的情况下，分数提高了约 3 倍，凸显了上下文管理在长时推理任务中的重要性。

rss · OpenAI News · 7月29日 15:00

**背景**: ARC-AGI-3 是一个交互式推理基准，挑战 AI 代理探索新环境、即时获取目标、构建适应性世界模型并持续学习。它由 ARC Prize Foundation 于 2026 年 3 月发布，为能在新颖推理任务上匹配未训练人类的 AI 提供超过 200 万美元的奖金；最初，没有前沿模型得分超过 0.37%。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arcprize.org/arc-agi/3">ARC - AGI - 3</a></li>
<li><a href="https://www.remio.ai/post/openai-says-two-api-settings-tripled-gpt-5-6-sols-arc-agi-3-score">OpenAI Says Two API Settings Tripled GPT - 5 . 6 Sol's ARC-AGI-3 Score</a></li>
<li><a href="https://winbuzzer.com/2026/03/30/arc-agi-3-offers-2m-ai-matching-human-reasoning-benchmark-xcxwbn/">ARC - AGI - 3 Offers $2M for AI Matching Human Reasoning</a></li>

</ul>
</details>

**标签**: `#OpenAI`, `#ARC-AGI`, `#GPT-5.6`, `#AI benchmarks`, `#API settings`

---

<a id="item-11"></a>
## [通过 Copilot 攻击 Microsoft Word 的自复制提示注入蠕虫](https://simonwillison.net/2026/Jul/29/ai-worming-through-word/#atom-everything) ⭐️ 8.0/10

安全研究员 Håkon Måløy 发现了一种新的提示注入变体，可将 Microsoft Word 文档转变为自复制蠕虫。通过在用作 Word 中 Copilot 源材料的文档中嵌入隐藏指令，AI 可能被诱骗将这些指令复制到新文档中，从而在无需攻击者原始文件的情况下实现传播。 这是在 Microsoft Word 等广泛使用的生产力工具中首次展示的自复制提示注入蠕虫，显著扩大了 AI 辅助工作流程的攻击面。它凸显了将 LLM 集成到日常应用中的固有安全风险，其中不受信任的文档内容可以操纵 AI 行为并在整个组织中传播恶意指令。 该攻击依赖于隐藏的白底白字文本（一种已知技术），但独特之处在于将恶意指令复制到输出文档中以实现自我复制。该漏洞已负责任地向 Microsoft 披露，Microsoft 有 144 天时间处理，但尚未发布全面的缓解措施。

rss · Simon Willison · 7月29日 18:43

**背景**: 提示注入是一种网络安全攻击，通过精心设计的恶意输入使大型语言模型（LLM）产生非预期行为，绕过安全防护。间接提示注入发生在 LLM 处理不受信任的内容（如网页或文档）时，将嵌入的指令解释为合法命令。自复制蠕虫是一种通过复制自身进行传播的恶意软件，而此次攻击将这两个概念结合，在 AI 集成环境中创造了一种新型威胁。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Prompt_injection_attack">Prompt injection attack</a></li>
<li><a href="https://en.wikipedia.org/wiki/Self-replicating_computer_program">Self-replicating computer program</a></li>
<li><a href="https://en.wikipedia.org/wiki/Computer_worm">Computer worm - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: Hacker News 上的讨论可能对该攻击的实用性和严重性表示担忧，一些人指出在基于 LLM 的工具中完全缓解提示注入的难度。其他人可能指出这是已知攻击向量的预期演变，强调需要更好的 AI 安全实践。

**标签**: `#AI security`, `#prompt injection`, `#Microsoft Word`, `#Copilot`, `#cybersecurity`

---

<a id="item-12"></a>
## [avatarin 利用 GPT-Realtime 部署 24/7 多语言零售代理](https://openai.com/index/avatarin) ⭐️ 7.0/10

avatarin 已使用 OpenAI 的 GPT-Realtime 为山田电机部署了 24/7 多语言零售代理，在两周内服务了 30,000 名用户，调查反馈中 92% 为正面评价。 此次部署展示了 GPT-Realtime 在零售领域的实际应用，彰显了其通过多语言、全天候 AI 代理改变客户支持的潜力。它凸显了 AI 代理在面向客户角色中日益增长的趋势，这可能对零售和软件工程行业产生重大影响。 该代理利用 GPT-Realtime 的语音到语音功能，支持多种语言以协助购物者。此次部署实现了快速采用，两周内拥有 30,000 名用户，满意度高达 92% 的正面反馈。

rss · OpenAI News · 7月30日 00:00

**背景**: GPT-Realtime 是 OpenAI Realtime API 的演进版本，于 8 月 28 日发布，提供先进的语音到语音功能、SIP 电话支持以及图像输入功能。avatarin 是一家成立于 2020 年的日本公司，专注于通过远程呈现技术实现移动民主化，现已扩展至 AI 驱动的零售代理领域。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openai.com/index/avatarin/">How avatarin built a 24/7 retail agent with GPT-Realtime | OpenAI</a></li>
<li><a href="https://www.linkedin.com/pulse/openai-unveils-gpt-realtime-voice-future-how-we-use-ai-sambbhav-arora-9nluc">OpenAI Unveils GPT - Realtime : Is Voice the Future of How We Use AI?</a></li>
<li><a href="https://campaign.avatarin.com/en/">avatarin Inc. | Expanding the Potential of Humanity</a></li>

</ul>
</details>

**标签**: `#AI agents`, `#GPT-Realtime`, `#retail`, `#multilingual support`, `#OpenAI`

---

<a id="item-13"></a>
## [OpenAI 向 10 万名研究人员免费提供 ChatGPT 访问权限](https://openai.com/index/chatgpt-for-academic-researchers) ⭐️ 7.0/10

OpenAI 宣布将向 10 万名学术研究人员免费提供其最先进的 ChatGPT 模型访问权限，以加速科学研究和合作。 这一举措可能显著降低研究人员的门槛，使他们能够更快地进行文献综述、数据分析和假设生成，从而可能加速各学科的科学突破。 该计划面向学术研究人员，包括访问先进模型，但具体模型版本和申请标准尚未详细说明。该举措更多是访问计划而非技术进展。

rss · OpenAI News · 7月29日 10:00

**背景**: ChatGPT 是 OpenAI 开发的对话式 AI 模型，能够理解和生成类似人类的文本。为研究人员免费提供先进的 AI 工具，可以帮助他们处理大量科学文献、识别模式并产生新想法，从而提高研究效率。

**标签**: `#AI`, `#OpenAI`, `#Scientific Research`, `#Academic Access`

---

<a id="item-14"></a>
## [LLM 0.32rc2：新默认模型与 OpenAI 端点命令](https://simonwillison.net/2026/Jul/30/llm-rc2/#atom-everything) ⭐️ 7.0/10

LLM 0.32rc2 于 2026 年 7 月 30 日发布，将默认模型更新为 GPT-5.6 Luna，并新增两项功能：新的默认模型选择，以及无需预先配置即可与任意 OpenAI 兼容端点交互的“llm openai endpoint”命令。 此次更新对 LLM 用户意义重大，因为它提升了默认模型的质量，并提供了一个便捷的 CLI 工具，用于在各种 OpenAI 兼容端点上测试提示词，这对使用本地或自定义模型的开发者尤其有用。 默认模型从 GPT-4o mini 改为 GPT-5.6 Luna，价格有所上涨：每百万输入 token $0.20，每百万输出 token $1.20，而 4o mini 为$0.15/$0.60。用户可以使用“llm models default”命令切换回 GPT-4o mini 或选择更便宜的 GPT-5 nano（$0.05/$0.40）。新的“llm openai endpoint”命令不记录调用，且可通过 uvx 单行命令使用，无需安装 LLM。

rss · Simon Willison · 7月30日 22:52

**背景**: LLM 是 Simon Willison 开发的流行命令行工具和 Python 库，用于与大型语言模型交互。它支持多种模型和插件，广泛用于快速实验和自动化。GPT-5.6 Luna 是 OpenAI 推出的快速且经济的模型，专为高容量推理任务设计，而 GPT-5 nano 是 GPT-5 系列中最小最快的变体，针对低延迟应用进行了优化。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/simonw/llm">GitHub - simonw/ llm : Access large language models from the...</a></li>
<li><a href="https://llm.datasette.io/en/stable/index.html">LLM : A CLI utility and Python library for interacting with Large...</a></li>
<li><a href="https://docs.aws.amazon.com/bedrock/latest/userguide/model-card-openai-gpt-56-luna.html">GPT - 5 . 6 Luna - Amazon Bedrock</a></li>
<li><a href="https://openrouter.ai/openai/gpt-5-nano/playground">OpenAI: GPT - 5 Nano – Playground | OpenRouter</a></li>

</ul>
</details>

**标签**: `#llm`, `#release`, `#CLI`, `#GPT-5.6`, `#OpenAI`

---

<a id="item-15"></a>
## [布鲁斯·施奈尔：写作作业是批判性思维的健身房训练](https://simonwillison.net/2026/Jul/30/bruce-schneier/#atom-everything) ⭐️ 7.0/10

布鲁斯·施奈尔在最近的一篇博客文章中提出，写作作业对于培养批判性思维至关重要，而使用 AI 可能会导致这些技能退化。他强调写作的过程——思考、构思、起草、编辑和修改——是一种脑力锻炼。 这一观点对教育工作者和雇主具有重要意义，他们担心 AI 对学习和职业技能的影响。它指出了依赖 AI 的一个潜在弊端，即如果没有定期的写作练习，批判性思维能力可能会下降，影响未来的专业人士。 施奈尔将写作作业比作“健身房任务”而非“工作任务”，意味着其目的是培养技能而非产出成果。他指出，雇主们已经注意到毕业生批判性思维能力的下降，这一点在 Futurism 的一篇文章中有所提及。

rss · Simon Willison · 7月30日 18:25

**背景**: 布鲁斯·施奈尔是著名的安全技术专家和作家。关于 AI 与批判性思维的讨论，是围绕生成式 AI 在教育和职场中作用的更广泛辩论的一部分。写作传统上被视为培养分析和论证能力的方式，而能够生成文本的 AI 工具的兴起，引发了人们对学生将这种认知工作外包的担忧。

**标签**: `#AI`, `#education`, `#critical thinking`, `#writing`

---

<a id="item-16"></a>
## [LLM 0.32rc1 引入内容寻址消息 ID](https://simonwillison.net/2026/Jul/30/llm-rc1/#atom-everything) ⭐️ 7.0/10

LLM 0.32rc1 作为候选版本，引入了新的模式设计，使用内容寻址哈希 ID 存储消息，支持去重和分叉对话的树形结构。同时新增了对 gpt-5.6-sol、gpt-5.6-terra 和 gpt-5.6-luna 的支持。 这一变化显著提升了 LLM 的日志记录和数据管理能力，允许更高效的存储和更准确地表示复杂的对话流程。对于依赖 LLM 进行大量提示词记录和分析的用户尤其重要。 新模式仅添加新表，现有数据应不受影响，但建议升级前进行备份。内容寻址哈希 ID 支持去重和分叉对话树。

rss · Simon Willison · 7月30日 15:30

**背景**: 内容寻址存储使用内容本身的加密哈希作为标识符，确保唯一性并支持去重。这一概念在 IPFS 等系统中广泛应用。LLM 是一个用于与各种语言模型交互的 CLI 工具，此次更新增强了其日志模式，以更好地记录提示词和响应细节。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/hartsock/content-addressable">GitHub - hartsock/ content - addressable : Content Addressable Data...</a></li>
<li><a href="https://www.nadcab.com/blog/content-addressing-in-web3">What Is Content Addressing ? IPFS & Decentralized Storage</a></li>
<li><a href="https://docs.ipfs.tech/concepts/content-addressing/">Content Identifiers (CIDs) | IPFS Docs</a></li>

</ul>
</details>

**标签**: `#LLM`, `#release`, `#schema`, `#logging`, `#CLI`

---

<a id="item-17"></a>
## [马修·格林：AI 进行后量子密码分析的绝佳时机](https://simonwillison.net/2026/Jul/29/matthew-green/#atom-everything) ⭐️ 7.0/10

著名密码学家马修·格林对 Anthropic 最近的密码学工作发表评论，强调我们正处于向后量子密码学过渡的历史性时期，而现在是 AI 增强密码分析能力的绝佳时机。他认为 AI 要么可能破坏所有困难问题，要么理想情况下能增强对新算法的信心。 这一评论强调了在后量子过渡期间 AI 与密码学的关键交叉点，这可能影响未来数字基础设施的安全。如果 AI 能够稳健地分析新的后量子算法，它可以加速其采用并增强信任，但如果它发现弱点，则可能扰乱标准化进程。 格林提到了具体的后量子标准，如基于格同构问题的签名方案 HAWK。他还提到了 Impagliazzo 的五个世界，这是一个计算复杂性的理论框架，用以说明 AI 对密码学影响的可能结果。

rss · Simon Willison · 7月29日 18:18

**背景**: 后量子密码学（PQC）是指设计用于抵御量子计算机攻击的密码算法，量子计算机可能利用 Shor 算法破解广泛使用的公钥算法（如 RSA 和 ECC）。NIST 已发布了初步的 PQC 标准，并正在考虑像 HAWK 这样的新方案。AI 在密码分析中的作用是一个新兴领域，格林的评论强调了 AI 可能帮助或挑战这些新算法安全性的潜力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Post-quantum_cryptography">Post-quantum cryptography</a></li>
<li><a href="https://csrc.nist.gov/csrc/media/Projects/pqc-dig-sig/documents/round-1/spec-files/hawk-spec-web.pdf">HAWK Specification Document</a></li>
<li><a href="https://en.wikipedia.org/wiki/Russell_Impagliazzo">Russell Impagliazzo - Wikipedia</a></li>

</ul>
</details>

**标签**: `#cryptography`, `#post-quantum`, `#AI`, `#security`, `#cryptanalysis`

---

<a id="item-18"></a>
## [Simon Willison 发布 llm-chat-completions-server 0.1a0](https://simonwillison.net/2026/Jul/30/llm-chat-completions-server/#atom-everything) ⭐️ 6.0/10

Simon Willison 发布了 llm-chat-completions-server 0.1a0，这是 LLM 命令行工具的一个插件，提供兼容 OpenAI 的聊天补全端点。它利用内容可寻址日志对扩展先前对话的请求进行去重。 该工具通过标准 API 简化了 LLM 模型的提供，减少多轮对话中的冗余计算和存储。它展示了内容可寻址日志在 LLM 工具中的实际优势，可能提高开发人员构建聊天应用的效率。 该服务器通过本地主机端点（例如端口 9001）暴露所有已安装 LLM 插件的模型。它完全由 GPT-5.6 Sol 编写，展示了该模型对 OpenAI 聊天补全 API 结构的熟练程度。该插件需要 LLM 0.32rc1 或更高版本，该版本引入了新的模式设计。

rss · Simon Willison · 7月30日 15:43

**背景**: 内容可寻址存储（CAS）是一种通过内容哈希来标识数据的方法，能够实现去重和高效检索。LLM 0.32rc1 引入了新模式，使用各个消息部分的哈希来对聊天补全请求进行去重，该服务器插件正是利用了这一点。这种方法对于多轮对话特别有用，因为每个请求都会扩展前一个请求，从而避免重复处理相同的消息段。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Content-addressable_storage">Content - addressable storage - Wikipedia</a></li>
<li><a href="https://simonwillison.net/2026/Jul/30/llm-rc1/">Release: llm 0 . 32 rc 1 | Simon Willison’s Weblog</a></li>

</ul>
</details>

**标签**: `#LLM`, `#OpenAI`, `#server`, `#content-addressable`, `#Simon Willison`

---