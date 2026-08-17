---
layout: default
title: "Horizon Summary: 2026-08-17 (ZH)"
date: 2026-08-17
lang: zh
---

> 从 35 条内容中筛选出 11 条重要资讯。

---

1. [Stripe 以超过 70 亿美元收购 AI 公司 OpenRouter](#item-1) ⭐️ 9.0/10
2. [Qwen 3.8 27B 表现出色但默认过度思考](#item-2) ⭐️ 8.0/10
3. [Anthropic 发布 Claude 系统提示词，引发社区分析](#item-3) ⭐️ 8.0/10
4. [英伟达将 OpenAI 数据中心融资担保削减至 1200 亿美元以下](#item-4) ⭐️ 8.0/10
5. [AI 模型正有意在权重上变笨](#item-5) ⭐️ 8.0/10
6. [Cloudflare 在切换域名服务器时静默注入分析脚本](#item-6) ⭐️ 8.0/10
7. [Direct File 项目复盘：对充满政治色彩项目的平衡审视](#item-7) ⭐️ 7.0/10
8. [发展中国家嵌入式工程师为 RISC-V 的成本与灵活性辩护](#item-8) ⭐️ 7.0/10
9. [联邦关键词列表导致数十亿研究经费被取消](#item-9) ⭐️ 7.0/10
10. [达里奥·阿莫迪：AI 不信任是机构信任危机](#item-10) ⭐️ 7.0/10
11. [CORS Chat：用于测试支持 CORS 的聊天端点的 Web 界面](#item-11) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Stripe 以超过 70 亿美元收购 AI 公司 OpenRouter](https://www.bloomberg.com/news/articles/2026-08-16/stripe-nears-deal-to-buy-ai-firm-openrouter-for-over-7-billion) ⭐️ 9.0/10

据彭博社报道，Stripe 已敲定以超过 70 亿美元收购 AI 网关初创公司 OpenRouter 的协议。该交易此前已有收购谈判的报道，标志着 AI 基础设施领域的重大整合。 此次收购使 Stripe 能够掌控 AI API 路由和支付基础设施，有望成为 AI 模型访问和交易的主导中间商。这标志着金融科技与 AI 的日益融合，并可能重塑开发者消费和支付 AI 服务的方式。 OpenRouter 在 2026 年 5 月以 13 亿美元的估值融资，此次交易在不到三个月内实现了 5.4 倍的回报。此次收购将 Stripe 从支付基础设施公司转变为 AI 运营平台提供商，整合了 OpenRouter 的统一 API 和路由能力。

hackernews · zacharyozer · 8月16日 20:31 · [社区讨论](https://news.ycombinator.com/item?id=49323381)

**背景**: OpenRouter 是一个提供统一 API 的平台，可访问来自不同提供商的数百种 AI 模型，具有智能路由、故障转移和成本控制等功能。Stripe 是一家领先的在线支付处理公司，以其对开发者友好的 API 和用于处理高容量、延迟敏感请求的基础设施而闻名。此次收购符合 Stripe 的雄心，即抽象金融轨道，现在又抽象 LLM 轨道，充当 AI 模型使用和支付的中间人。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://techcrunch.com/2026/08/16/stripe-will-reportedly-acquire-ai-gateway-startup-openrouter-for-7b/">Stripe will reportedly acquire AI gateway startup OpenRouter ...</a></li>
<li><a href="https://fortune.com/2026/08/16/stripe-7-billion-deal-ai-firm-openrouter-acquisition/">Stripe clinches over $7 billion deal to buy AI firm OpenRouter</a></li>
<li><a href="http://endroid.com/2026/stripe-openrouter-acquisition-7-billion/">Stripe Acquires OpenRouter for $7B+ in AI Infrastructure ...</a></li>

</ul>
</details>

**社区讨论**: 社区评论强调了战略动机：Stripe 在 API 基础设施方面的专业知识以及掌控 AI 路由的愿望，以及该交易确保支付量的潜力，尤其是在 OpenAI 将其支付提供商从 Stripe 切换到 Adyen 之后。一些人质疑估值，指出 70 亿美元超过了 Lyft 等公司的市值，而另一些人则指出转换成本和分销优势是合理的。

**标签**: `#acquisition`, `#AI infrastructure`, `#fintech`, `#OpenRouter`, `#Stripe`

---

<a id="item-2"></a>
## [Qwen 3.8 27B 表现出色但默认过度思考](https://simonwillison.net/2026/Aug/16/qwen-38-27b/) ⭐️ 8.0/10

阿里巴巴 Qwen 实验室于 2026 年 8 月发布了 Qwen 3.8 27B，这是一款采用 Apache 2.0 许可、拥有 270 亿参数的视觉能力大语言模型。该模型在基准测试中相比前代 Qwen 3.6 27B 以及闭源的 Qwen 3.7-Plus 均有显著提升，但默认的'xhigh'推理强度导致大量 token 消耗和缓慢的推理速度。 此次发布对开源权重 LLM 社区意义重大，因为它提供了一个可在消费级硬件上运行的强大视觉模型，可能使高质量多模态 AI 更加普及。然而，默认的过度思考行为凸显了可用性挑战，可能阻碍其在实际应用中的采用。 该模型支持 262,144 token 的原生上下文长度，可通过 RoPE 扩展到 1M。Simon Willison 通过 LM Studio 测试了 17GB 的 Q4_K_M 量化版本，发现使用默认的'xhigh'推理时，一个简单的 SVG 生成任务耗时 21 分钟，使用了 22,276 个推理 token 生成 3,223 个输出 token。他建议增加上下文限制以避免触及默认的 8,192 token 上限。

rss · Simon Willison · 8月16日 22:00 · [社区讨论](https://news.ycombinator.com/item?id=49324985)

**背景**: Qwen 3.8 27B 是一个基于 Qwen 3.5 架构、拥有 270 亿参数的密集模型，并带有视觉编码器。它是阿里巴巴 Qwen 系列的一部分，该系列包括开源权重和闭源模型。该模型的默认推理强度设置为'xhigh'，旨在处理复杂任务，但在消费级硬件上日常使用并不实际。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://simonwillison.net/2026/Aug/16/qwen-38-27b/">Qwen 3.8 27B is excellent, but it defaults to wildly overthinking things</a></li>
<li><a href="https://huggingface.co/Qwen">Org profile for Qwen on Hugging Face, the AI community building the...</a></li>
<li><a href="https://lmstudio.ai/models/qwen3.8">Qwen 3 . 8</a></li>

</ul>
</details>

**社区讨论**: 社区评论普遍认为 Qwen 3.8 27B 表现出色，但存在过度思考和推理缓慢的问题。用户报告称其 token 效率非常低，一位用户提到在双 GPU 设置下完成一项任务耗时 11 小时，而 GPT 5.5 仅用 20 分钟。一些人建议使用较低的推理强度设置以提高速度，另一些人则将其与 Muse 30B 等其他模型进行比较，认为其在 token 效率方面表现更好。

**标签**: `#LLM`, `#Qwen`, `#open-source`, `#benchmarks`, `#local deployment`

---

<a id="item-3"></a>
## [Anthropic 发布 Claude 系统提示词，引发社区分析](https://platform.claude.com/docs/en/release-notes/system-prompts) ⭐️ 8.0/10

Anthropic 在其官方文档网站上发布了 Claude 模型的系统提示词，这是一次罕见的透明度举措。社区成员（包括 Simon Willison）创建了 git 历史记录来追踪版本之间的变化，例如 Opus 4.8 和 Opus 5 之间的差异。 此次发布为研究人员和从业者提供了前所未有的机会，深入了解领先 AI 模型的设计，从而分析和理解塑造 Claude 响应的行为准则。这也为 AI 行业的透明度树立了先例，可能促使其他提供商效仿。 系统提示词异常冗长且详细，一些社区成员对此表示质疑，因为近期建议是保持提示词简短。提示词包含处理图像、争议话题和复杂逻辑的具体规则，并且会随模型版本更新，社区维护的 git 仓库中可以看到这些变化。

hackernews · tosh · 8月16日 12:48 · [社区讨论](https://news.ycombinator.com/item?id=49319556)

**背景**: 系统提示词是在用户输入之前提供给 AI 模型的隐藏指令，用于指导其行为和安全护栏。Anthropic 决定发布这些提示词是罕见的，因为大多数提供商都将其保密。此举使得外部能够分析 Claude 如何设计来处理各种场景，并与关于 AI 透明度和问责制的更广泛讨论相一致。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/asgeirtj/system_prompts_leaks">GitHub - asgeirtj/ system _ prompts _leaks: Extracted system prompts ...</a></li>
<li><a href="https://www.prompthub.us/blog/an-analysis-of-the-claude-4-system-prompt">An Analysis of the Claude 4 System Prompt - prompthub.us</a></li>
<li><a href="https://braintitan.medium.com/anthropic-has-taken-the-rare-step-of-proactively-announcing-system-prompts-of-claude-and-promised-fe6565bda4aa">Anthropic has taken the rare step of proactively announcing system ...</a></li>

</ul>
</details>

**社区讨论**: 社区情绪总体积极，用户赞赏这种透明度以及 Simon Willison 等成员提供的详细分析。然而，一些人担心提示词的长度，质疑其必要性或可能分散模型的注意力。此外，还有关于论坛上 AI 相关故事审核的附带抱怨。

**标签**: `#AI`, `#Anthropic`, `#Claude`, `#system prompts`, `#transparency`

---

<a id="item-4"></a>
## [英伟达将 OpenAI 数据中心融资担保削减至 1200 亿美元以下](https://www.reuters.com/business/nvidia-scales-back-250-billion-openai-data-center-guarantee-wsj-reports-2026-08-14/) ⭐️ 8.0/10

据报道，英伟达已大幅减少其为 OpenAI 拟议的俄亥俄州数据中心项目可能提供的融资担保金额，从 2500 亿美元降至不到 1200 亿美元。这一调整是在投资者对这家芯片制造商在大型 AI 基础设施融资中的风险敞口表示担忧之后做出的。 这一削减标志着 AI 投资格局的转变，主要参与者正在重新评估大规模基础设施项目的财务风险。它可能影响 AI 数据中心建设的步伐以及 AI 行业更广泛的资本周期。 最初 2500 亿美元的金额是在 7 月底讨论的，但英伟达现在预计最初担保不到 1200 亿美元。该交易尚未签署，整个园区建设可能耗资高达 5000 亿美元，使其可能成为有史以来最昂贵的单一建设项目。

hackernews · root-parent · 8月16日 21:07 · [社区讨论](https://news.ycombinator.com/item?id=49323686)

**背景**: 英伟达和 OpenAI 于 2025 年 9 月宣布建立战略合作伙伴关系，为 OpenAI 的下一代 AI 基础设施部署至少 10 吉瓦的英伟达系统。融资担保是英伟达支持大型数据中心项目的一种方式，但如果项目失败或表现不佳，这会使公司面临巨大的财务风险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://theoutpost.ai/news-story/nvidia-slashes-financial-guarantee-for-open-ai-s-ohio-data-center-from-250-b-to-under-120-b-29811/">Nvidia Cuts OpenAI Ohio Data Center Guarantee to $120B</a></li>
<li><a href="https://finance.yahoo.com/technology/ai/articles/nvidia-scales-back-250-billion-234356524.html?fr=sycsrp_catchall">Nvidia scales back funding guarantee for Ohio OpenAI data ...</a></li>
<li><a href="https://nvidianews.nvidia.com/news/openai-and-nvidia-announce-strategic-partnership-to-deploy-10gw-of-nvidia-systems">OpenAI and NVIDIA Announce Strategic Partnership to Deploy 10 ...</a></li>

</ul>
</details>

**社区讨论**: 社区评论强调了对 AI 行业循环融资和“虚假利润”的担忧，有人指出英伟达正变得更像一家储蓄贷款公司。其他人指出，即使担保减少，英伟达仍可能盈利，还有人认为这是将 GPU 变成资产类别战略的一部分。

**标签**: `#Nvidia`, `#OpenAI`, `#AI infrastructure`, `#financing`, `#data centers`

---

<a id="item-5"></a>
## [AI 模型正有意在权重上变笨](https://w4g1.dev/blog/models-are-getting-dumber-on-purpose) ⭐️ 8.0/10

文章认为，AI 模型正有意减少存储在权重中的事实性知识，转而依赖工具使用和外部知识检索。这标志着一种重要的设计趋势，即模型更注重推理和工具集成，而非参数化记忆。 这一趋势对模型设计、幻觉率和 AI 生态系统具有重大影响，可能导致更小、更高效的模型依赖可插拔知识库。它也挑战了传统上通过扩大模型规模来获取知识的方式，可能重塑 AI 系统的构建和部署方式。 文章引用了事实回忆基准 SimpleQA，目前领先的 Gemini 2.5 Pro 得分仅为 53%，凸显了参数化知识的局限。文章还预测未来模型卡可能不再列出知识截止日期，因为权重过时的周期将从几周延长到几年。

hackernews · hruvhwe · 8月16日 19:04 · [社区讨论](https://news.ycombinator.com/item?id=49322695)

**背景**: 大型语言模型（LLM）传统上在训练时将知识存储在参数中，这可能导致知识过时和幻觉。检索增强生成（RAG）是一种混合方法，将 LLM 与外部最新数据源结合，减少对参数化记忆的依赖，提高准确性和时效性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://strategycore.com/resources/model-weights-quantization-reproducibility">Why the Model You Run Still Matters: Weights ... | StrategyCore</a></li>
<li><a href="https://www.techginity.com/blog/why-rag-llm-systems-outperform-standard-language-models">Why RAG LLM Systems Outperform Standard Language Models</a></li>
<li><a href="https://www.databricks.com/blog/what-is-retrieval-augmented-generation">What is Retrieval Augmented Generation (RAG)? | Databricks</a></li>

</ul>
</details>

**社区讨论**: 社区评论对可插拔知识库表现出兴趣，一位用户设想为特定领域提供模块化模型。另一位评论者批评文章过时，指出 SimpleQA 未更新且 Gemini 2.5 Pro 已发布十六个月。还有评论者质疑推理与事实能否真正分离，认为推理往往需要事实基础。

**标签**: `#AI`, `#LLM`, `#knowledge bases`, `#tool use`, `#model design`

---

<a id="item-6"></a>
## [Cloudflare 在切换域名服务器时静默注入分析脚本](https://news.ycombinator.com/item?id=49322107) ⭐️ 8.0/10

有用户报告称，在将域名服务器切换到 Cloudflare 以启用 R2 存储桶服务后，Cloudflare 静默地向其纯 HTML、无 JavaScript 的网站注入了 Web Analytics JavaScript 代码片段。用户必须通过 Analytics 仪表板手动选择退出，他们认为这种做法具有侵入性。 这引发了重大的隐私和同意问题，因为 Cloudflare 默认注入跟踪脚本，未明确征得用户同意。这影响到许多依赖 Cloudflare 进行 DNS 或代理的用户，他们可能不知道这一行为，从而可能削弱对平台的信任。 注入的脚本来自 static.cloudflareinsights.com/beacon.min.js，并包含带有 token 的 data-cf-beacon 属性。用户可以通过设置限制脚本来源的 Content-Security-Policy (CSP) 头，或在 Cloudflare 仪表板中手动禁用分析来缓解此问题。

hackernews · stagas · 8月16日 17:49

**背景**: Cloudflare Web Analytics，也称为真实用户监控 (RUM)，是 Cloudflare 提供的注重隐私的免费分析服务。当用户将域名服务器切换到 Cloudflare 时，该服务可能会自动启用 Web Analytics，并向提供的页面注入 JavaScript beacon，即使网站是静态的且没有 JavaScript。这种行为类似于一些免费托管提供商注入广告或脚本，但对于 DNS 和 CDN 提供商来说，这是出乎意料的。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://news.ycombinator.com/item?id=49322107">Tell HN: Cloudflare silently injects its analytics when you switch nameservers | Hacker News</a></li>
<li><a href="https://burgeonlab.com/blog/cloudflare-web-analytics-rum-injected-tracking-beacon-script-into-my-sites/">Cloudflare Auto Injected Tracking Scripts To My Sites</a></li>
<li><a href="https://www.cloudflare.com/web-analytics/">Cloudflare Web Analytics | Cloudflare</a></li>

</ul>
</details>

**社区讨论**: 社区表达了担忧并分享了技术解决方案。有用户建议使用 Content-Security-Policy (CSP) 头来阻止注入的脚本，另一位用户确认看到了该脚本并提供了其来源。一些用户质疑如果仅将 Cloudflare 用于 DNS，注入是如何发生的，指出这暗示代理处于活动状态。其他人将其与旧式免费主机注入广告的行为进行比较，强调了其侵入性。

**标签**: `#Cloudflare`, `#privacy`, `#analytics`, `#security`, `#web`

---

<a id="item-7"></a>
## [Direct File 项目复盘：对充满政治色彩项目的平衡审视](https://www.ischool.berkeley.edu/sites/default/files/vinton_report_5.pdf) ⭐️ 7.0/10

一份关于 Direct File 项目的复盘报告已发布，详细审视了其在充满政治色彩的环境中的成败。该报告由团队成员撰写，对项目生命周期进行了平衡的分析。 这份报告为政治与技术的交汇提供了宝贵见解，特别是对政府数字基础设施项目而言。它强调了在政治敏感背景下提供用户友好的数字服务所面临的挑战和机遇，对政策制定者和技术专家都具有参考价值。 该报告写作质量上乘，提供了关键细节和相关背景，同时保持对全局和紧迫期限的关注。它以事实的方式处理党派政治环境，对成功与失败给予同等考量。

hackernews · ronbenton · 8月17日 00:17 · [社区讨论](https://news.ycombinator.com/item?id=49325185)

**背景**: Direct File 是一项免费的在线政府服务，允许符合条件的纳税人直接向美国国税局提交联邦纳税申报表。该项目是联邦政府改善数字服务更广泛努力的一部分，其复盘报告为类似项目提供了案例研究。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/IRS_Direct_File">IRS Direct File - Wikipedia</a></li>
<li><a href="https://fas.org/publication/direct-file-is-the-floor-not-ceiling/">Direct File Is the Floor, Not the Ceiling - fas.org</a></li>
<li><a href="https://www.gao.gov/assets/gao-25-106933.pdf">GAO-25-106933, DIRECT FILE: IRS Successfully Piloted Online ...</a></li>

</ul>
</details>

**社区讨论**: 社区评论称赞该报告的平衡性和写作质量，一位用户表示阅读起来出乎意料地愉快。另一位评论者对项目的终结表示怀疑，将其归因于政治原因而非项目本身，还有一位认为政府不应维护数字基础设施，而应将其外包。

**标签**: `#government`, `#digital infrastructure`, `#post-mortem`, `#politics`, `#technology`

---

<a id="item-8"></a>
## [发展中国家嵌入式工程师为 RISC-V 的成本与灵活性辩护](https://rvembedded.com/blog_post/12/) ⭐️ 7.0/10

一位来自发展中国家的嵌入式工程师发表了对 RISC-V 批评的回应，认为其灵活性和低成本使其非常适合资源有限地区的嵌入式系统。文章强调了成本和可及性的重要性，而这些在性能比较主导的讨论中常被忽视。 这一视角将 RISC-V 的讨论扩展到性能指标之外，强调了影响发展中国家开发者的经济和物流因素。它挑战了关于硬件采用关键因素的假设，可能影响社区对 RISC-V 价值主张的评估。 作者指出，将低成本芯片运送到其国家的运费可能高达 60 至 200 美元，使得即使 1 美元的芯片也变得昂贵，但声称 RISC-V 部件可以以每个 10 美分的价格到达。这一明显的矛盾在评论中引发争议，一些读者质疑其成本逻辑。

hackernews · Narishma · 8月16日 17:01 · [社区讨论](https://news.ycombinator.com/item?id=49321717)

**背景**: RISC-V 是一种基于精简指令集计算（RISC）原则的开源指令集架构（ISA），设计上简单、模块化且可扩展。嵌入式系统是在更大系统中具有专用功能的专用计算机系统，常用于消费电子和工业应用。关于 RISC-V 可行性的争论通常集中在性能和碎片化上，但成本和可及性对于资源有限地区的开发者至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.geeksforgeeks.org/computer-organization-architecture/computer-organization-risc-and-cisc/">RISC vs CISC - GeeksforGeeks</a></li>
<li><a href="https://en.wikipedia.org/wiki/Embedded_system">Embedded system - Wikipedia</a></li>
<li><a href="https://www.arm.com/glossary/embedded-system-design">What Is Embedded System Design (ESD)?</a></li>

</ul>
</details>

**社区讨论**: Hacker News 上的评论内容充实，用户们就原始批评和作者的观点展开辩论。一些人认为作者忽略了原始文章对性能和碎片化的关注，而另一些人则质疑成本和运费逻辑，指出作者说法中的不一致之处。

**标签**: `#RISC-V`, `#embedded systems`, `#hardware`, `#cost analysis`, `#developer perspective`

---

<a id="item-9"></a>
## [联邦关键词列表导致数十亿研究经费被取消](https://www.highereddive.com/news/inside-the-federal-keyword-lists-that-canceled-billions-in-research-funding/826203/) ⭐️ 7.0/10

法庭文件显示，包括 NIH 和 NSF 在内的联邦机构使用关键词列表来识别和终止研究拨款，导致数十亿美元的资金被取消。NSF 的列表尤其源自参议员 Ted Cruz 在 2024 年的一份报告。 这种做法对科学进步和学术自由具有重大影响，因为它针对 DEI 和绿色能源等研究领域，可能扼杀重要工作。它影响了全国的研究人员，尤其是严重依赖联邦拨款的早期职业科学家。 在四个机构中，NSF 使用的关键词数量远远最多。关键词搜索针对的是面临保守派反对的倡议，如 DEI 和绿色能源，并被用于取消研究人员（包括加州大学的研究人员）持有的拨款。

hackernews · walrus01 · 8月17日 00:14 · [社区讨论](https://news.ycombinator.com/item?id=49325159)

**背景**: 联邦研究经费是科学家，尤其是早期职业研究人员的重要支持来源。使用基于关键词的搜索来取消拨款，代表了联邦机构执行政策方式的转变，引发了对政治干预科学的担忧。NSF 依赖政治报告凸显了政治与研究经费的交集。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.highereddive.com/news/inside-the-federal-keyword-lists-that-canceled-billions-in-research-funding/826203/">Inside the federal keyword lists that canceled billions in ...</a></li>
<li><a href="https://education.ufl.edu/educational-research/2026/08/05/inside-the-federal-keywords-that-canceled-billions-in-research-funding/">Inside the Federal Keywords that Canceled Billions in ...</a></li>
<li><a href="https://www.byteseu.com/2232369/">Inside the federal keyword lists that canceled billions in ...</a></li>

</ul>
</details>

**社区讨论**: 社区评论表达了强烈不满，一位用户称该政府“严重且恶意地无能”，另一位将其描述为“卑鄙和邪恶的巢穴”。还有一个链接指向关于禁用词列表的相关讨论，以及一条评论将问题归咎于“右翼推特脑”。

**标签**: `#research funding`, `#federal policy`, `#science policy`, `#academia`, `#government`

---

<a id="item-10"></a>
## [达里奥·阿莫迪：AI 不信任是机构信任危机](https://simonwillison.net/2026/Aug/16/dario-amodei/) ⭐️ 7.0/10

Anthropic 首席执行官达里奥·阿莫迪在推特上表示，公众对 AI 的不信任主要不是由 AI 领导人的警告引起的，而是由更广泛的机构信任危机所致。他指出，重建信任需要实实在在的成果，比如真正治愈癌症，而不是营销活动。 这一观点反驳了“AI 领导人的风险警告加剧公众恐惧”的常见说法，并强调了提供实际利益的重要性。这对 AI 伦理和行业讨论具有重要意义，因为它将焦点从信息传递转向实际成果。 阿莫迪特别批评了“华丽营销活动”的想法，并指出“AI 将治愈癌症”之类的说法是陈词滥调，人们认为这是欺骗。他承认，对包括 Anthropic 在内的 AI 公司最准确的批评是，它们尚未兑现造福世界的重大承诺。

rss · Simon Willison · 8月16日 15:05

**背景**: 达里奥·阿莫迪是 Anthropic 的联合创始人兼首席执行官，该公司开发了 Claude 大型语言模型。他曾在 OpenAI 担任研究副总裁。几十年来，公众对机构的信任一直在下降，根据城市研究所的数据，自 1979 年以来，美国主要机构的信任度下降了 22 个百分点。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Dario_Amodei">Dario Amodei - Wikipedia</a></li>
<li><a href="https://www.urban.org/research/publication/understanding-crisis-institutional-trust">Understanding the Crisis in Institutional Trust | Urban Institute</a></li>

</ul>
</details>

**标签**: `#AI ethics`, `#public trust`, `#Anthropic`, `#Dario Amodei`, `#AI industry`

---

<a id="item-11"></a>
## [CORS Chat：用于测试支持 CORS 的聊天端点的 Web 界面](https://simonwillison.net/2026/Aug/15/cors-chat/) ⭐️ 6.0/10

Simon Willison 发布了 CORS Chat，这是一个基于 Web 的工具，用于测试支持 CORS 的 OpenAI-Responses 兼容聊天端点。它包含一个新颖的功能，可以在令牌流式传输时逐步渲染 SVG 图像。 该工具简化了测试本地和远程 LLM 端点的过程，特别是对于使用 LM Studio 或 OpenRouter 的开发者。渐进式 SVG 渲染功能提供了一种实时可视化模型输出的独特方式，可以增强调试和用户体验。 CORS Chat 在浏览器中持久化对话，并允许导出为 JSON。它已使用--cors 选项与 LM Studio 以及 OpenRouter 进行了测试，两者均运行正常。

rss · Simon Willison · 8月15日 14:49

**背景**: CORS（跨源资源共享）是一种安全机制，允许 Web 应用程序从不同源请求资源。OpenAI-Responses 兼容端点是指遵循 OpenAI Responses API 格式的 API，从而实现不同 LLM 提供商之间的互操作性。LM Studio 是一个本地 LLM 服务器，通过--cors 标志支持 CORS，而 OpenRouter 是一个通过统一 API 提供多个 LLM 访问的服务。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://lmstudio.ai/docs/developer/openai-compat">OpenAI Compatibility Endpoints | LM Studio</a></li>
<li><a href="https://lmstudio.ai/docs/developer/core/server/settings">Server Settings | LM Studio</a></li>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/SVG">SVG : Scalable Vector Graphics | MDN</a></li>

</ul>
</details>

**标签**: `#developer-tools`, `#CORS`, `#chat`, `#LLM`, `#web-UI`

---