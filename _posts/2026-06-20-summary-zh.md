---
layout: default
title: "Horizon Summary: 2026-06-20 (ZH)"
date: 2026-06-20
lang: zh
---

> 从 48 条内容中筛选出 14 条重要资讯。

---

1. [Project Valhalla 将值类型引入 JDK 28](#item-1) ⭐️ 9.0/10
2. [AlphaFold 联合创始人 John Jumper 离开 DeepMind 加入 Anthropic](#item-2) ⭐️ 9.0/10
3. [Dan Abramov：ATProto 中没有实例](#item-3) ⭐️ 8.0/10
4. [挪威禁止小学使用人工智能](#item-4) ⭐️ 8.0/10
5. [《毁灭战士》与《德军总部 3D》作曲家鲍比·普林斯去世](#item-5) ⭐️ 8.0/10
6. [EFF 呼吁免费开放 PACER 法院记录](#item-6) ⭐️ 8.0/10
7. [前 OpenAI 研究员打造低成本桌面机器人实验平台](#item-7) ⭐️ 8.0/10
8. [AI 助力儿童罕见遗传病诊断](#item-8) ⭐️ 8.0/10
9. [负载均衡系统令人惊讶的经济学](#item-9) ⭐️ 7.0/10
10. [MCP 作为认证网关：Sean Lynch 的洞见](#item-10) ⭐️ 7.0/10
11. [Datasette Apps：在 Datasette 中托管自定义 HTML 应用](#item-11) ⭐️ 7.0/10
12. [OpenAI 为 ChatGPT 企业版新增支出控制与分析功能](#item-12) ⭐️ 6.0/10
13. [OpenAI 用 GPT-5.5 Instant 提升 ChatGPT 健康回复质量](#item-13) ⭐️ 6.0/10
14. [Datasette ACL 0.6a0 扩展为通用资源共享系统](#item-14) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Project Valhalla 将值类型引入 JDK 28](https://www.jvm-weekly.com/p/project-valhalla-explained-how-a) ⭐️ 9.0/10

经过十年的开发，Project Valhalla 在 JDK 28 中为 JVM 引入了值类型，实现了紧凑的内存布局和性能提升。 这对 Java 来说是一个重要里程碑，因为值类型允许开发者在不牺牲抽象的情况下编写高性能代码，对系统编程和数据密集型应用产生重大影响。 值类型是不可变的，可以内联存储在数组和对象中，消除了对象头和指针间接引用，但堆扁平化仅限于表示不超过 64 位的对象。

hackernews · philonoist · 6月19日 06:35 · [社区讨论](https://news.ycombinator.com/item?id=48595511)

**背景**: Java 长期以来支持基本类型（int、double）和引用类型（对象）。值类型通过提供具有值语义的用户定义类型来弥合差距，结合了基本类型的性能和对象的灵活性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openjdk.org/projects/valhalla/">Project Valhalla - OpenJDK</a></li>
<li><a href="https://news.ycombinator.com/item?id=48595511">Project Valhalla, Explained: How a Decade of Work Arrives in JDK 28</a></li>

</ul>
</details>

**社区讨论**: HN 上的讨论非常热烈，一些评论者批评值类型的复杂性和局限性，而另一些人则为设计选择辩护并强调显著的性能优势。还有关于空安全性和堆扁平化权衡的辩论。

**标签**: `#Java`, `#JVM`, `#Project Valhalla`, `#value types`, `#performance`

---

<a id="item-2"></a>
## [AlphaFold 联合创始人 John Jumper 离开 DeepMind 加入 Anthropic](https://twitter.com/JohnJumperSci/status/2068001285173834106) ⭐️ 9.0/10

AlphaFold 项目负责人、2024 年诺贝尔化学奖共同获得者 John Jumper 宣布离开 Google DeepMind，加入 AI 安全公司 Anthropic。 这一高调的人才流动标志着 AI 研究人才可能从能力导向的实验室转向安全导向的组织，并引发了对 Google DeepMind 人才保留能力的质疑。 Jumper 的离职是 Google 一系列高层人才流失的最新案例，此前已有其他关键 AI 研究人员离开。Demis Hassabis 公开感谢 Jumper 九年的合作，称 AlphaFold '改变了世界'。

hackernews · artninja1988 · 6月19日 17:53 · [社区讨论](https://news.ycombinator.com/item?id=48601162)

**背景**: AlphaFold 是由 DeepMind 开发的 AI 系统，能从氨基酸序列预测蛋白质三维结构，在 CASP 竞赛中取得了突破性精度。John Jumper 领导了 AlphaFold 团队，并因此获得 2024 年诺贝尔化学奖。Anthropic 是一家专注于构建可靠、可解释 AI 系统的 AI 安全公司。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/AlphaFold">AlphaFold</a></li>
<li><a href="https://en.wikipedia.org/wiki/Anthropic">Anthropic - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区评论表达了惊讶，并猜测 Google 内部存在问题，有人表示 '内部肯定发生了些劲爆的事'，并关注 Demis Hassabis 是否也会离开。一条评论将此举比作 '超级马里奥离开任天堂去专注管道工工作'。

**标签**: `#AI`, `#talent movement`, `#Anthropic`, `#Google DeepMind`, `#AlphaFold`

---

<a id="item-3"></a>
## [Dan Abramov：ATProto 中没有实例](https://overreacted.io/there-are-no-instances-in-atproto/) ⭐️ 8.0/10

Dan Abramov 发表文章解释，ATProto（Bluesky 的协议）中不存在“实例”这一概念，并与 Mastodon 的 ActivityPub 进行对比，同时使用了 RSS 类比。 这一澄清解决了去中心化社交媒体领域的一个常见误解，帮助开发者和用户理解 ATProto 与 ActivityPub 在架构上的根本差异。 在 ATProto 中，个人数据服务器（PDS）、中继（Relay）和应用视图（AppView）是独立的服务，具有不同的扩展需求，这与 Mastodon 的单体实例不同。文章使用 RSS 类比，将博客比作 PDS，将 Google Reader 比作 AppView。

hackernews · danabramov · 6月19日 15:10 · [社区讨论](https://news.ycombinator.com/item?id=48599515)

**背景**: ATProto（认证传输协议）是由 Bluesky 开发的用于社交应用的去中心化协议。与使用服务器间联邦（实例）的 ActivityPub 不同，ATProto 将数据存储（PDS）、数据中继和应用逻辑（AppView）分离，使用户可以在不丢失数据的情况下切换服务。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://atproto.com/guides/overview">Protocol Overview - AT Protocol</a></li>
<li><a href="https://fediview.com/articles/activitypub-vs-atproto-understanding-protocols/">ActivityPub vs. ATProtocol: Understanding the Protocols ...</a></li>
<li><a href="https://fediversereport.com/a-conceptual-model-of-atproto-and-activitypub/">A conceptual model of ATProto and ActivityPub</a></li>

</ul>
</details>

**社区讨论**: 文章评论包括对 RSS 类比的批评，认为 RSS 并不依赖 Google Reader，且 ATProto 的中继运行成本高昂。也有人赞赏这一澄清，但指出文章未能说明 ATProto 如何解决实例所处理的如去联邦化等问题。

**标签**: `#ATProto`, `#Bluesky`, `#decentralization`, `#protocol design`, `#social media`

---

<a id="item-4"></a>
## [挪威禁止小学使用人工智能](https://www.reuters.com/technology/norway-imposes-near-ban-ai-elementary-school-2026-06-19/) ⭐️ 8.0/10

挪威政府宣布，13 岁以下小学生在校基本禁止使用人工智能，14 至 16 岁初中生可在教师监督下有限使用。 该政策为教育领域的人工智能监管树立了先例，优先考虑读写等基础技能而非 AI 辅助学习，可能影响其他国家的做法。 禁令适用于 1 至 7 年级（6-13 岁），8 至 10 年级（14-16 岁）可在教师监督下谨慎使用 AI 工具。政府担心 AI 会阻碍批判性思维和基本技能的发展。

hackernews · ilreb · 6月19日 16:03 · [社区讨论](https://news.ycombinator.com/item?id=48600093)

**背景**: 像 ChatGPT 这样的生成式 AI 工具引发了对学习影响的担忧，尤其是对需要发展读写和理解能力的幼儿。挪威的决定反映了关于是否应将 AI 融入课堂或限制以保留传统学习方法的日益激烈的辩论。

**社区讨论**: 评论者大多支持该禁令，将其比作在理解算术之前不给计算器。一些人指出 AI 对学生成绩有害，在教育中禁止它是明智的，尽管执行可能具有挑战性。

**标签**: `#AI policy`, `#education`, `#Norway`, `#generative AI`, `#children`

---

<a id="item-5"></a>
## [《毁灭战士》与《德军总部 3D》作曲家鲍比·普林斯去世](https://www.legacy.com/legacy/robert-bobby-prince-lll) ⭐️ 8.0/10

鲍比·普林斯，这位为《毁灭战士》、《德军总部 3D》和《毁灭公爵 3D》创作了标志性配乐的作曲家，已去世，其讣告在 Legacy.com 上得到确认。 普林斯的音乐定义了早期第一人称射击游戏的氛围，并影响了数代游戏作曲家和玩家，他的离世是游戏史上的重要时刻。 普林斯还为《毁灭战士》贡献了音效，他的作品常从潘特拉、杀手等重金属乐队汲取灵感，将其融入令人难忘的 MIDI 曲目中。

hackernews · pgrote · 6月19日 19:35 · [社区讨论](https://news.ycombinator.com/item?id=48602352)

**背景**: 鲍比·普林斯是 1990 年代早期共享软件时代的关键人物，为 id Software 和 3D Realms 的游戏创作音乐。他为《毁灭战士》配乐的作品，如“E1M1: At Doom's Gate”，已成为经典。这些音乐以 MIDI 文件形式分发，使粉丝可以在游戏外聆听。

**社区讨论**: 社区评论表达了深切的悲伤和感激，粉丝们分享个人回忆，讲述普林斯的音乐如何影响了他们对游戏和重金属的热爱。许多人强调他的作品在《毁灭战士》和《德军总部 3D》等游戏中的沉浸式力量。

**标签**: `#gaming`, `#music`, `#obituary`, `#retro gaming`, `#game development`

---

<a id="item-6"></a>
## [EFF 呼吁免费开放 PACER 法院记录](https://www.eff.org/deeplinks/2026/06/court-records-should-be-free) ⭐️ 8.0/10

电子前哨基金会（EFF）发表文章，主张 PACER 法院记录应免费开放，指出公众获取面临的经济障碍，并强调了 CourtListener 和 RECAP 等项目的作用。 这很重要，因为 PACER 费用可能阻碍公众对司法系统的监督，对资源有限的个人和小型组织影响尤为严重。 PACER 每页收费 0.10 美元，每份文件最高收费 3.00 美元，但频繁使用可能产生高额费用；RECAP 浏览器扩展会自动将购买的文件分享到 CourtListener 供免费访问。

hackernews · hn_acker · 6月19日 17:34 · [社区讨论](https://news.ycombinator.com/item?id=48600946)

**背景**: PACER（公共法院电子记录访问系统）是联邦法院系统的电子公共访问服务，由美国法院行政办公室管理。截至 2013 年，它存储了超过 5 亿份文件。CourtListener 和 RECAP 由 Free Law Project 运营，是通过用户贡献文件提供免费访问 PACER 内容的非营利项目。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/PACER_(law)">PACER (law) - Wikipedia</a></li>
<li><a href="https://pacer.uscourts.gov/">Public Access to Court Electronic Records | PACER : Federal Court ...</a></li>
<li><a href="https://free.law/recap">RECAP Suite — Turning PACER Around Since 2009 | Free Law Project</a></li>

</ul>
</details>

**社区讨论**: 评论者提出了不同观点：有人指出州法院费用可能更高（例如爱达荷州每页 10 美元），还有人强调了资助法院系统的公共政策难题。其他人则赞扬了 RECAP 的作用，并希望它最终能变得过时。

**标签**: `#public policy`, `#legal tech`, `#open access`, `#PACER`, `#civic tech`

---

<a id="item-7"></a>
## [前 OpenAI 研究员打造低成本桌面机器人实验平台](https://dfdxlabs.com/research/2026/robotics-setup/) ⭐️ 8.0/10

一位曾在 OpenAI（2017–2020）从事机器人操作研究的研究员，搭建了一套单人桌面操作实验平台，成本约为 OpenAI 团队系统价格的十分之一，并正在就关键设计取舍征求社区反馈。 该项目表明，有意义的机器人操作研究现在已可被个人开展，降低了入门门槛，有望加速创新。作者的经验和对设计取舍的透明讨论，为日益壮大的独立机器人研究者群体提供了宝贵指导。 作者对三个决策尚不确定：单臂 vs. 双臂（为节省成本/空间选择了单臂）、暂时不标定相机内外参、以及使用 RGB 还是 RGB-D 来训练 ACT 或 Diffusion Policy 等策略。他对自己不采用 ROS 2 或 LeRobot、而是自建软件栈的决定很有信心。

hackernews · mplappert · 6月18日 14:51 · [社区讨论](https://news.ycombinator.com/item?id=48586329)

**背景**: 机器人操作研究通常需要昂贵的硬件和团队协作。ACT（基于 Transformer 的动作分块）和 Diffusion Policy 是现代的模仿学习方法，能从演示数据中学习机器人策略。ROS 2 是广泛使用的开源机器人中间件，LeRobot 则是机器人学习库。自建软件栈可获得完全控制权，但牺牲了社区支持和复用性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://diffusion-policy.cs.columbia.edu/">Diffusion Policy: Visuomotor Policy Learning via Action Diffusion</a></li>
<li><a href="https://www.roboticscenter.ai/research/ros2-vs-custom-robot-software-stack">ROS 2 vs Custom Stack: Choosing Robot Software Infrastructure</a></li>
<li><a href="https://medium.com/@deepkarkada/action-chunking-with-transformers-act-robot-policy-80519fc024bc">Action chunking with Transformers ( ACT ) robot policy | Medium</a></li>

</ul>
</details>

**社区讨论**: 评论者建议使用 VR 控制器（如 Quest 3s）替代 SpaceMouse 进行遥操作，并推荐尽早标定相机以利于策略学习。一位用户分享了使用廉价机械臂（HIWONDER）的经验，指出其精度很差。另一位用户提出合作意向，并询问不使用 LeRobot 的原因。

**标签**: `#robotics`, `#research setup`, `#manipulation`, `#hardware`, `#teleoperation`

---

<a id="item-8"></a>
## [AI 助力儿童罕见遗传病诊断](https://openai.com/index/diagnose-rare-childhood-diseases) ⭐️ 8.0/10

研究人员使用 OpenAI 的 o3 推理模型重新审视未解决的罕见儿科疾病病例，识别出 18 个多年来专家未能诊断的新病例。 这展示了 AI 缩短罕见病诊断历程的潜力，为多年来寻求答案的家庭带来希望。 该研究发表在《NEJM AI》上，由波士顿儿童医院和哈佛大学合作完成，使用了 OpenAI 的 o3 Deep Research 模型。

rss · OpenAI News · 6月18日 08:00

**背景**: 罕见遗传病通常需要五到七年才能确诊，因为存在大量基因变异和零散的医疗记录。AI 推理模型可以筛选数百万个变异和临床数据，找到人类专家可能遗漏的线索。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openai.com/index/diagnose-rare-childhood-diseases/">Using AI to help physicians diagnose rare genetic diseases ... | OpenAI</a></li>
<li><a href="https://en.wikipedia.org/wiki/OpenAI_o3">OpenAI o3 - Wikipedia</a></li>
<li><a href="https://www.techtimes.com/articles/318662/20260618/ai-rare-disease-diagnoses-openai-o3-solves-18-cases-specialists-could-not.htm">AI Rare Disease Diagnoses : OpenAI o3 Solves 18 Cases Specialists...</a></li>

</ul>
</details>

**标签**: `#AI`, `#healthcare`, `#rare diseases`, `#diagnosis`, `#OpenAI`

---

<a id="item-9"></a>
## [负载均衡系统令人惊讶的经济学](https://brooker.co.za/blog/2020/08/06/erlang.html) ⭐️ 7.0/10

Marc Brooker 的一篇文章利用排队论表明，即使负载分布中很小的不平衡也会导致显著的性能下降，挑战了负载均衡近乎完美的假设。 这一见解对于设计高效的分布式系统至关重要，因为它揭示了可能需要过度配置或仔细调优，以避免负载不平衡带来的隐藏成本。 该分析使用具有泊松到达和指数服务时间的 M/M/1 队列模型，表明在 10 台服务器和 10% 的不平衡情况下，延迟可能比完美平衡的系统差 25% 以上。

hackernews · KraftyOne · 6月19日 20:30 · [社区讨论](https://news.ycombinator.com/item?id=48602918)

**背景**: 排队论是对等待队列的数学研究，用于预测队列长度和等待时间。负载均衡将传入请求分配到多个服务器，以避免任何单个服务器过载。文章假设独立的泊松到达，这在具有相关突发的现实场景中可能不成立。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Queueing_theory">Queueing theory - Wikipedia</a></li>
<li><a href="https://www.qminder.com/blog/queue-management/queuing-theory-guide/">The Beginner’s Guide to Queuing theory | Qminder</a></li>

</ul>
</details>

**社区讨论**: 评论者指出泊松模型是一种简化；实际流量通常因超时、重试或惊群效应而产生相关突发，这可能加剧不平衡问题。还有人指出，文章忽略了服务前队列的讨论以及处理时间方差的影响。

**标签**: `#load balancing`, `#queueing theory`, `#distributed systems`, `#performance`

---

<a id="item-10"></a>
## [MCP 作为认证网关：Sean Lynch 的洞见](https://simonwillison.net/2026/Jun/19/sean-lynch/#atom-everything) ⭐️ 7.0/10

Sean Lynch 在 Hacker News 的评论中提出，模型上下文协议（MCP）最有价值的用途可能是作为 API 的认证网关，将认证流程隔离在智能体的上下文窗口之外。 这一观点将 MCP 的角色从通用的工具集成协议重新定义为 AI 智能体的关键安全层，可能简化智能体跨不同 API 处理认证的方式。 Lynch 指出，即使 MCP 仅作为认证网关，它仍然是一个胜利，强调了认证隔离是当前智能体架构中的核心痛点。

rss · Simon Willison · 6月19日 22:45

**背景**: 模型上下文协议（MCP）是 Anthropic 于 2024 年 11 月推出的开放标准，旨在规范 AI 系统连接外部工具和数据源的方式。目前，AI 智能体常常难以在其有限的上下文窗口内管理认证流程，导致安全性和复杂性问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Model_Context_Protocol">Model Context Protocol - Wikipedia</a></li>
<li><a href="https://modelcontextprotocol.io/">What is the Model Context Protocol ( MCP )? - Model Context Protocol</a></li>
<li><a href="https://agentgateway.dev/">agentgateway | Agent Connectivity Solved</a></li>

</ul>
</details>

**社区讨论**: Hacker News 上的讨论（该引文来源）可能对认证隔离的好处表示赞同，同时一些人争论 MCP 更广泛的集成能力是否同样重要。

**标签**: `#model-context-protocol`, `#llms`, `#ai`, `#authentication`, `#generative-ai`

---

<a id="item-11"></a>
## [Datasette Apps：在 Datasette 中托管自定义 HTML 应用](https://simonwillison.net/2026/Jun/18/datasette-apps/#atom-everything) ⭐️ 7.0/10

Simon Willison 发布了 datasette-apps 插件，允许用户在 Datasette 内部托管沙盒化的 HTML+JavaScript 应用，这些应用可以执行只读和配置好的写入 SQL 查询。 该插件将 Datasette 转变为一个完整的应用平台，无需单独托管即可创建自定义交互工具，并扩展了数据探索和可视化的生态系统。 应用在沙盒化的 iframe 中运行，带有 `allow-scripts allow-forms` 和阻止出站 HTTP 请求的 CSP 头，防止数据泄露。写入查询需要预先配置的存储查询。

rss · Simon Willison · 6月18日 23:58

**背景**: Datasette 是一个用于探索和发布数据的开源工具，提供 JSON API 用于自定义前端。以前，开发者需要单独托管他们的 HTML 应用；这个插件将它们直接集成到 Datasette 的界面中。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://datasette.io/blog/2026/datasette-apps/">Host applications inside Datasette with Datasette Apps</a></li>
<li><a href="https://simonwillison.net/2026/Jun/18/datasette-apps/">Datasette Apps: Host custom HTML applications inside Datasette</a></li>

</ul>
</details>

**标签**: `#datasette`, `#plugin`, `#sql`, `#web-development`, `#open-source`

---

<a id="item-12"></a>
## [OpenAI 为 ChatGPT 企业版新增支出控制与分析功能](https://openai.com/index/chatgpt-enterprise-spend-controls) ⭐️ 6.0/10

OpenAI 为 ChatGPT 企业版推出了新的支出控制和使用分析功能，允许组织对 AI 使用设置硬性限制，并按用户、群组、时间段和模型跟踪消耗情况。 此次更新使企业能够从开放的 AI 实验转向可衡量的支出管理，帮助它们自信地扩展 AI 应用，避免意外成本。 管理员现在可以为每个用户或群组设置预算和硬性限制，并查看整个工作区的采用率和参与度详细分析。

rss · OpenAI News · 6月18日 17:00

**背景**: ChatGPT 企业版是 OpenAI 面向企业的产品，包含企业级安全、集中管理和更高的使用限制。此前，组织缺乏对 AI 支出的细粒度可见性，难以随着使用增长控制成本。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cio.com/article/4187252/openai-adds-spend-controls-and-usage-analytics-to-chatgpt-enterprise.html">OpenAI adds spend controls and usage analytics to ChatGPT ...</a></li>
<li><a href="https://help.openai.com/en/articles/10875114-user-analytics-for-chatgpt-enterprise-and-edu">Workspace analytics for ChatGPT Enterprise and Edu</a></li>

</ul>
</details>

**标签**: `#OpenAI`, `#ChatGPT Enterprise`, `#cost management`, `#analytics`

---

<a id="item-13"></a>
## [OpenAI 用 GPT-5.5 Instant 提升 ChatGPT 健康回复质量](https://openai.com/index/improving-health-intelligence-in-chatgpt) ⭐️ 6.0/10

OpenAI 宣布 GPT-5.5 Instant 通过更强的推理、更好的上下文、更清晰的沟通以及医生参与的评估，改进了 ChatGPT 的健康与 wellness 回复。 此次更新增强了 AI 生成健康建议的可靠性和安全性，可能提高用户对 ChatGPT 处理健康相关查询的信任度和采用率。 这些改进基于医生参与的评估，即医疗专业人员帮助评估和优化模型输出。GPT-5.5 Instant 是 GPT-5.5 模型系列的一个变体，该系列还包括 Pro 等其他模式。

rss · OpenAI News · 6月18日 11:00

**背景**: GPT-5.5 是 OpenAI 推出的大型语言模型，接替 GPT-5.4。它有不同的模式，其中 GPT-5.5 Instant 是更快、更高效的变体。OpenAI 一直在逐步提升 ChatGPT 在各领域的能力，而健康是一个准确性和安全性至关重要的关键领域。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://help.openai.com/en/articles/11909943-gpt-55-in-chatgpt">GPT - 5 . 5 in ChatGPT | OpenAI Help Center</a></li>

</ul>
</details>

**标签**: `#AI`, `#healthcare`, `#ChatGPT`, `#OpenAI`

---

<a id="item-14"></a>
## [Datasette ACL 0.6a0 扩展为通用资源共享系统](https://simonwillison.net/2026/Jun/18/datasette-acl/#atom-everything) ⭐️ 6.0/10

Datasette ACL 0.6a0 于 2026 年 6 月 13 日发布，从仅限表的权限扩展为面向多用户 Datasette 实例的通用资源共享系统。 此更新对于需要在各种资源上进行细粒度访问控制的 Datasette 用户来说意义重大，它实现了更安全的多用户部署。 该插件正在积极开发中，目前需要 Datasette 1.0a15 或更高版本；权限保存在内部数据库中。

rss · Simon Willison · 6月18日 19:03

**背景**: Datasette 是一个用于探索和发布数据的开源工具。datasette-acl 插件提供高级权限管理，最初仅限于表级访问控制。此版本向更通用的资源共享模型迈进，允许管理员为表以外的各种资源定义权限。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/datasette/datasette-acl">GitHub - datasette/datasette-acl: Advanced permission ...</a></li>
<li><a href="https://pypi.org/project/datasette-acl/">datasette-acl · PyPI</a></li>
<li><a href="https://simonwillison.net/2026/Jun/18/datasette-acl/">Release: datasette-acl 0.6a0 - simonwillison.net</a></li>

</ul>
</details>

**标签**: `#datasette`, `#permissions`, `#open-source`, `#plugin`

---