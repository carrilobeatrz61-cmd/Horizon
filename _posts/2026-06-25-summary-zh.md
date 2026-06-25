---
layout: default
title: "Horizon Summary: 2026-06-25 (ZH)"
date: 2026-06-25
lang: zh
---

> 从 49 条内容中筛选出 14 条重要资讯。

---

1. [OpenAI 携手 Broadcom 发布首款定制 AI 芯片 'Jalapeno'](#item-1) ⭐️ 9.0/10
2. [Anthropic 指控阿里巴巴通过蒸馏窃取 Claude AI 能力](#item-2) ⭐️ 8.0/10
3. [高通收购 AI 编译器初创公司 Modular](#item-3) ⭐️ 8.0/10
4. [NVIDIA 45°C 冷却方案大幅降低数据中心用水](#item-4) ⭐️ 8.0/10
5. [5 亿美元基金旨在终结呼吸道感染](#item-5) ⭐️ 8.0/10
6. [Nub：一个类似 Bun 的 Node.js 一体化工具包](#item-6) ⭐️ 8.0/10
7. [GPT-5 Pro 助力破解三年免疫学谜题](#item-7) ⭐️ 8.0/10
8. [LLM 生成的求职申请失去个人特色](#item-8) ⭐️ 8.0/10
9. [LuaJIT 3.0 提议语法扩展，引发争议](#item-9) ⭐️ 7.0/10
10. [Cloudflare 面向所有用户推出自管理 OAuth](#item-10) ⭐️ 7.0/10
11. [OpenAI 支持 Appia 基金会制定 AI 标准](#item-11) ⭐️ 7.0/10
12. [MDN 浏览器兼容数据转为 SQLite 数据库](#item-12) ⭐️ 7.0/10
13. [Datasette 1.0a35 新增创建/修改表 API](#item-13) ⭐️ 7.0/10
14. [OPFS + Pyodide 测试工具实现持久化 SQLite](#item-14) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [OpenAI 携手 Broadcom 发布首款定制 AI 芯片 'Jalapeno'](https://techcrunch.com/2026/06/24/openai-unveils-its-first-custom-chip-built-by-broadcom/) ⭐️ 9.0/10

OpenAI 与 Broadcom 联合发布了由台积电制造的定制 AI 推理芯片 Jalapeno，声称其设计周期仅九个月，并借助 OpenAI 自身模型加速了开发过程。 这标志着 OpenAI 首次涉足定制芯片领域，旨在减少对英伟达等 GPU 供应商的依赖，并优化其模型的推理效率，有望降低用户成本并提升性能。 Jalapeno 是一款专为 LLM 推理设计的巨型掩模版级 ASIC，采用大型计算小芯片和 HBM 内存，以平衡高吞吐量和低延迟，特别适用于推理和智能体工作负载。

hackernews · jamdesk · 6月24日 17:47 · [社区讨论](https://news.ycombinator.com/item?id=48663324)

**背景**: AI 推理是运行已训练模型进行预测的过程，与需要大量算力的训练不同。谷歌 TPU 等定制芯片已证明，专用硬件在推理方面可超越通用 GPU。OpenAI 此举顺应了 AI 公司自研芯片以获取竞争优势的趋势。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openai.com/index/openai-broadcom-jalapeno-inference-chip/">OpenAI and Broadcom unveil LLM-optimized inference chip | OpenAI</a></li>
<li><a href="https://www.tomshardware.com/tech-industry/artificial-intelligence/broadcom-and-openai-unveil-custom-built-jalapeno-inference-processor-openais-first-chip-is-a-massive-reticle-sized-asic-built-in-an-ultra-fast-nine-month-development-cycle">Broadcom and OpenAI unveil custom-built Jalapeño inference processor — OpenAI's first chip is a massive reticle-sized ASIC built in an ultra-fast nine-month development cycle | Tom's Hardware</a></li>
<li><a href="https://www.cnbc.com/2026/06/24/openai-and-broadcom-reveal-jalapeno-first-ai-chip-in-partnership.html">OpenAI and Broadcom reveal Jalapeno, first AI chip in partnership</a></li>

</ul>
</details>

**社区讨论**: 评论者对声称的由 AI 加速的九个月设计周期表示怀疑，有人称其为营销噱头。其他人则讨论了推理芯片的技术优势，将 Jalapeno 与 Taalas 和 Cerebras 等竞争对手进行比较，并指出台积电作为制造商的重要性。

**标签**: `#AI hardware`, `#OpenAI`, `#custom chip`, `#inference`, `#Broadcom`

---

<a id="item-2"></a>
## [Anthropic 指控阿里巴巴通过蒸馏窃取 Claude AI 能力](https://www.reuters.com/world/china/anthropic-says-alibaba-illicitly-extracted-claude-ai-model-capabilities-2026-06-24/) ⭐️ 8.0/10

Anthropic 指控阿里巴巴在 2026 年 4 月 22 日至 6 月 5 日期间，通过近 25,000 个欺诈账户发起大规模蒸馏攻击，非法提取其 Claude AI 模型的能力，共产生超过 2880 万次交互。 此事件凸显了模型蒸馏作为窃取 AI 能力手段的日益威胁，可能削弱前沿 AI 开发者的竞争优势，并引发严重的知识产权和国家安全担忧。 该蒸馏攻击利用 Claude 的输出训练较弱模型，即黑盒蒸馏技术，被 Anthropic 的安全系统检测到。阿里巴巴尚未公开回应这些指控。

hackernews · htrp · 6月24日 19:48 · [社区讨论](https://news.ycombinator.com/item?id=48664814)

**背景**: 模型蒸馏是一种机器学习技术，通过让较小的“学生”模型学习较大“教师”模型的输出来实现类似性能，同时降低计算成本。虽然合法用于研究和效率提升，但未经授权蒸馏专有模型可能构成知识产权盗窃。Anthropic 的 Claude 是领先的 AI 模型，其能力被视为宝贵的商业秘密。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Model_distillation">Model distillation</a></li>
<li><a href="https://www.bbc.com/news/articles/cwyklykn5dwo">Anthropic accuses Chinese rival Alibaba of illicitly extracting AI capabilities</a></li>
<li><a href="https://nationalcioreview.com/articles-insights/extra-bytes/claude-ai-model-extraction-security-and-export-control-implications/">Claude AI Model Extraction: Security and Export Control Implications - The National CIO Review</a></li>

</ul>
</details>

**社区讨论**: 社区评论观点不一：有人解释了蒸馏的技术方法（黑盒与 RLAIF），也有人质疑 Anthropic 的投诉伦理，因为 LLM 本身也是用公开抓取的数据训练的。一位评论者指出，中国转售商以大幅折扣出售 Claude 令牌，通过出售用户日志和推理链作为训练数据来补贴成本。

**标签**: `#AI`, `#security`, `#model distillation`, `#Anthropic`, `#Alibaba`

---

<a id="item-3"></a>
## [高通收购 AI 编译器初创公司 Modular](https://www.reuters.com/business/qualcomm-buy-ai-startup-modular-2026-06-24/) ⭐️ 8.0/10

2026 年 6 月 24 日，高通宣布以约 40 亿美元收购 Modular 公司，该公司是 Mojo 编程语言和 MAX 推理栈的开发商。 此次收购可能使高通能够挑战英伟达的 CUDA 主导地位，通过提供针对 ARM 芯片优化的高性能、跨平台 AI 推理栈，有望降低大规模 AI 推理的成本。 Modular 的 Mojo 语言基于 MLIR，旨在结合类似 Python 的易用性和 C++级别的性能，而 MAX 栈则提供了一个硬件无关的 AI 推理服务框架。该交易预计于 2026 年底完成。

hackernews · timmyd · 6月24日 13:49 · [社区讨论](https://news.ycombinator.com/item?id=48659798)

**背景**: Modular 由 LLVM 和 Swift 的原创者 Chris Lattner 与 Tim Davis 共同创立。Mojo 是一种专有编程语言，通过 MLIR 可编译到 CPU、GPU 和 TPU 等多种目标。高通是 ARM 芯片的领先设计商，并一直在扩展其 AI 能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mojo_(programming_language)">Mojo (programming language)</a></li>
<li><a href="https://www.modular.com/">Modular: Inference from Kernel to Cloud</a></li>
<li><a href="https://github.com/modular/modular">GitHub - modular/modular: The Modular Platform (includes MAX & Mojo) · GitHub</a></li>

</ul>
</details>

**社区讨论**: 社区反应不一：一些人失望地认为 Mojo 可能无法成为真正的跨平台语言，而另一些人则看到高通利用 ARM 进行大规模推理的潜力。评论者还注意到高通收购 AI 和 RISC-V 相关公司的更广泛战略。

**标签**: `#acquisition`, `#AI`, `#compiler`, `#Qualcomm`, `#Modular`

---

<a id="item-4"></a>
## [NVIDIA 45°C 冷却方案大幅降低数据中心用水](https://blogs.nvidia.com/blog/liquid-cooling-ai-factories/) ⭐️ 8.0/10

NVIDIA 推出了一种 45°C 直接芯片级液冷架构，用于 AI 数据中心，可将水耗降至接近零，并实现废热用于区域供暖。 这项创新解决了 AI 数据中心日益增长的用水和能源需求，有望节省数百万美元并提升可持续性。它还为区域供暖系统开辟了新的协同效应，惠及当地社区。 冷却液温度 45°C 高于传统液冷（通常 20-30°C），减少了对冷水机组和水蒸发的需求。该设计在适宜气候下效果最佳，并可搭配热泵用于区域供暖。

hackernews · nitin_flanker · 6月24日 14:10 · [社区讨论](https://news.ycombinator.com/item?id=48660178)

**背景**: 数据中心消耗大量电力和水用于冷却，尤其是在 AI 工作负载增加机架密度的情况下。传统风冷正被液冷取代以提高效率。区域供暖网络可利用数据中心废热，降低整体能源成本。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.guru3d.com/story/nvidia-unveils-liquid-cooling-design-for-ai-data-centers/">NVIDIA Unveils 45 ° C Liquid Cooling Design for AI Data Centers</a></li>
<li><a href="https://www.techbuzz.ai/articles/nvidia-s-45-c-liquid-cooling-redefines-ai-data-center-energy">NVIDIA's 45 ° C Liquid Cooling Redefines AI Data Center Energy</a></li>
<li><a href="https://www.networkworld.com/article/4149069/why-ai-rack-densities-make-liquid-cooling-nonnegotiable.html">Why AI rack densities make liquid cooling ... | Network World</a></li>

</ul>
</details>

**社区讨论**: 评论者强调了区域供暖的潜力，指出 45°C 对此类系统可行，每年可带来数百万美元的价值。有人质疑其新颖性，指出其他设施已使用高温液冷。还有人要求更多关于气候依赖性和泵限制的细节。

**标签**: `#data centers`, `#cooling`, `#sustainability`, `#NVIDIA`, `#energy efficiency`

---

<a id="item-5"></a>
## [5 亿美元基金旨在终结呼吸道感染](https://blog.interceptfund.com/p/ending-respiratory-infections) ⭐️ 8.0/10

一项 5 亿美元的慈善基金已启动，旨在通过空气净化和预防技术消除呼吸道感染。 呼吸道感染几乎每年影响每个人，这项举措可能大幅减少全球范围内的疾病和死亡，尤其是对脆弱人群。 该基金专注于可扩展的空气净化和预防措施，针对普通感冒、流感和新兴病原体。它由主要慈善家支持，旨在十年内部署解决方案。

hackernews · EthanFantl · 6月25日 01:14 · [社区讨论](https://news.ycombinator.com/item?id=48667588)

**背景**: 呼吸道感染是疾病和死亡的主要原因，造成数十亿的生产力损失。疫苗和口罩等现有干预措施的采用率或有效性有限。HEPA 过滤器和紫外线等空气净化技术可以减少空气传播，但尚未广泛采用。

**社区讨论**: 评论者分享了个人悲剧并表示支持，一位用户因免疫抑制而失去伴侣于一种轻微病毒。其他人批评依赖慈善解决公共卫生问题，而一些人质疑患病率统计数据。总体情绪是充满希望但谨慎。

**标签**: `#public health`, `#philanthropy`, `#respiratory infections`, `#air cleaning`, `#preventative medicine`

---

<a id="item-6"></a>
## [Nub：一个类似 Bun 的 Node.js 一体化工具包](https://github.com/nubjs/nub) ⭐️ 8.0/10

Zod 的创建者 Colin McDonnell 发布了 Nub，这是一个类似 Bun 的 Node.js 工具包，通过预加载钩子添加了转译、模块解析和 polyfill，而不替换 Node 的运行时。 Nub 通过提供 TypeScript 支持以及 Worker 和 Temporal 等 API 的 polyfill 等现代功能，改善了 Node.js 用户的开发体验，而无需切换到像 Bun 这样的新运行时。 Nub 使用基于 oxc 的转译器（打包为 Node-API 插件），注册模块解析钩子，并按需注入 polyfill。它通过 --require 预加载钩子在原生 Node.js 上运行。

hackernews · colinmcd · 6月24日 14:14 · [社区讨论](https://news.ycombinator.com/item?id=48660267)

**背景**: Node.js 是一个基于 Chrome V8 引擎的 JavaScript 运行时。Bun 是一个较新的运行时，内置了转译器、包管理器和测试运行器，提供了简化的开发体验。Nub 旨在为 Node.js 带来类似的便利，而无需替换它。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://nubjs.com/">Nub — a fast runner CLI for Node . js — Nub</a></li>
<li><a href="https://github.com/nubjs/nub">GitHub - nubjs/ nub : The fast all-in-one Node . js toolkit · GitHub</a></li>
<li><a href="https://nodejs.org/api/cli.html">Command-line API | Node.js v26.3.1 Documentation</a></li>

</ul>
</details>

**社区讨论**: 社区反应积极，有用户将整个 monorepo 迁移到 Nub 且零问题。一些人讨论了技术细节，如使用 --require 与 --import 对 ESM 的支持，并提到了与 Bun 的比较。

**标签**: `#Node.js`, `#tooling`, `#developer experience`, `#TypeScript`, `#open source`

---

<a id="item-7"></a>
## [GPT-5 Pro 助力破解三年免疫学谜题](https://openai.com/index/gpt-5-immunology-mystery) ⭐️ 8.0/10

OpenAI 的 GPT-5 Pro 模型帮助免疫学家 Derya Unutmaz 解决了一个关于 T 细胞行为的长期谜题，该谜题三年来一直未解。 这一突破展示了 GPT-5 在加速科学发现方面的潜力，尤其是在免疫学领域，对癌症和自身免疫性疾病研究具有重要意义。 GPT-5 Pro 在 GPQA（一个包含极难科学问题的基准测试）上取得了最先进的性能，使其能够推理复杂的生物数据并提出新颖的假设。

rss · OpenAI News · 6月23日 17:00

**背景**: T 细胞是一种白细胞，在适应性免疫反应中起核心作用。了解其行为对于开发癌症和自身免疫性疾病的治疗方法至关重要。GPT-5 Pro 是 OpenAI 最新模型的高级版本，专为高级用户设计，具备研究级推理能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openai.com/index/introducing-gpt-5/">Introducing GPT - 5 | OpenAI</a></li>
<li><a href="https://en.wikipedia.org/wiki/T_cell">T cell - Wikipedia</a></li>

</ul>
</details>

**标签**: `#GPT-5`, `#immunology`, `#AI in science`, `#cancer research`, `#autoimmune disease`

---

<a id="item-8"></a>
## [LLM 生成的求职申请失去个人特色](https://simonwillison.net/2026/Jun/24/tom-macwright/#atom-everything) ⭐️ 8.0/10

Tom MacWright 观察到，越来越多的求职申请和作品集由 LLM 生成，变得千篇一律、缺乏个性，无法展现候选人的真实情况。 这一趋势削弱了求职申请的目的——传达候选人的独特技能和个性，可能导致招聘流程效率降低且更加缺乏人情味。 MacWright 指出，这些申请通常链接到 LLM 生成的作品集网站和 GitHub 项目，提交信息也完全由 LLM 生成，让他完全感受不到背后的人。

rss · Simon Willison · 6月24日 18:13

**背景**: 像 GPT-4 这样的大型语言模型（LLM）能够生成类似人类的文本，因此可用于起草简历和求职信。然而，过度依赖这些工具可能导致内容缺乏真实性和个人风格，而这在求职申请中至关重要。

**标签**: `#careers`, `#ai`, `#hiring`, `#authenticity`, `#llm`

---

<a id="item-9"></a>
## [LuaJIT 3.0 提议语法扩展，引发争议](https://github.com/LuaJIT/LuaJIT/issues/1475) ⭐️ 7.0/10

LuaJIT 3.0 提议语法扩展，包括 C 风格运算符（如 && 替代 and，|| 替代 or）和三目运算符（x ? y : z），相关提案已在 GitHub 问题中发布。 该提案可能显著改变 Lua 的语法和语言特性，虽然可能提升与类 C 语言的互操作性，但存在碎片化和丧失 Lua 简洁性的风险。 提案包括现有运算符的替代语法以及三目表达式等新特性，旨在让来自其他语言背景的开发者更容易上手 Lua。

hackernews · phreddypharkus · 6月25日 00:41 · [社区讨论](https://news.ycombinator.com/item?id=48667336)

**背景**: LuaJIT 是 Lua 的即时编译器，以高性能著称。Lua 本身是一种轻量级脚本语言，语法简洁。该提案旨在现代化 LuaJIT 的语法，同时保持与 Lua 5.1 的兼容性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://luajit.org/extensions.html">Extensions</a></li>
<li><a href="https://news.ycombinator.com/item?id=48667336">LuaJIT 3.0 proposed syntax extensions | Hacker News</a></li>

</ul>
</details>

**社区讨论**: 社区评论褒贬不一：有人支持这些生活质量改进，也有人批评这些改变不必要且损害了 Lua 的特性。三目运算符尤其有争议，有建议改用 Luau 的 if-then-else 表达式语法。

**标签**: `#LuaJIT`, `#syntax`, `#programming languages`, `#open source`

---

<a id="item-10"></a>
## [Cloudflare 面向所有用户推出自管理 OAuth](https://blog.cloudflare.com/oauth-for-all/) ⭐️ 7.0/10

Cloudflare 宣布推出自管理 OAuth，允许用户创建 OAuth 客户端，授权第三方应用访问其 Cloudflare 资源，从而扩展平台生态系统。 这使得开发者能够更安全、更灵活地构建与 Cloudflare 的集成，减少对 API 令牌的依赖，并为 Cloudflare 应用生态系统开辟新的可能性。 自管理 OAuth 提供了一种比 API 令牌更安全、更用户友好且更易于管理的替代方案，所有用户均可免费使用。

hackernews · terryds · 6月25日 02:18 · [社区讨论](https://news.ycombinator.com/item?id=48668033)

**背景**: OAuth 是一种基于令牌的身份验证和授权开放标准，允许用户在不共享凭据的情况下授予对其资源的有限访问权限。此前 Cloudflare 仅对特定集成支持 OAuth；此次发布将其推广给所有用户。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://cloudflare-docs.cloudflare-docs.workers.dev/changelog/post/2026-06-03-public-oauth-clients/">Introducing self - managed OAuth clients · Changelog</a></li>
<li><a href="https://developers.cloudflare.com/cloudflare-one/access-controls/applications/http-apps/managed-oauth/">Managed OAuth · Cloudflare One docs</a></li>
<li><a href="https://www.cloudflare.com/learning/access-management/what-is-oauth/">What is OAuth? | SAML vs. OAuth | Cloudflare</a></li>

</ul>
</details>

**社区讨论**: 社区评论表达出复杂情绪：一些人认为 OAuth 令人困惑并担心复杂性，另一些人则质疑其安全影响和滥用可能性，并与 AWS 的做法进行比较。还有人担心 Cloudflare 扩张过于广泛。

**标签**: `#Cloudflare`, `#OAuth`, `#API`, `#Security`, `#Developer Tools`

---

<a id="item-11"></a>
## [OpenAI 支持 Appia 基金会制定 AI 标准](https://openai.com/index/helping-build-shared-standards-for-advanced-ai) ⭐️ 7.0/10

OpenAI 宣布支持 Appia 基金会，该基金会隶属于 Linux 基金会联合开发基金会，旨在为先进 AI 制定共享标准、评估框架和安全实践。 此次合作意义重大，因为它促进了先进 AI 的全球合作和标准化安全措施，这对于整个行业负责任地开发和部署 AI 至关重要。 Appia 基金会专注于为 AI 价值链创建模块化开源规范和符合性评估，确保 AI 系统满足消费者的期望和义务。

rss · OpenAI News · 6月23日 13:00

**背景**: Appia 基金会由 Linux 基金会联合开发基金会发起，旨在为 AI 价值链建立标准化的符合性规范。它致力于提供评估 AI 系统是否满足消费者义务和期望的实用手段。OpenAI 的参与为这一标准化工作增添了可信度和行业影响力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://appiafoundation.org/">Appia Foundation</a></li>
<li><a href="https://www.linuxfoundation.org/press/linux-foundation-launches-appia-foundation-to-establish-standardized-conformity-specifications-across-the-ai-value-chain">Linux Foundation Launches Appia Foundation to Establish...</a></li>

</ul>
</details>

**标签**: `#AI safety`, `#AI governance`, `#standards`, `#OpenAI`, `#global cooperation`

---

<a id="item-12"></a>
## [MDN 浏览器兼容数据转为 SQLite 数据库](https://simonwillison.net/2026/Jun/24/browser-compat-db/#atom-everything) ⭐️ 7.0/10

Simon Willison 将 MDN 的 browser-compat-data 转换成一个约 66MB 的 SQLite 数据库，并通过 GitHub 托管，带有开放的 CORS 头，可通过 Datasette Lite 轻松访问。 这使得 MDN 全面的浏览器兼容数据对开发者更易访问，无需解析 JSON 文件即可快速查询并集成到工具中。 该数据库使用 sqlite-utils 和 GitHub Actions 工作流构建，然后强制推送到一个孤立分支，以利用 GitHub 的 CDN 和 CORS 头。

rss · Simon Willison · 6月24日 23:59

**背景**: MDN Web Docs 提供了一个浏览器兼容数据仓库（browser-compat-data），开发者用它来检查哪些 Web 特性在不同浏览器中得到支持。Simon Willison 创建了 sqlite-utils，一个用于构建和操作 SQLite 数据库的工具。CORS 头允许 Web 应用从不同源访问资源，使得 Datasette Lite 等工具可以直接加载该数据库。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://developer.mozilla.org/en-US/blog/introducing-mdn-mcp-server/">Introducing the MDN MCP server - MDN Web Docs</a></li>
<li><a href="https://github.com/mdn/mcp">GitHub - mdn/mcp: MDN's prototype MCP server · GitHub</a></li>
<li><a href="https://sqlite-utils.datasette.io/">sqlite - utils</a></li>

</ul>
</details>

**标签**: `#browser-compat`, `#SQLite`, `#developer-tools`, `#data-engineering`

---

<a id="item-13"></a>
## [Datasette 1.0a35 新增创建/修改表 API](https://simonwillison.net/2026/Jun/23/datasette/#atom-everything) ⭐️ 7.0/10

Datasette 1.0a35 引入了新的创建和修改表界面及 JSON API，用户可通过 API 或 UI 定义列、主键、约束等。同时，它还提供了稳定的模板上下文文档，用于自定义模板。 此版本标志着 Datasette 1.0 的重要进展，实现了此前仅能通过 SQLite 命令完成的编程式模式变更。它使开发者能够以 Datasette 为后端构建动态数据库应用。 创建表 API 支持列类型、NOT NULL 约束、字面量和表达式默认值以及单列外键。修改表 API 支持添加、重命名、重新排序和删除列，以及更改类型、默认值、约束和主键/外键。

rss · Simon Willison · 6月23日 21:34

**背景**: Datasette 是一个用于探索和发布 SQLite 数据库的开源工具，提供 Web 界面和 JSON API 用于数据查询。此前，创建或修改表需要直接使用 SQLite 命令；此版本为模式变更添加了一流的 API 支持。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://docs.datasette.io/en/latest/json_api.html?highlight=pagination">JSON API - Datasette documentation</a></li>
<li><a href="https://simonwillison.net/2026/jun/23/datasette/">Release: datasette 1.0a35 | Simon Willison’s Weblog</a></li>

</ul>
</details>

**标签**: `#datasette`, `#open source`, `#database`, `#release`, `#JSON API`

---

<a id="item-14"></a>
## [OPFS + Pyodide 测试工具实现持久化 SQLite](https://simonwillison.net/2026/Jun/23/opfs-pyodide/#atom-everything) ⭐️ 6.0/10

Simon Willison 发布了一个测试工具，将 Origin Private File System (OPFS) 与 Pyodide 结合，探索在基于浏览器的 Python 应用（如 Datasette Lite）中编辑持久化 SQLite 文件。 该实验可能实现无需服务器的完全客户端持久化数据应用，扩展基于 WebAssembly 的 Python 工具的能力。 该工具使用 OPFS（一种用于源私有沙盒文件存储的浏览器 API）和 Pyodide（编译为 WebAssembly 的 Python 运行时）。它由 Claude Code for web 构建，并以 playground UI 形式提供。

rss · Simon Willison · 6月23日 18:58

**背景**: Datasette Lite 通过 Pyodide 和 WebAssembly 在浏览器中完全运行 Python Datasette 应用。OPFS 提供了一个高性能、特定于源的虚拟文件系统，对用户不可见，适合在 Web 应用中进行持久化存储。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/API/File_System_API/Origin_private_file_system">Origin private file system - Web APIs | MDN</a></li>
<li><a href="https://pyodide.org/">Pyodide — Version 314.0.0</a></li>
<li><a href="https://web.dev/articles/origin-private-file-system">The origin private file system | Articles | web.dev</a></li>

</ul>
</details>

**标签**: `#OPFS`, `#Pyodide`, `#WebAssembly`, `#Datasette Lite`, `#browser storage`

---