---
layout: default
title: "Horizon Summary: 2026-09-04 (ZH)"
date: 2026-09-04
lang: zh
---

> 从 56 条内容中筛选出 14 条重要资讯。

---

1. [OpenAI 发布 GPT-6 Astra，ARC-AGI-3 得分接近完美](#item-1) ⭐️ 10.0/10
2. [Verisign 提议终止所有三级 .name 域名](#item-2) ⭐️ 8.0/10
3. [人工河狸坝将银鲑存活率从 8%提升至 60%](#item-3) ⭐️ 8.0/10
4. [借助 LLM 将 1993 年 Amiga 游戏移植到 Godot](#item-4) ⭐️ 8.0/10
5. [研究揭示 Claude、Codex 和 Cursor 在 1.7 万次运行中的工具偏好](#item-5) ⭐️ 8.0/10
6. [围棋大师申真谞让两子击败 AI KataGo](#item-6) ⭐️ 8.0/10
7. [AI 代理正在将前端开发同质化，趋向 React](#item-7) ⭐️ 8.0/10
8. [探讨 OpenAI Astra 的循环架构](#item-8) ⭐️ 8.0/10
9. [OpenAI 启动 10 亿美元 Daybreak 计划，保护关键服务](#item-9) ⭐️ 8.0/10
10. [Paint.NET 开发者借助 AI 重写 Direct2D 以支持 WINE](#item-10) ⭐️ 8.0/10
11. [Claude 新系统提示词禁止复制歌词](#item-11) ⭐️ 7.0/10
12. [Claude Code v2.1.260 新增差异面板与缓存诊断](#item-12) ⭐️ 6.0/10
13. [Playco 借助 GPT-6 Astra 将游戏原型制作中的手动修复减少 50%](#item-13) ⭐️ 6.0/10
14. [llm-gemini 0.34 新增对 Gemini 3.8 Flash 的支持](#item-14) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [OpenAI 发布 GPT-6 Astra，ARC-AGI-3 得分接近完美](https://openai.com/index/gpt-6-astra/) ⭐️ 10.0/10

OpenAI 宣布了下一代 AI 模型 GPT-6 Astra，其在 ARC-AGI-3 基准测试中取得了 99.9%的得分，并在编程基准上取得了重大进展。该模型正在逐步推出，并提供了系统卡以说明安全细节。 GPT-6 Astra 代表了 AI 推理和编程能力的重大飞跃，可能加速软件开发和 AI 研究的进展。其在 ARC-AGI-3 上接近完美的得分表明向更通用智能迈进，这可能影响依赖复杂问题解决的行业。 ARC-AGI-3 得分 99.9%是在特定 harness（responses API）下取得的，与之前模型（如 GPT-5.6 Sol，未使用该 harness 时得分为 7.8%）的可比性存在争议。该模型在 Artificial Analysis Coding Agent Index（综合了 DeepSWE 和 Terminal-Bench 等基准）上也显示出重大进步。

hackernews · kibae · 9月3日 18:41 · [社区讨论](https://news.ycombinator.com/item?id=49554643)

**背景**: ARC-AGI-3 是一个交互式推理基准，旨在衡量 AI 代理的类人智能，要求它们探索新环境并即时获取目标。Artificial Analysis Coding Agent Index 是由 DeepSWE、Terminal-Bench v2.1 和 SWE-Atlas-QnA 等基准组成的综合得分，用于评估编码代理的性能。GPT-6 Astra 是 OpenAI GPT 系列中继 GPT-5 之后的最新版本，被视为一次重大版本发布。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arcprize.org/arc-agi/3">ARC-AGI-3</a></li>
<li><a href="https://artificialanalysis.ai/agents/coding-agents">AI Coding Agent Benchmarks & Leaderboard | Artificial Analysis</a></li>
<li><a href="https://openai.com/index/how-two-settings-tripled-our-arc-agi-3-scores/">How enabling two settings tripled our scores on the ARC-AGI-3 benchmark | OpenAI</a></li>

</ul>
</details>

**社区讨论**: 社区评论对 ARC-AGI-3 评分表表示怀疑，指出如果使用相同的 harness，GPT-5.6 Sol 的得分会高得多，因此比较具有误导性。一些人质疑基准改进是否表明真正的 AGI，呼应了 François Chollet 的批评，即前沿模型的进展往往类似于技能获取而非真正的智能。其他人则评论了自主购买演示的普遍性，质疑其相关性。

**标签**: `#AI`, `#OpenAI`, `#GPT-6`, `#ARC-AGI`, `#machine learning`

---

<a id="item-2"></a>
## [Verisign 提议终止所有三级 .name 域名](https://neil.fraser.name/news/2026/09/03/) ⭐️ 8.0/10

Verisign 已向 ICANN 提议终止所有三级 .name 域名（x.y.name），这将影响现有注册者，并可能释放相应的二级域名（y.name）。该提议引发了社区的广泛关注和讨论。 这一政策变更可能破坏现有域名注册的稳定性，并与 ICANN 确保互联网稳定安全运行的使命相悖。它引发了关于域名所有权、域名抢注风险以及互联网治理决策过程的关键问题。 该提议专门针对 .name 下的三级域名，如 x.y.name，不影响像 y.name 这样的二级域名。社区成员指出，Verisign 的提议包含误导性陈述，且未解决保留已释放二级域名以防止抢注的需求。

hackernews · pavel_lishin · 9月3日 14:54 · [社区讨论](https://news.ycombinator.com/item?id=49550772)

**背景**: .name 顶级域名最初是为了支持三级域名而设立，允许个人注册如 john.doe.name 这样的个人域名。然而，运营该注册局的 Verisign 现在提议终止这些三级注册，理由是声誉问题和低使用率。此举引发了对域名注册稳定性的担忧，以及二级域名释放后可能被滥用的风险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://neil.fraser.name/news/2026/09/03/">Neil Fraser: News: . name Termination</a></li>
<li><a href="https://en.wikipedia.org/wiki/Verisign">Verisign - Wikipedia</a></li>
<li><a href="https://www.verisign.com/">A global provider of domain name registry services and... | Verisign</a></li>

</ul>
</details>

**社区讨论**: 社区评论强烈反对该提议，用户如 nneonneo 建议 Verisign 应停止新注册但尊重现有注册，并保留二级域名以防止抢注。其他人如 jl6 认为该提议与 ICANN 的稳定和安全使命相悖。一些用户澄清只有三级域名受影响，二级域名不受影响，但仍批评该决定对注册者有害。

**标签**: `#domain names`, `#ICANN`, `#policy`, `#internet governance`, `#Verisign`

---

<a id="item-3"></a>
## [人工河狸坝将银鲑存活率从 8%提升至 60%](https://www.discoverwildlife.com/animal-facts/artificial-beaver-dams-california) ⭐️ 8.0/10

在加州北部，人工河狸坝的建设将幼年银鲑的越冬存活率从 8%大幅提升至 60%。这种修复技术模拟了河狸的自然活动，以重建失去的湿地栖息地。 这一显著改善为受威胁的鲑鱼种群提供了一种有前景且经济有效的保护工具，尤其是在河狸已灭绝的地区。它凸显了生态系统工程在恢复关键栖息地和支持生物多样性方面的潜力。 人工坝使用树枝等天然材料建造，抬高了水位，形成了更深的池塘，为幼鲑提供了庇护所。有趣的是，筑坝后水温反而下降，这可能是由于地下水交换增加，对银鲑等冷水物种有利。

hackernews · speckx · 9月3日 16:21 · [社区讨论](https://news.ycombinator.com/item?id=49552572)

**背景**: 河狸坝以通过创造湿地改变景观而闻名，这些湿地惠及包括鲑鱼在内的许多物种。历史上，河狸在北美广泛分布，但因皮毛被大量捕猎而减少，导致其筑坝效益的丧失。人工河狸坝是一种修复技术，用于在河狸缺失的地区模拟这些效益。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.discoverwildlife.com/animal-facts/artificial-beaver-dams-california">People started building artificial beaver dams in... | Discover Wildlife</a></li>
<li><a href="https://pbswisconsin.org/news-item/how-ecosystem-engineers-are-building-mock-beaver-dams-to-help-restore-more-wetlands-in-wisconsin/">How ecosystem engineers are building mock beaver dams to help...</a></li>

</ul>
</details>

**社区讨论**: 评论者分享了个人轶事和相关文献，如一篇关于池塘中银鲑幼鱼的博客文章，以及一本关于自耕农修复水坝的书《三对荒野》。一些人对水温下降这一反直觉的发现表示惊讶，而另一些人则质疑为什么不直接重新引入河狸，而是建造人工坝。

**标签**: `#ecology`, `#conservation`, `#salmon`, `#beaver dams`, `#environmental science`

---

<a id="item-4"></a>
## [借助 LLM 将 1993 年 Amiga 游戏移植到 Godot](https://babyloniantwins.com/blog/porting-a-1993-amiga-game-to-godot/) ⭐️ 8.0/10

一位开发者成功地将自己 1993 年用 MC68000 汇编编写的 Amiga 游戏，借助 LLM（Claude）阅读并翻译汇编代码，移植到了 Godot 引擎。初步移植仅用一个晚上完成，随后又花了几个周末完善手感并发布游戏。 这展示了一种新颖高效的复古游戏移植工作流，利用 LLM 弥合传统汇编代码与现代引擎之间的鸿沟。它可能激励其他开发者保护和复兴经典游戏，并凸显了 AI 在软件考古和逆向工程中日益重要的作用。 开发者在 Mac 上使用 vasm 汇编代码，目标是生成与原始二进制逐字节相同的文件。但存在 108 字节的差异，因为原始文件是 AsmOne 在游戏运行后保存的内存快照，而非干净的汇编输出。开发者还免费发布了原始游戏。

hackernews · rabahs · 9月3日 14:28 · [社区讨论](https://news.ycombinator.com/item?id=49550375)

**背景**: Amiga 是 20 世纪 80 年代末至 90 年代初流行的个人电脑，许多游戏为追求性能而使用 MC68000 汇编编写。Godot 是一款现代开源游戏引擎，支持 2D 和 3D 游戏开发。AsmOne 是 Amiga 开发中流行的汇编器和 IDE，它将代码汇编到内存中，并允许保存内存快照。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Godot_(game_engine)">Godot (game engine)</a></li>
<li><a href="https://en.wikipedia.org/wiki/Amiga_programming_languages">Amiga programming languages - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区成员对 1993 年的汇编编码表示惊叹，并分享了类似的 LLM 辅助移植经验。一位用户成功使用 Claude 将 ZX81 内存转储转换为 Go，另一位则一直在为多种系统构建可复用的主机移植框架。还有人希望 LLM 能导出此类移植的工程指南。

**标签**: `#LLM`, `#retrocomputing`, `#game development`, `#Godot`, `#assembly`

---

<a id="item-5"></a>
## [研究揭示 Claude、Codex 和 Cursor 在 1.7 万次运行中的工具偏好](https://armature.tech/blog/which-tools-coding-agents-install) ⭐️ 8.0/10

Armature 发布了一项实证研究，分析了 Claude、Codex 和 Cursor 在 17,000 次运行中安装和使用哪些工具，揭示了它们行为的明显模式。研究结果突出了这些 AI 编程代理在文件编辑、网络搜索等任务中选择不同工具的方式。 这项研究为开发者和为 AI 代理构建工具的公司提供了宝贵见解，因为了解代理的偏好可以为产品设计和营销策略提供参考。它还引发了关于 AI 代理行为演变以及 AI 生态系统中商业锁定可能性的讨论。 该研究测量了 17,000 次运行中的工具使用情况，显示 Claude Code 经常使用 awk、sed 和 Python 进行文件编辑，而其他代理可能偏好不同的方法。分析还指出，网络搜索并非总是自动触发，模型版本（例如 Opus 与较新模型）可能影响行为。

hackernews · screm · 9月3日 21:20 · [社区讨论](https://news.ycombinator.com/item?id=49557206)

**背景**: 像 Claude Code、OpenAI 的 Codex 和 Cursor 这样的 AI 编程代理是帮助开发者编写、编辑和调试代码的工具。这些代理通常依赖外部工具（如 shell 命令、文件编辑器、网络搜索）来完成任务，它们的选择可能因底层模型和配置而异。理解这些模式对于希望优化工作流程的开发者以及旨在将产品与 AI 代理集成的公司至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://code.claude.com/docs/en/best-practices">Best practices for Claude Code - Claude Code Docs</a></li>
<li><a href="https://openai.com/index/introducing-codex/">Introducing Codex | OpenAI</a></li>
<li><a href="https://cursor.com/">AI Coding Agent for Building Ambitious Software | Cursor</a></li>

</ul>
</details>

**社区讨论**: 社区评论反映了热情与担忧的混合情绪。一些用户认为这是 AI‘黄金时代’的证据，而另一些则担心未来以利润为导向的锁定。一位构建类似跟踪工具的用户分享了自己的开源项目，另一位用户指出 Claude Code 的文件编辑行为在 5 系列中发生了变化，引发了对模型特定差异的好奇。

**标签**: `#AI coding agents`, `#tool usage`, `#empirical study`, `#developer tools`, `#Claude Code`

---

<a id="item-6"></a>
## [围棋大师申真谞让两子击败 AI KataGo](https://www.kedglobal.com/artificial-intelligence/newsView/ked202607210007) ⭐️ 8.0/10

围棋大师申真谞在让两子的情况下击败了顶级围棋 AI 程序 KataGo，这是人类对抗领先 AI 的一次重大成就。这场比赛凸显了申真谞的战略创造力以及在让子条件下利用 AI 弱点的能力。 这一结果表明，即使是最强大的 AI，在让子条件下也可能被人类击败，为理解 AI 的局限性和人类战略思维的价值提供了见解。这也引发了关于复杂游戏中人类与 AI 力量平衡的持续讨论。 申真谞被广泛认为是有史以来最强的人类围棋选手，等级分超过 3850，远超最接近的对手。让两子是一个巨大的优势，估计相当于数百个 ELO 点，申真谞采用了特定策略，包括复杂的定式变化，以确保胜利。

hackernews · gmays · 9月3日 01:11 · [社区讨论](https://news.ycombinator.com/item?id=49544762)

**背景**: 围棋是一种古老的棋盘游戏，棋盘为 19x19，近年来像 KataGo 这样的 AI 程序已经超越了人类的能力。让子用于平衡不同实力选手之间的比赛，让两子对较弱方来说是一个巨大的优势。KataGo 是最强的开源围棋 AI 之一，但它可能不在超级计算机上运行，这可能影响其性能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Two-stone_handicap">Two-stone handicap</a></li>
<li><a href="https://en.wikipedia.org/wiki/Handicapping_in_Go">Handicapping in Go - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Professional_go_handicaps">Professional Go handicaps - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，申真谞的实力非凡，与对手的等级分差距在历史上无与伦比，并且他的下法非常接近 AI。一些人指出标题可能具有误导性，因为让子意味着申真谞被视为较弱方，但他们也承认没有这样的优势，人类无法获胜。其他人讨论了技术方面，例如 AI 的计算资源有限，以及它倾向于下高概率的棋而不是适应让子。

**标签**: `#AI`, `#Go`, `#KataGo`, `#human vs AI`, `#game theory`

---

<a id="item-7"></a>
## [AI 代理正在将前端开发同质化，趋向 React](https://nolanlawson.com/2026/08/23/the-asteroid-currently-hitting-frontend-web-development/) ⭐️ 8.0/10

Nolan Lawson 的文章指出，AI 编码代理因训练数据中 React 等流行框架的过度代表，正日益偏向这些框架，导致前端开发趋于同质化。文章敦促开发者适应这一新现实，即“代理体验”比“开发者体验”更重要。 这一转变可能对前端开发者的技术选择和职业发展产生重大影响，因为 AI 代理在编码工作流中越来越普遍。它凸显了软件开发中更广泛的同质化趋势，可能减少技术栈的多样性和创新。 文章引用了 Cursor 和 Viget 将代码库从 Solid 和 Lit 迁移到 React 的例子，说明主流框架的吸引力。文章还指出，AI 代理编写非主流技术可能需要更多令牌，使其效率较低。

hackernews · codechicago277 · 9月3日 19:17 · [社区讨论](https://news.ycombinator.com/item?id=49555233)

**背景**: AI 代理是自主执行编码任务的软件工具，通常使用在大量公共代码上训练的大型语言模型。由于训练数据以 React 等流行框架为主，这些代理倾向于生成这些框架的代码，从而强化其主导地位。这可能导致反馈循环，开发者为了优化 AI 辅助而选择流行框架，进一步使生态系统同质化。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.zdnet.com/article/ai-agents-make-great-teammates-but-dont-let-them-code-alone-heres-why/">AI agents make great teammates, but don't let them code... - ZDNET</a></li>
<li><a href="https://roadmap.sh/frontend">Frontend Developer Roadmap: What is Frontend Development ?</a></li>

</ul>
</details>

**社区讨论**: 评论者对同质化趋势表示不安，有人称这感觉像“赢家通吃”的局面。一些人视其为转向 AI 技能的信号，而另一些人则对代码库从轻量框架迁移到 React 表示遗憾。少数人对资深工程师构建护栏和新工具的机会持乐观态度。

**标签**: `#AI`, `#frontend`, `#web development`, `#React`, `#future of coding`

---

<a id="item-8"></a>
## [探讨 OpenAI Astra 的循环架构](https://www.lesswrong.com/posts/PLisnSFir8y5AHkmP/how-concerned-should-we-be-about-astra-s-recurrent) ⭐️ 8.0/10

LessWrong 上的一篇帖子和 Hacker News 上的讨论，探讨了 OpenAI 即将推出的 Astra 模型传闻中采用的“循环深度”或“循环变压器”架构的影响，权衡了潜在的好处与安全担忧。讨论引用了 Sebastian Raschka 的专家分析以及 The Information 和 Fortune 的报道。 这一架构转变可能显著影响 AI 模型的效率和推理能力，并可能影响未来 AI 发展的方向。然而，它引发了安全专家对先进 AI 系统可解释性和可控性的担忧，这对于确保安全部署至关重要。 据报道，该架构重用层堆栈以在不增加参数的情况下增加容量，如 Nanbeige4.2-3B 所示。与经典 RNN 不同，它没有在整个轨迹中累积的无界隐藏状态，但这种方法仍然引发可解释性问题。

hackernews · yurivish · 9月3日 17:10 · [社区讨论](https://news.ycombinator.com/item?id=49553321)

**背景**: 循环神经网络（RNN）通过隐藏状态逐步处理序列，而变压器则使用注意力机制处理整个序列。循环变压器或循环深度是一种混合方法，它迭代地重用层，可能提高效率。据传 OpenAI 的 Astra 模型采用了这种技术，引发了对其影响的讨论。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://sebastianraschka.com/blog/2026/openai-astra-looped-transformers.html">OpenAI Astra and Looped Transformers | Sebastian Raschka, PhD</a></li>
<li><a href="https://fortune.com/2026/09/03/reports-openais-astra-model-uses-a-new-more-efficient-ai-architecture-alarms-ai-safety-experts-who-worry-the-method-makes-models-harder-to-control/">Why are AI safety experts alarmed by reports OpenAI’s Astra model uses “recurrent depth”? | Fortune</a></li>
<li><a href="https://www.geeky-gadgets.com/openai-chatgpt-6-astra-model-rumors/">ChatGPT 6 Astra Model Rumors: Recurrent Depth Explained - Geeky Gadgets</a></li>

</ul>
</details>

**社区讨论**: 社区评论反应不一：一些人欢迎循环作为思维链的更自然替代方案，而另一些人则质疑其新颖性和安全性影响。一位评论者指出，思维链中的中间标记可能不代表逻辑路径，另一位则链接到关于安全警报的相关 Hacker News 讨论。

**标签**: `#AI`, `#architecture`, `#transformers`, `#OpenAI`, `#recurrent neural networks`

---

<a id="item-9"></a>
## [OpenAI 启动 10 亿美元 Daybreak 计划，保护关键服务](https://openai.com/index/daybreak-for-frontline-defenders) ⭐️ 8.0/10

OpenAI 宣布了“Daybreak for Frontline Defenders”计划，这是一项 10 亿美元的承诺，旨在扩大前沿网络 AI、培训和支持对关键服务的获取。该计划旨在帮助一线防御者保护电力、供水等关键基础设施。 该计划可能显著增强关键服务的网络安全态势，这些服务正日益受到复杂网络威胁的攻击。通过提供对前沿 AI 工具的补贴获取，OpenAI 正将自己定位为国家和全球关键基础设施保护的关键合作伙伴。 这项 10 亿美元的承诺包括对 Daybreak 网络模型的补贴获取、培训、技术支持和合作伙伴关系。该计划将支持美国和世界各地的一线防御者，利用 GPT-5.6 Sol 和 Codex Security 等模型进行威胁识别、补丁生成和修复验证。

rss · OpenAI News · 9月3日 13:15

**背景**: Daybreak 是 OpenAI 的网络安全计划，利用前沿模型部署 AI 进行网络防御，以识别威胁并生成补丁。新计划通过关注关键服务来扩展这一举措，这些服务往往资金不足且容易受到攻击。OpenAI 与 Palo Alto Networks 等实体的合作旨在将先进的网络模型应用于实际环境。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openai.com/index/daybreak-for-frontline-defenders/">Daybreak for Frontline Defenders : $1B to protect essential... | OpenAI</a></li>
<li><a href="https://thenewstack.io/openai-daybreak-frontline-defenders/">OpenAI spends $1 billion to expand Daybreak to defend power, water...</a></li>
<li><a href="https://openai.com/daybreak/">Daybreak | OpenAI for cybersecurity | OpenAI</a></li>

</ul>
</details>

**标签**: `#cybersecurity`, `#AI`, `#OpenAI`, `#public infrastructure`, `#investment`

---

<a id="item-10"></a>
## [Paint.NET 开发者借助 AI 重写 Direct2D 以支持 WINE](https://simonwillison.net/2026/Sep/2/rick-brewster/) ⭐️ 8.0/10

Paint.NET 开发者 Rick Brewster 宣布，该应用现在包含一个内部、从零开始、通过洁净室逆向工程重写的 Direct2D 实现，通过 /wine 标志触发，以启用实验性的 WINE/Linux 支持。这 18 万行代码主要由 AI 助手 Claude 生成，被描述为“氛围编程”，且未经彻底审查。 这一成就展示了 AI 辅助编程在解决复杂、长期存在的技术挑战（如 WINE 上的 Direct2D 兼容性）方面的潜力，而此前这被认为不可行。同时，它也引发了关于 AI 生成代码的可靠性和可维护性的重要问题，尤其是在未经过彻底审查的情况下。 该重写代码位于 PaintDotNet.Windows.Direct2D1.Managed.dll 中，仅在 WINE 上使用。Brewster 提到，他不得不“照看”Claude，以确保正确的 COM 引用计数（AddRef）并纠正糟糕的设计决策，但对其逆向工程 Direct2D 内置效果公式的能力印象深刻。Paint.NET 其余部分约有 70 万行代码，开发了 20 多年。

rss · Simon Willison · 9月2日 05:50

**背景**: Direct2D 是 Windows 的 2D 图形 API，而 WINE 是一个兼容层，允许 Windows 应用程序在 Linux 和其他类 Unix 系统上运行。洁净室逆向工程是一种法律上可辩护的方法，其中一个团队分析系统并记录规范，另一个团队在不直接接触原始代码的情况下重建它。“氛围编程”指的是接受 AI 生成的代码而不进行彻底审查，依赖迭代提示和测试。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.retroreversing.com/clean-room-reversing">Legality of Reverse Engineering & Clean Room Reversing - Retro...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Vibe_coding">Vibe coding - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Wine_(software)">Wine (software) - Wikipedia</a></li>

</ul>
</details>

**标签**: `#Direct2D`, `#WINE`, `#AI-assisted coding`, `#Paint.NET`, `#reverse engineering`

---

<a id="item-11"></a>
## [Claude 新系统提示词禁止复制歌词](https://simonwillison.net/2026/Sep/2/claudes-new-system-prompt/) ⭐️ 7.0/10

Anthropic 已重新整理并发布了 Claude 模型的系统提示词，其中包括一项显著更新，限制复制歌词。新提示词明确禁止全部或部分复制歌词、诗歌或书籍段落，并在初次拒绝后持续拒绝类似请求。 此次更新凸显了 Anthropic 在版权合规方面的主动态度，可能为其他 AI 公司树立先例。同时，它也强调了系统提示词透明度对研究人员和用户日益增长的重要性。 该限制适用于歌词、诗歌以及书籍和文章中的段落，包括最后一行、副歌、钩子或逐音符写出的旋律。1929 年前首次发表的作品不受限制，但 Claude 在不确定作品日期时会拒绝请求。

rss · Simon Willison · 9月2日 14:16

**背景**: 系统提示词是赋予 AI 模型的指令，用于塑造其行为。Anthropic 发布这些提示词以提高透明度，让用户和研究人员了解模型限制。最近重组为按模型分页并支持 Markdown 输出，便于比较和分析。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://simonwillison.net/2026/Sep/2/claudes-new-system-prompt/">Claude ’s new system prompt really doesn’t want to reproduce song ...</a></li>
<li><a href="https://github.com/asgeirtj/system_prompts_leaks">GitHub - asgeirtj/ system _ prompts _leaks: Extracted system prompts ...</a></li>
<li><a href="https://cache.directory/prompts/">system prompts — cache.directory</a></li>

</ul>
</details>

**标签**: `#AI`, `#Anthropic`, `#system prompts`, `#transparency`, `#Claude`

---

<a id="item-12"></a>
## [Claude Code v2.1.260 新增差异面板与缓存诊断](https://github.com/anthropics/claude-code/releases/tag/v2.1.260) ⭐️ 6.0/10

Claude Code v2.1.260 引入了 /diff 命令，在全屏模式下打开差异面板以显示未提交的更改，并在 /cost 和状态行中添加了提示缓存未命中的可能原因。它还针对无头会话添加了 /reload-plugins 和 /advisor 的文本形式，并修复了大量 bug。 此版本为使用 Claude Code 的开发者（尤其是在无头或自动化工作流中）提高了透明度和控制力。缓存未命中诊断有助于用户理解和降低 token 成本，解决了 AI 辅助编码中的一个常见痛点。 差异面板在 Claude 编辑时显示未提交的更改，可通过 /diff 切换。缓存未命中诊断现在会指出可能的原因，如工具定义更改或超过 TTL 空闲。无头会话新增了 /reload-plugins 和基于文本的 /advisor，并修复了权限规则解析、沙箱问题和模型切换错误。

rss · Claude Code Releases · 9月3日 23:48

**背景**: Claude Code 是一款 AI 驱动的编码助手，可在终端或 VS Code 扩展中运行。它使用提示缓存来降低成本，但缓存未命中会增加 token 使用量。无头会话（使用 -p 或 Agent SDK）允许编程控制，新命令将功能扩展到桌面和远程环境。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://code.claude.com/docs/en/vs-code">Use Claude Code in VS Code - Claude Code Docs</a></li>
<li><a href="https://www.devclass.com/ai-ml/2026/04/01/anthropic-admits-claude-code-users-hitting-usage-limits-way-faster-than-expected/5213575">Anthropic admits Claude Code users hitting usage limits 'way faster...</a></li>
<li><a href="https://danielkeller.com/tech/headless-agents/">From Terminal to Factory - Running Headless AI Agents... - Daniel Keller</a></li>

</ul>
</details>

**标签**: `#Claude Code`, `#release notes`, `#developer tools`, `#AI coding assistant`

---

<a id="item-13"></a>
## [Playco 借助 GPT-6 Astra 将游戏原型制作中的手动修复减少 50%](https://openai.com/index/playco-game-prototyping-with-astra) ⭐️ 6.0/10

Playco 使用 OpenAI 的 GPT-6 Astra 从单个灰盒基础构建了三个主题游戏原型，并报告称与之前的模型相比，手动修复减少了 50%。 这展示了 GPT-6 Astra 在简化游戏开发流程方面的潜力，可能为游戏工作室降低成本和缩短上市时间。同时，它也凸显了 AI 在创意和技术生产过程中日益重要的作用。 这些原型是基于灰盒基础构建的，灰盒是游戏关卡的未纹理化基础版本，用于测试游戏玩法。手动修复减少 50% 表明 GPT-6 Astra 在代码生成和错误修正能力上有所提升。

rss · OpenAI News · 9月3日 12:00

**背景**: 在游戏开发中，“灰盒”或“白盒”是早期阶段，使用简单形状构建关卡以测试机制和流程。GPT-6 Astra 是 OpenAI 最强大的模型，专为复杂推理、编码和其他端到端任务设计，支持高推理努力级别。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openai.com/index/playco-game-prototyping-with-astra/">Playco cut manual fixes 50% prototyping games with... | OpenAI</a></li>
<li><a href="https://openai.com/index/gpt-6-astra/">GPT - 6 Astra : A new generation of intelligence | OpenAI</a></li>
<li><a href="https://developers.openai.com/api/docs/models/gpt-6-astra">GPT - 6 Astra Model | OpenAI API</a></li>

</ul>
</details>

**标签**: `#AI`, `#game development`, `#GPT-6 Astra`, `#OpenAI`, `#prototyping`

---

<a id="item-14"></a>
## [llm-gemini 0.34 新增对 Gemini 3.8 Flash 的支持](https://simonwillison.net/2026/Sep/2/llm-gemini/) ⭐️ 6.0/10

llm-gemini 0.34 已发布，新增了对 Google 新推出的 Gemini 3.8 Flash 模型的支持，提供低、中、高三种思考级别，并修复了一个异步响应无法记录已解析模型版本的 bug。 此次发布使 LLM 工具生态与 Google 最新的 Flash 模型保持同步，该模型在软件工程和智能体任务中性能有所提升。llm-gemini 的用户现在可以直接在 LLM 命令行工具中利用 Gemini 3.8 Flash 的功能，包括其快速且成本低廉的生成能力。 新模型 gemini-3.8-flash 支持可配置的思考级别（低、中、高）。异步响应 bug 的修复由 Charlie Tonneslan 贡献。Gemini 3.8 Flash 拥有 100 万 token 的上下文窗口，定价为输入每百万 token 0.750 美元，输出每百万 token 3.75 美元。

rss · Simon Willison · 9月2日 16:39

**背景**: llm-gemini 是 Simon Willison 的 LLM 工具的一个插件，该工具为访问各种 AI 模型提供了命令行界面。Gemini Flash 模型旨在快速且成本效益高，适合 HTML 和 JavaScript 生成等任务。此次发布还展示了使用 Gemini 3.8 Flash 配合 llm-coding-agent 插件来增强 markdown-svg-renderer 工具，使其支持 HTML 渲染。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/simonw/llm-gemini">GitHub - simonw/ llm - gemini : LLM plugin to access Google's Gemini...</a></li>
<li><a href="https://ai.google.dev/gemini-api/docs/models/gemini-3.8-flash">Gemini 3 . 8 Flash | Gemini API | Google AI for Developers</a></li>
<li><a href="https://llm-stats.com/models/gemini-3.8-flash">Gemini 3 . 8 Flash API Pricing, Context Window & Benchmarks</a></li>

</ul>
</details>

**标签**: `#LLM`, `#Gemini`, `#release`, `#plugin`, `#AI`

---