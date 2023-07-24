#! https://zhuanlan.zhihu.com/p/642149893
- [LLM 相关项目](#llm-相关项目)
- [01. 开源：参考 功能，代码流程](#01-开源参考-功能代码流程)
- [02. 闭源：借鉴 产品流程](#02-闭源借鉴-产品流程)
- [03. GPT 相关 开源项目](#03-gpt-相关-开源项目)
- [04. GPT Prompt Engineer](#04-gpt-prompt-engineer)
- [05. 一键翻译 图片文字](#05-一键翻译-图片文字)
- [06. ChatGPT 网页模拟](#06-chatgpt-网页模拟)
  - [6.1. Yidadaa/ChatGPT-Next-Web 36K](#61-yidadaachatgpt-next-web-36k)
  - [6.2. Chanzhaoyu/chatgpt-web 25K](#62-chanzhaoyuchatgpt-web-25k)
  - [6.3. pengzhile 潘多拉 **黑科技！** 18k](#63-pengzhile-潘多拉-黑科技-18k)
  - [6.4. Bin-Huang/chatbox 13K](#64-bin-huangchatbox-13k)
  - [6.5. chatgpt-web-share 2.2K](#65-chatgpt-web-share-22k)
- [07. Al Zebra: 面向儿童的AI数学辅导软件](#07-al-zebra-面向儿童的ai数学辅导软件)
- [08. ShortGPT：自动化内容创作框架](#08-shortgpt自动化内容创作框架)
- [09. Code Interpreter: 开源平替](#09-code-interpreter-开源平替)

# LLM 相关项目

[Github备份地址](https://github.com/moyy/ai_share/blob/main/src/topic/ai_project.md)

# 01. 开源：参考 功能，代码流程

||Github Star数||
|--|--|--|
|[SQL Genius](https://sqlgenius.app)||用AI将自然语言转化为 SQL，可以自己定义表结构|
|[Danswer](https://github.com/danswer-ai/danswer)||开源企业级问答系统|
|[gpt-author](https://github.com/mshumer/gpt-author)||使用GPT-4和Stable Diffusion API调用链生成原创奇幻小说|
|[GPT Code UI](https://github.com/ricklamers/gpt-code-ui/)||开源 GPT 代码解释器插件|
|[GPTCache](https://github.com/zilliztech/GPTCache)|4.3k|用`向量数据库`做缓存|
|[PDF-GPT](https://github.com/bhaskatripathi/pdfGPT)|5.3k||
|[Semantra](https://github.com/freedmand/semantra)||语义搜索|
|[Quivr](https://github.com/StanGirard/quivr)||基于 Langchain / Supabase 的 QA|
|[AutoGPT](https://autogpt.net/)||旨在使GPT-4完全自主|
|[L♾️pGPT](https://github.com/farizrahman4u/loopgpt)|1.1k|AutoGPT 的 重新实现|
|[GPT Engineer](https://github.com/AntonOsika/gpt-engineer)|31.9k|指定你希望它构建什么，人工智能要求澄清，然后构建它|
|[Private PGT](https://github.com/imartinez/privateGPT)|31.4k|拥有您公司所有知识的私人聊天GPT。|
|[localGPT](https://github.com/PromtEngineer/localGPT)|8.7k|类似 privateGPT，用 Vicuna-7B 模型替换了 GPT4ALL 模型，并且我们使用 InstructorEmbeddings 而不是原始 privateGPT 中使用的 LlamaEmbeddings|
|[AgentGPT](https://agentgpt.reworkd.ai/zh)|24.3k|基于浏览器的 AutoGPT 实现，可通过无代码平台访问|
|[BabyAGI](https://github.com/yoheinakajima/babyagi)|15.6k|使用人工智能管理任务的简单框架|
|[smol developer](https://github.com/smol-ai/developer)|9.9k|给产品规范，给你构建整个脚手架，并根据提示一步步完成项目|
|[SuperAGI](https://github.com/TransformerOptimus/SuperAGI)|8.4k|通过工具扩展代理的能力|
|[Bloop](https://bloop.ai/)|7k|`Rust`实现的 基于语义的 代码搜索引擎|
|[Camel](https://github.com/camel-ai/camel)|2.4k|大型语言模型社会“心灵”探索的交际主体|
|[MiniAGI](https://github.com/muellerberndt/mini-agi)|2.3k|简单的自治代理，兼容GPT-3.5-Turbo和GPT-4|
|[DataBerry](https://www.databerry.ai/)|1.9k|ChatGPT Agent Trained On Your Custom Data|
|[OpenAGI](https://github.com/agiresearch/OpenAGI)|1.3k|当LLM遇到领域专家|
|[ai-legion](https://github.com/eumemic/ai-legion)|1.1k|一个让智能体协同工作的平台，其精神类似于 AutoGPT 和 Baby AGI，但用 TypeScript 编写|
|[Superagent](https://www.superagent.sh/)|1k|用于：法律 & 个性化学习 & 市场研究 & NPC & 内容创作 & 赔率计算建议|
|[TeenageAGI](https://github.com/seanpixel/Teenage-AGI/)|818|使用 OpenAI 和 Pinecone 为 AI 代理提供记忆，并允许其在之前“思考”进行操作（输出文本）|
|[WorkGPT](https://github.com/team-openpm/workgpt)|515|你给它一个指令和一组 API，它会与 AI 来回对话，直到指令完成。|
|[Multi-GPT](https://github.com/rumpfmax/Multi-GPT)|422|多个“expertGPT”协作执行一项任务。每个人都有自己的短期和长期记忆以及相互沟通的能力。|
|[pezzo](https://github.com/pezzolabs/pezzo)|351|旨在简化提示设计、版本管理、发布、协作、故障排除、可观察性等|
|[ReactAgent](https://reactagent.io/)|150|使用GPT-4语言模型从用户故事中生成和组合React组件|
|[斯坦福 AI小镇](https://theolvs.github.io/westworld/)|6||
|[英伟达：Voyager](https://voyager.minedojo.org/)||一种具有大型语言模型的开放式化身Agent|

# 02. 闭源：借鉴 产品流程

|||
|--|--|
|[chato: QA 系统](https://chato.cn)|||
|[Mendable AI](https://www.mendable.ai/)||输入github url 的 QA|
|[DeepNote](https://deepnote.com/blog/introducing-deepnote-ai)|凭借其高效和上下文代码建议，为未来笔记本电脑中人工智能驱动的数据探索铺平了道路。|
|[Airplane Autopilot](https://www.airplane.dev/autopilot)|一家制造内部工具的公司，他们正在制造自动驾驶人工智能助手|
|[Aomni](https://www.aomni.com/)|专门为研究设计的人工智能代理|
|[BitBuilder](https://www.bitbuilder.ai/)|“开发人员的虚拟实习生”，通过针对您的存储库提出的PR生成代码|
|[butternut](https://butternut.ai/)|创建一个功能齐全、可在20秒内启动的网站的工具|
|[Cognosys](https://www.cognosys.ai/)|基于Web的AutoGPT/babyAGI版本|
|[Diagram](https://diagram.com/)|人工智能驱动的设计工具，适用于从文案到从文本生成独特图标的一切，最近被Figma收购|
|[Factory](https://www.factory.ai/)|开发用于端到端构建软件的自主编码Droid|
|[Fine Tuner](https://fine-tuner.ai/)|人工智能代理无代码构建平台|
|[Fixie](https://www.fixie.ai/)|一个创建LLM驱动的应用程序（如AI代理）的平台|
|[Floodehq](https://floodehq.com/)|人工智能通信代理，目前处于封闭测试版|
|[Grit](https://www.grit.io/)|一个用于自动修复技术差距的工具的测试版，将代码迁移和依赖升级置于自动驾驶状态|
|[Magic AI](https://hex.tech/product/magic-ai/)|Hex人工智能工具，用于人类用数据做惊人的事情|
|[Heymoon](https://heymoon.ai/)|生活私人助理：让你掌握日历、任务和信息|
|[Lindy](https://www.lindy.ai/)|人工智能助手，可以帮助完成日常任务，例如日历管理、电子邮件起草和合同发送|
|[MultiOn](https://multion.ai/)|人工智能个人代理，保持首次人工智能航班预订、食品订单（一个汉堡）和工作场所证书的记录|
|[Proficient AI](https://proficientai.com/)|允许开发人员在其应用程序中构建、部署和操作对话式人工智能代理的交互API和SDK|
|[Saga](https://saga.so/ai)|数字人工智能助手，一个集成笔记、任务和工具的人工智能工作空间|
|[Second](https://www.second.dev/)|针对每个代码库的自动化迁移和升级|

# 03. GPT 相关 开源项目

- 翻译助手：划词翻译 `openai-translator`
- 双语网页翻译插件 `immersive-translate`
- 文档秘书：你直接提问即可 `ChatPDF`
- 论文总结工具`ChatPaper`、`ResearchGPT`
- 视频助手 `Language Reactor`
- 搜索与视频总结插件 `Glarity`
- 能总结B站视频的 `BibiGPT`
- 语音对话助手 `talk-to-chatgpt`
- [MetaGPT](https://github.com/geekan/MetaGPT) 生成产品分析文档、用户故事、竞品分析、数据结构、项目 API

# 04. [GPT Prompt Engineer](https://github.com/mshumer/gpt-prompt-engineer)

用户只需要输入一些简单的任务描述，并提供参考用例。该工具便会自动帮你生成各种 Prompt，自动对 Prompt 测试和评分，帮你尽可能找到最优项目提示。

项目引入了提示测试、ELO 评级系统、权重和偏差日志记录，在 Prompt 生成过程中，给你足够的数据作为评估。

# 05. [一键翻译 图片文字](https://zyddnys/manga-image-translator)

[在线测试](https://cotrans.touhou.ai/)

一键翻译各类图片内文字，特别适合漫画的翻译，支持DeepL和ChatGPT的API。

# 06. ChatGPT 网页模拟

截至 2023.07.13 找到的 项目有如下几个，Star数 从 高到低：

## 6.1. [Yidadaa/ChatGPT-Next-Web](https://github.com/Yidadaa/ChatGPT-Next-Web) 36K

+ 支持 GPT-4
+ 流式响应
+ 国际化：英语、简体中文、繁体中文、日本语 等
+ 客户端: Windows / Mac / Linux
+ `Doing`: 模拟 插件 支持（非官方），支持联网搜索、计算器、调用其他平台 api
+ 支持自部署的LLM：`LocalAI` 项目 `llama` / `gpt4all` 等
    - **狠！** 用 [api-for-open-llm](https://github.com/xusenlinzy/api-for-open-llm)

## 6.2. [Chanzhaoyu/chatgpt-web](https://github.com/Chanzhaoyu/chatgpt-web) 25K 

两种方式 实现 OpenAI-ChatGPT 的网页模拟：

+ API: gpt-3.5-turbo
+ accessToken: 就是 通过截取网页，看懂了 GPT HTTP API 后自己模拟；
    - 依赖于第三方服务器，并且有速率限制
    - OpenAI API 代理 实现 2: [社区代理](https://github.com/transitive-bullshit/chatgpt-api#reverse-proxy)

## 6.3. [pengzhile 潘多拉](https://github.com/pengzhile/pandora) **黑科技！** 18k 

好处：

+ 免代理。
+ 如果你有账号，就可以免去 api 付费。众所周知：api 付费 按 Token，还需要 另外绑卡。。。

功能：

+ 能免梯子，有插件支持，和官网一样的体验。
+ **狠：** 支持 代码解释器，只要你有 plus 账号
+ **狠：** 支持 GPT 插件，只要你有 plus 账号
+ **狠：** [支持 Chat GPT 转 Turbo API](https://github.com/pengzhile/pandora/issues/837)

原理：

**注：** 目前 没有人 发布有关反向代理如何工作的信息，以防止 OpenAI 禁用访问！

+ 按下文获取自己的`Access Token`
+ 里面 会调用 `fakeopen`代理 提供的 api 进行 `OpenAI` 转发，但 ai.fakeopen.com 不开源；
+ `fakeopen` 代理，估计是 通过截取网页，看懂了 GPT HTTP API 后自己模拟；
+ `fakeopen` 开源平替，能力：无法访问 插件，无法访问 代码解释器！
    - **狠：** [chatgpt-api](https://github.com/transitive-bullshit/chatgpt-api#reverse-proxy) 14.7K
    - [chatgpt-proxy](https://github.com/flyingpot/chatgpt-proxy) 
    
步骤：

+ 点击 https://chat.zhile.io 包含一个共享账号的链接，没有账号的可以点进去体验一下
+ 最新拿 Access Token 的技术原理，记录在 [这里](https://zhile.io/2023/05/19/how-to-get-chatgpt-access-token-via-pkce.html)
+ 可以访问 [这里](https://ai-20230626.fakeopen.com/auth) 拿 Access Token
+ 也可以官方登录，然后访问 [这里](https://chat.openai.com/api/auth/session) 拿 Access Token
+ Access Token 有效期 30 天，期间访问不需要梯子。这意味着你在手机上也可随意使用。

## 6.4. [Bin-Huang/chatbox](https://github.com/Bin-Huang/chatbox) 13K

+ 支持 OpenAI(GPT3.5, GPT4) /  Azure OpenAI / ChatGLM-6B
+ 流式回复，打字机特效
+ 适合团队办公，共享 OpenAI API 资源
+ 客户端: Windows / Mac / Linux

## 6.5. [chatgpt-web-share](https://github.com/moeakwak/chatgpt-web-share) 2.2K 

+ 共享 ChatGPT 账号 给 多用户同时使用 
+ 使用 FastAPI + Vue3 开发
+ 支持 ChatGPT Plus / 设置对话模型 / 用户请求限制等功能。
+ 支持使用 GPT-4！

# 07. [Al Zebra: 面向儿童的AI数学辅导软件](https://github.com/moreshk/alzebra)

旨在提供互动学习体验，通过根据孩子之前的回答情况提出逐渐增加难度的问题，验证答案，并为正确解决方案提供逐步解释，帮孩子们学习数学，有智能递进的问题复杂性、逐步解释正确答案以及互动有趣的学习体验等特点

# 08. [ShortGPT：自动化内容创作框架](https://github.com/RayVentura/ShortGPT)

简化了视频创作、素材获取、语音合成和编辑任务

# 09. [Code Interpreter: 开源平替](https://github.com/shroominic/codeinterpreter-api)

