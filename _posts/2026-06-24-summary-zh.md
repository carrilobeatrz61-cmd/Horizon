---
layout: default
title: "Horizon Summary: 2026-06-24 (ZH)"
date: 2026-06-24
lang: zh
---

> 从 66 条内容中筛选出 13 条重要资讯。

---

1. [Rhombus 语言 1.0 发布，基于 Racket](#item-1) ⭐️ 9.0/10
2. [漏洞报告因 LLM 垃圾信息而贬值](#item-2) ⭐️ 8.0/10
3. [TikZ 编辑器：LaTeX 图形的所见即所得工具](#item-3) ⭐️ 8.0/10
4. [AI 编码工具可能导致代码库难以维护](#item-4) ⭐️ 8.0/10
5. [谷歌因非官方 Workspace CLI 工具解雇员工](#item-5) ⭐️ 8.0/10
6. [GPT-5 助力解决三年免疫学谜题](#item-6) ⭐️ 8.0/10
7. [OpenAI 发布 Daybreak 安全工具](#item-7) ⭐️ 8.0/10
8. [LLM 在提示注入中优先考虑风格而非角色标签](#item-8) ⭐️ 8.0/10
9. [将 Moebius 0.2B 图像修复模型移植到浏览器中运行](#item-9) ⭐️ 8.0/10
10. [FUTO Swipe：开源滑行输入模型发布](#item-10) ⭐️ 7.0/10
11. [Swift Package Index 被苹果收购](#item-11) ⭐️ 7.0/10
12. [Meta 因数据泄露暂停员工监控项目](#item-12) ⭐️ 7.0/10
13. [Datasette 1.0a35 新增带 JSON API 的创建/修改表功能](#item-13) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Rhombus 语言 1.0 发布，基于 Racket](https://blog.racket-lang.org/2026/06/rhombus-v1.0.html) ⭐️ 9.0/10

Rhombus 语言 1.0 正式发布，这是一种基于 Racket 的新编程语言，具有新颖的宏系统和 `...` 运算符。 此次发布是 Racket 生态系统的一个重要里程碑，它提供了传统语法和强大的宏扩展能力，可能吸引偏好非 Lisp 语法的开发者。 `...` 运算符并非内置功能，而是一个宏，可以处理嵌套数据结构并替代 map 操作。Rhombus 使用 "shrubbery" 语法层提供传统语法，同时保留 Racket 的宏能力。

hackernews · Decabytes · 6月22日 17:50 · [社区讨论](https://news.ycombinator.com/item?id=48633473)

**背景**: Racket 是一种 Lisp 方言，以其强大的宏系统和面向语言编程而闻名。Rhombus 旨在将 Racket 的宏扩展性与主流语言（如 Python 或 JavaScript）用户熟悉的语法相结合。该项目已开发数年，之前在 Hacker News 上有过讨论。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://deepwiki.com/racket/rhombus/2.1-syntax-objects-and-macros">Syntax Objects and Macros | racket/rhombus | DeepWiki</a></li>
<li><a href="https://docs.racket-lang.org/rhombus/index.html">Rhombus - Racket</a></li>
<li><a href="https://docs.racket-lang.org/rhombus-meta-tutorial/">Rhombus Metaprogramming Tutorial - docs.racket-lang.org</a></li>

</ul>
</details>

**社区讨论**: 社区成员称赞 `...` 运算符的通用性和基于宏的实现。一些人表示更偏好 s-表达式，但也承认传统语法的价值。还有人希望看到 Rhombus 在会议上展示。

**标签**: `#Racket`, `#Rhombus`, `#programming languages`, `#macros`, `#syntax`

---

<a id="item-2"></a>
## [漏洞报告因 LLM 垃圾信息而贬值](https://words.filippo.io/vuln-reports/) ⭐️ 8.0/10

作者认为，由于大量低质量、通常由 LLM 生成的报告涌入，漏洞报告已经贬值，改变了研究人员与项目维护者之间的动态。 这一趋势破坏了漏洞披露流程的信任和效率，可能导致真正的安全问题在噪音中被忽视。 作者指出，许多报告是由 LLM 生成的，发现诸如不良 CSS 之类的琐碎问题，有些甚至可能是敲诈企图。这迫使维护者花费时间过滤垃圾信息，而不是修复真正的漏洞。

hackernews · goranmoomin · 6月23日 23:42 · [社区讨论](https://news.ycombinator.com/item?id=48653216)

**背景**: 漏洞披露是安全研究人员向组织报告缺陷的正式流程。传统上，这类报告因有助于提升安全性而受到重视。然而，LLM 的兴起使得大量低质量报告得以批量生产，削弱了其重要性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/html/2511.04538v1">From Model to Breach: Towards Actionable LLM-Generated Vulnerabilities ...</a></li>
<li><a href="https://sprinto.com/blog/vulnerability-disclosure/">What is Vulnerability Disclosure ? (Types, Process , Guidelines)</a></li>

</ul>
</details>

**社区讨论**: 评论者观点不一：有人同情被垃圾信息淹没的维护者，也有人认为漏洞报告主要惠及项目而非研究人员。一些人认为这种情况是暂时的，因为 LLM 最终将帮助修复和预防漏洞。

**标签**: `#security`, `#vulnerability disclosure`, `#LLM`, `#open source`, `#spam`

---

<a id="item-3"></a>
## [TikZ 编辑器：LaTeX 图形的所见即所得工具](https://tikz.dev/editor/) ⭐️ 8.0/10

一个开源的 TikZ 所见即所得编辑器已发布，允许用户通过拖拽和调整元素大小来可视化编辑 TikZ 源代码，同时保持源代码和渲染图形同步。 该工具解决了学者和 LaTeX 用户手动调整坐标并重新编译的主要痛点，可能大幅节省时间并减少图形创建中的错误。 该编辑器解析 TikZ 代码以跟踪对象的精确源代码位置，允许覆盖坐标而不改变其他代码结构。它几乎完全使用 Codex 构建，估计消耗了 7 亿个 token。

hackernews · DominikPeters · 6月23日 14:24 · [社区讨论](https://news.ycombinator.com/item?id=48645437)

**背景**: TikZ 是一个强大的 LaTeX 包，用于通过声明式命令创建矢量图形，但需要手动指定坐标并频繁重新编译以达到所需布局。所见即所得编辑器允许直接的可视化操作，这在 HTML 中很常见，但在 LaTeX 图形工具中很少见。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.overleaf.com/learn/latex/TikZ_package">TikZ package - Overleaf, Online LaTeX Editor</a></li>
<li><a href="https://en.wikipedia.org/wiki/WYSIWYG_editor">WYSIWYG editor</a></li>

</ul>
</details>

**社区讨论**: 社区称赞了其概念和用户界面，但一些人批评生成的代码不必要地使用了绝对坐标。开发者透露该项目通过 Codex 消耗了 7 亿个 token，ChatGPT 订阅费用约 500 美元，引发了关于 AI 辅助开发成本的讨论。

**标签**: `#LaTeX`, `#TikZ`, `#editor`, `#academic`, `#open-source`

---

<a id="item-4"></a>
## [AI 编码工具可能导致代码库难以维护](https://lucumr.pocoo.org/2026/6/23/the-coming-loop/) ⭐️ 8.0/10

Flask 框架的创建者 Armin Ronacher 发表博文警告，AI 辅助编码可能导致代码库难以维护，并削弱人类对软件的理解。他主张采用规范驱动开发作为解决方案。 随着 AI 编码工具的普及，这篇文章指出了关键风险：开发者专业知识的流失和代码质量的下降。它促使行业在生产力提升与长期可维护性之间寻求平衡。 Ronacher 警告说，代码库可能默认需要机器参与维护，而开发者越来越多地合并自己无法完全解释的代码。他建议在使用 AI 生成代码之前先编写详细的规范。

hackernews · ingve · 6月23日 11:06 · [社区讨论](https://news.ycombinator.com/item?id=48643180)

**背景**: 规范驱动开发是一种方法论，在编码之前将正式规范作为权威依据。Armin Ronacher 是知名的开源开发者，以创建 Flask 和 Jinja 而闻名。他的博文反映了业界对 AI 影响软件工程实践的日益担忧。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Specification-driven_development">Specification-driven development</a></li>
<li><a href="https://en.wikipedia.org/wiki/Armin_Ronacher">Armin Ronacher - Wikipedia</a></li>
<li><a href="https://martinfowler.com/articles/exploring-gen-ai/sdd-3-tools.html">Understanding Spec-Driven-Development: Kiro, spec-kit, and Tessl</a></li>

</ul>
</details>

**社区讨论**: 评论者大多认同 Ronacher 的担忧，指出清晰度和规范是有效使用 AI 的前提。一些人认为 LLM 擅长完成任务但缺乏审美判断，而瓶颈往往在于编写良好的规范。

**标签**: `#AI`, `#software engineering`, `#code quality`, `#LLM`, `#developer productivity`

---

<a id="item-5"></a>
## [谷歌因非官方 Workspace CLI 工具解雇员工](https://twitter.com/JPoehnelt/status/2069482265953087602) ⭐️ 8.0/10

谷歌解雇了 Justin Poehnelt，他因未经公司批准在 GitHub 上发布非官方的 Google Workspace CLI 工具而被解雇。该工具为 Google Workspace API 提供了统一的命令行界面，并在 GitHub 上迅速走红。 这一事件凸显了员工创新与企业官僚主义之间的紧张关系，引发了对大型科技公司开源贡献政策的质疑。同时，它也为那些创建与雇主产品相关的非官方工具的开发者敲响了警钟。 该工具使用了谷歌自己的 API，并被一些人误认为是谷歌的官方发布。Poehnelt 之前在 Chrome 团队任职期间（2015-2021 年）曾向谷歌管理的 GitHub 组织下的开源项目贡献过代码。

hackernews · justinwp · 6月23日 18:13 · [社区讨论](https://news.ycombinator.com/item?id=48649011)

**背景**: 谷歌有正式的开源政策，要求员工在发布可能与公司关联的项目前获得批准。Google Workspace CLI 是 2026 年发布的一款官方工具，但 Poehnelt 的非官方版本早于它且未经授权。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/googleworkspace/cli">GitHub - googleworkspace/cli: Google Workspace CLI — one command-line tool for Drive, Gmail, Calendar, Sheets, Docs, Chat, Admin, and more. Dynamically built from Google Discovery Service. Includes AI agent skills.</a></li>
<li><a href="https://www.infoq.com/news/2026/06/google-workspace-cli/">Google Workspace CLI: Unified Command-Line Tool Built for Humans and AI Agents - InfoQ</a></li>

</ul>
</details>

**社区讨论**: 评论意见分歧：一些人批评 Poehnelt 判断力差，发布了可能被误认为是官方产品的工具；另一些人则同情他，引用 Pournelle 的官僚铁律，并指出谷歌曾鼓励 20%时间用于副业项目。几位看似现任或前任谷歌员工的评论者对他的行为持批评态度。

**标签**: `#Google`, `#employment`, `#open source`, `#corporate policy`, `#CLI`

---

<a id="item-6"></a>
## [GPT-5 助力解决三年免疫学谜题](https://openai.com/index/gpt-5-immunology-mystery) ⭐️ 8.0/10

OpenAI 的 GPT-5 Pro 模型帮助免疫学家 Derya Unutmaz 解决了一个关于 T 细胞行为的三年未解之谜，为 T 细胞在免疫反应中的功能提供了新见解。 这一突破展示了大型语言模型加速科学发现的潜力，尤其是在免疫学领域，对开发癌症和自身免疫疾病的治疗方法具有重要意义。 GPT-5 Pro 于 2025 年 8 月 7 日发布，是一款具有扩展推理能力的多模态大型语言模型，使其能够分析复杂的免疫学数据，并提出研究人员三年来未能找到的解决方案。

rss · OpenAI News · 6月23日 17:00

**背景**: T 细胞是一种对适应性免疫至关重要的白细胞。它们通过 T 细胞受体（TCR）和 MHC 复合体识别并响应抗原。理解 T 细胞行为是开发癌症和自身免疫疾病疗法的关键，但许多方面仍不清楚。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GPT-5_Pro">GPT-5 Pro</a></li>
<li><a href="https://openai.com/index/introducing-gpt-5/">Introducing GPT - 5 | OpenAI</a></li>

</ul>
</details>

**标签**: `#GPT-5`, `#immunology`, `#AI in science`, `#cancer research`, `#autoimmune disease`

---

<a id="item-7"></a>
## [OpenAI 发布 Daybreak 安全工具](https://openai.com/index/daybreak-securing-the-world) ⭐️ 8.0/10

OpenAI 宣布了 Daybreak 计划，推出了 Codex Security、GPT-5.5-Cyber 和 Patch the Planet，旨在大规模自动化漏洞检测、验证和修复。 这些工具代表了向 AI 驱动网络安全迈出的重要一步，可能减少保护软件所需的时间和专业知识，从而帮助全球组织抵御网络威胁。 Codex Security 是一个 AI 驱动的应用安全代理，可逐次提交扫描 GitHub 仓库；GPT-5.5-Cyber 是一个专为高级防御性网络工作流设计的模型，目前向关键基础设施防御者提供有限预览。

rss · OpenAI News · 6月22日 10:00

**背景**: 漏洞管理传统上需要安全专家手动查找和修复代码缺陷。OpenAI 的 Daybreak 工具利用大型语言模型自动化这些任务，基于早期如 GPT-4 等模型在代码分析方面的潜力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openai.com/index/gpt-5-5-with-trusted-access-for-cyber/">Scaling Trusted Access for Cyber with GPT-5.5 and GPT-5.5-Cyber | OpenAI</a></li>
<li><a href="https://www.testingcatalog.com/openai-launches-new-security-tools-and-updates-gpt-5-5-cyber/">OpenAI launches new security tools and updates GPT-5.5-Cyber</a></li>

</ul>
</details>

**标签**: `#AI Security`, `#Vulnerability Management`, `#OpenAI`, `#Cybersecurity`, `#Automated Patching`

---

<a id="item-8"></a>
## [LLM 在提示注入中优先考虑风格而非角色标签](https://simonwillison.net/2026/Jun/22/prompt-injection-as-role-confusion/#atom-everything) ⭐️ 8.0/10

Charles Ye、Jasmine Cui 和 Dylan Hadfield-Menell 的研究证实，LLM 无法可靠地区分特权文本（如<system>标签）和不可信的用户输入，因为它们更注重文本的风格而非明确的角色标签。这导致了有效的越狱攻击，例如附加模仿模型内部思考风格的文本以绕过安全策略。 这一发现对 AI 安全意义重大，因为它揭示了当前 LLM 架构的一个根本性局限：基于角色的防御是不够的。研究指出，如果没有真正的角色感知，提示注入防御将永远是一场打地鼠游戏，对已部署的 AI 系统构成持续风险。 研究人员发现，“去风格化”——以略微不同的方式重写文本，使其看起来不像角色标签中的预期格式——将攻击成功率从 61%降至 10%。他们将底层机制称为“角色混淆”，并认为这解释了为什么模型会被模仿内部思考块写作风格的文本所迷惑。

rss · Simon Willison · 6月22日 23:59

**背景**: 提示注入是一种网络安全利用手段，通过恶意输入导致 LLM 产生意外行为，通常绕过安全护栏。LLM 被训练为遵循指令，但本质上无法区分开发者定义的提示和用户输入。像<system>和<user>这样的角色标签用于划分特权指令，但这项研究表明，模型更依赖风格线索而非这些显式标记。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://role-confusion.github.io/">Prompt Injection as Role Confusion</a></li>
<li><a href="https://en.wikipedia.org/wiki/Prompt_injection">Prompt injection</a></li>
<li><a href="https://www.ibm.com/think/topics/prompt-injection">What Is a Prompt Injection Attack? | IBM</a></li>

</ul>
</details>

**社区讨论**: 鉴于作者的声誉，Hacker News 上的讨论可能很有深度，可能强调了这一发现对 AI 安全的实际影响，以及需要超越基于角色的防御机制。一些评论者可能会讨论在 LLM 中实现真正角色感知的可行性。

**标签**: `#prompt injection`, `#AI safety`, `#LLM security`, `#jailbreak`, `#role confusion`

---

<a id="item-9"></a>
## [将 Moebius 0.2B 图像修复模型移植到浏览器中运行](https://simonwillison.net/2026/Jun/22/porting-moebius/#atom-everything) ⭐️ 8.0/10

Simon Willison 成功将 Moebius 0.2B 图像修复模型移植到浏览器中，利用 WebGPU 实现 GPU 加速的修复功能，无需本地 CUDA 或 PyTorch。在线演示可在 simonw.github.io/moebius-web/上体验。 这一移植使得任何拥有现代浏览器的用户都能使用高质量的图像修复模型，无需昂贵的 GPU 硬件即可进行 AI 图像编辑，从而推动了 AI 图像编辑的普及。同时，它也展示了 WebGPU 在客户端运行复杂深度学习模型方面日益增强的能力。 该移植使用了 ONNX Runtime Web 及其 WebGPU 后端，将原始的 PyTorch 模型转换为 ONNX 格式。该模型仅有 0.2B 参数，但在修复基准测试中达到了与 10B+模型相当的性能。

rss · Simon Willison · 6月22日 23:43

**背景**: 图像修复是指利用周围像素信息填补图像中缺失或损坏区域的任务。Moebius 是一个轻量级的深度学习图像修复框架，仅有 0.2B 参数，最初需要 PyTorch 和 NVIDIA CUDA 支持。WebGPU 是一种现代浏览器 API，允许 Web 应用程序利用设备的 GPU 进行加速计算。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/papers/2606.19195">Paper page - Moebius : 0 . 2 B Lightweight Image Inpainting Framework...</a></li>
<li><a href="https://arxiv.org/abs/2606.19195">[2606.19195] Moebius : 0 . 2 B Lightweight Image Inpainting Framework...</a></li>
<li><a href="https://www.mlhive.com/2026/06/why-moebius-0-2b-disrupts-generative-image-inpainting">Why Moebius 0 . 2 B is Disrupting Generative Image Inpainting</a></li>

</ul>
</details>

**社区讨论**: Hacker News 上的讨论（item?id=48630171）反响积极，许多用户对基于浏览器的演示和模型质量印象深刻。一些人讨论了 WebGPU 在运行其他模型方面的潜力，另一些人则注意到巧妙使用 Claude Code 辅助移植过程。

**标签**: `#machine learning`, `#webgpu`, `#image inpainting`, `#browser`, `#porting`

---

<a id="item-10"></a>
## [FUTO Swipe：开源滑行输入模型发布](https://swipe.futo.tech/) ⭐️ 7.0/10

FUTO 发布了 FUTO Swipe，这是一系列开源滑行输入模型和算法，旨在提高移动键盘的准确性和速度，可用于 FUTO 键盘及更广泛的社区。 该项目提供了尊重隐私的替代方案，以替代 Gboard 等专有滑行输入方案，通过支持开源创新和多语言支持，可能重塑移动输入方式。 该模型基于通过 swipe.futo.org 收集的超过 100 万次滑动的开放数据集进行训练，初始版本专注于英语，并计划支持更多语言。

hackernews · futohq · 6月23日 17:50 · [社区讨论](https://news.ycombinator.com/item?id=48648619)

**背景**: 滑行输入允许用户通过在键盘上滑动手指来输入文字，算法预测意图词汇。大多数现有解决方案是专有的或侵犯隐私的，限制了定制化和数据控制。FUTO Swipe 旨在通过开放、社区驱动的方式填补这一空白。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://swipe.futo.tech/">FUTO Swipe</a></li>
<li><a href="https://github.com/futo-org/android-keyboard/releases">Releases · futo-org/android-keyboard</a></li>
<li><a href="https://swipe.futo.org/">FUTO Keyboard Swipe Training</a></li>

</ul>
</details>

**社区讨论**: 社区反馈显示对多语言支持和布局优化有强烈兴趣，用户将 FUTO Swipe 与 Gboard 进行比较。一些人报告说它几乎和 Gboard 一样好，而另一些人则指出存在随机大写和缺乏上下文感知建议等问题。

**标签**: `#keyboard`, `#swipe typing`, `#mobile input`, `#open source`, `#NLP`

---

<a id="item-11"></a>
## [Swift Package Index 被苹果收购](https://swiftpackageindex.com/blog/swift-package-index-joins-apple) ⭐️ 7.0/10

苹果公司收购了社区维护的 Swift 包搜索工具 Swift Package Index (SPI)，该消息已在 SPI 博客上公布。 此次收购表明苹果对 Swift 生态系统的进一步投入，但也引发了对平台未来开放性的担忧，以及可能整合开发者身份功能的猜测。 SPI 团队将加入苹果，服务将继续运营，但苹果明确将开发者身份列为未来方向，这可能导致与苹果生态系统的更紧密集成。

hackernews · JDevlieghere · 6月23日 18:00 · [社区讨论](https://news.ycombinator.com/item?id=48648779)

**背景**: Swift Package Index 是一个社区运营的网站，用于索引 Swift 包并显示其跨平台兼容性。它一直是 Swift 开发者的重要资源，补充了苹果自家的 Swift Package Manager。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.swift.org/blog/swift-package-index-developer-spotlight/">Swift Package Index gains Apple sponsorship | Swift .org</a></li>

</ul>
</details>

**社区讨论**: 社区反应不一：有人为 SPI 团队感到高兴，也有人对苹果在开源和开发者服务方面的记录表示怀疑，尤其是关于开发者身份整合的提及。

**标签**: `#Swift`, `#Apple`, `#Package Management`, `#Open Source`, `#Acquisition`

---

<a id="item-12"></a>
## [Meta 因数据泄露暂停员工监控项目](https://www.wired.com/story/meta-pauses-employee-tracking-program-following-internal-security-breach/) ⭐️ 7.0/10

Meta 暂停了其“模型能力倡议”（MCI）员工监控项目，该项目通过记录键盘输入和屏幕活动来训练 AI，原因是一次内部数据泄露导致员工的私人对话和绩效数据在公司内被曝光。 这一事件凸显了企业 AI 训练需求与员工隐私之间的紧张关系，引发了关于工作场所监控以及数据收集伦理边界的更广泛讨论。 此次泄露是由于包含 MCI 收集数据的数据库意外对所有 Meta 员工开放，导致明文私人对话和绩效指标被曝光。Meta 高管曾多次为该计划辩护，称其对 AI 开发是必要的。

hackernews · 1vuio0pswjnm7 · 6月24日 00:28 · [社区讨论](https://news.ycombinator.com/item?id=48653575)

**背景**: Meta 于今年 4 月启动了“模型能力倡议”（MCI），通过追踪员工在公司笔记本电脑上的活动（包括键盘输入和屏幕录制）来收集 AI 模型训练数据。该计划曾因隐私问题遭到员工内部批评。这并非 Meta 首次因数据处理引发争议，该公司此前曾卷入剑桥分析等隐私丑闻。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.wired.com/story/meta-pauses-employee-tracking-program-following-internal-security-breach/">Meta Pauses Employee-Tracking Program Following Internal Data Leak | WIRED</a></li>
<li><a href="https://www.businessinsider.com/meta-ai-training-data-leak-exposed-employee-activity-across-company-2026-6">Meta pauses an AI training program that tracks employees' keystrokes after an internal leak</a></li>
<li><a href="https://dataconomy.com/2026/06/23/meta-ai-training-program-data-leak/">Meta Pauses Employee Tracking Program After Internal Data Leak - Dataconomy</a></li>

</ul>
</details>

**社区讨论**: 评论者表达了强烈批评，有人称 Meta“无耻”并质疑其公司道德。还有人指出，用 AI 来保护数据具有讽刺意味，因为该工具本身很可能就是用 AI 构建的，并提到此次泄露证实了员工此前对该计划的担忧。

**标签**: `#privacy`, `#surveillance`, `#Meta`, `#data leak`, `#corporate ethics`

---

<a id="item-13"></a>
## [Datasette 1.0a35 新增带 JSON API 的创建/修改表功能](https://simonwillison.net/2026/Jun/23/datasette/#atom-everything) ⭐️ 7.0/10

Datasette 1.0a35 引入了新的创建表界面和修改表界面，两者均由 JSON API 支持，并提供了全面的模板上下文文档。此版本标志着向 1.0 稳定版迈出了重要一步。 这些功能使用户能够直接通过 Datasette 的 Web 界面和 JSON API 管理 SQLite 数据库模式，减少对外部工具的依赖。稳定的模板上下文文档也为自定义模板开发者提供了可靠的基础。 创建表 API 支持定义列、主键、自定义类型、NOT NULL 约束、默认值、表达式默认值和单列外键。修改表 API 允许添加、重命名、重新排序、删除列，更改类型、约束、主键、外键以及重命名表，并包含一个删除表按钮。

rss · Simon Willison · 6月23日 21:34

**背景**: Datasette 是一个用于探索和发布 SQLite 数据库的开源工具。它提供 Web 界面和 JSON API 用于查询和交互数据。在此版本之前，创建或修改表需要直接使用 SQLite 命令或外部工具。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://docs.datasette.io/en/latest/json_api.html">JSON API - Datasette documentation</a></li>
<li><a href="https://github.com/simonw/datasette/issues/2360">Proposal — Datasette JSON API changes for 1.0 · Issue #2360...</a></li>

</ul>
</details>

**标签**: `#datasette`, `#release`, `#database`, `#JSON API`

---