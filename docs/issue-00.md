---
title: In The Loop 科技周刊：创刊号｜以长期主义观察世界
date: 2023-12-31 14:33:36
type: garden
author: houmin
tags:
---

`Hello World`，这里是 In The Loop 科技周刊，是 In The Loop 在 2024 年新成立的一个栏目。In The Loop 科技周刊的灵感来自阮一峰老师的科技爱好者周刊[^1]，珠玉在前，In The Loop 更多地会从自己视角出发，重点关注目前日新月异的科技发展，包括但不限于 LLM、多模态、Agent、机器智能、计算生物、分子动力学、自动驾驶、AI Infra 等新方向新行业的发展，也会尝试去结合科技创投融资动态、国家产业政策动向，看看产业界都在关注些什么。

## 创刊号｜ World In The Loop，以长期主义观察世界

### 为什么想要做 In The Loop 科技周刊？

1. 有时候发现自己对于一些行业动态只知道一些名词，知道好像有这么件事情发生，但是却一直不理解其背后的含义。根据二八法则，有时候你只需要花 20% 的时间就可以了解一件事情 80% 的部分，也希望自己以后对于所谈论的事情有敬畏心，言之有物而不是夸夸其谈。
2. 受限于目前工作带宽，每周更新一期博客对我来说十分困难，简单的题材不值得聊，深入的话题需要更长时间准备。周刊的形式会更加轻松一点，主要选取过去一周行业内发生的重点事件，简单提出一些个人观点。一方面可以监督我更好地跟进行业动态，另一方面也希望认识更多的朋友，可以共同交流，我相信真诚的、有上下文的交流有时候会擦出意想不到的火花。
3. 科技的发展往往都是草蛇灰线、螺旋发展的，当突然在某一个方向取得进展获得众人目光关注之时，也许在它之前已经有过各种不同的尝试，直到那一刻才最终成功。周刊期待以长期主义的视角，冷静观察各个方向的发展，就像我喜欢看的「晚点」一样，也许周刊会晚一点发布，但会保证不会做震惊体似的夸夸其谈，很多东西都是有逻辑的，不用每天都震惊。英国著名新闻周刊「The Economist」从 1843 年到现在已经超过了 180 年的历史，如果有机会从第一期一直看到最新一期也许会获得非常奇特的体验。

### 为什么是周刊而不是日报或者月刊 ？

1. 每天一更的频率对我来说太过频繁，即使是对于周刊这种速评的类型。不排除有很多大佬在工作之余仍然能够保持日更，对我来说，周刊是一个 side project，更多的是促进自己的学习与跟进动态，同时分享出来。
2. 对于长期一点的回顾，期望会通过主题文章来回顾，也不需要月刊这种形式。一周或者两周一期的回顾可能更加适合我这种节奏。

### 打算怎么做 In The Loop 科技周刊？

1. 去年大模型刚出来的时候，有观点说借助大模型的能力能够一人成团。在撰写本周刊时，我会尝试开发和构建自己的 Agent，期待能够通过最新的模型能力来提升我制作周刊的效率。不论是信息收集、信息整理，还是题图绘制等，希望能够探索出一套自己的 Pipeline。
2. 本周刊从第 0 期开始即是开源，所有的文字和题图都开源在 GitHub 上，具体可以参考我的 repo： https://github.com/houminz/weekly 。如果以后上述制作周刊的 Pipeline 成熟了，有机会也希望能够开源对应的工具。和阮一峰老师的科技爱好者周刊一样，欢迎大家到 GitHub 提 Issue 参与共建。
3. 目前科技周刊还在调试阶段，还不能保持每周更新的频率，周刊的排版和形式可能也会发生变化。但排除不可抗力等因素，至少能够保持两周一更。等到春暖花开，整套流水线运行无阻，那时候应该能够保持周更。

In The Loop 科技周刊的动态起点为 State of AI 的 2023 年度报告，在前几期，我将会补齐之前落后的进度。以下是本期内容，内容主要参考自 Your Guide To AI[^6] 。因为出自个人视角，难免会有一些错漏和偏差，欢迎交流与指正。

## AI Safety

10 月底，英国政府主办了首届 AI Safety 峰会，吸引力超过 27 个国家政府和众多的研究机构和科技公司参与[^3]。其中就包括了中国政府，在科技公司中代表中国参加的**只有阿里巴巴和腾讯两家公司**。峰会的成果是各国政府签署了一份声明，阐明了应对前沿人工智能风险的共同议程[^4]。

除了政府之间的合作，也有来自学界的共识。10 月底，Geoff Hinton、Yoshua Bengio 以及来自中国清华大学的姚期智院士、张亚勤院士等学术界泰斗合署的共识文件[^5]，对 AI 可能带来的风险作出警告。

11 月最重要的事件显然是 OpenAI 的纷争，经历了 Sam Altman 被开除、全体员工请辞、董事会重组，Sam Altman 回归等离奇剧情。这次混乱反映了 OpenAI 对组织结构的不可持续，之前 OpenAI 充满理想主义的组织结构创新实验或将需要被重新评估，又或许当前已经有 300 多年历史的有限责任公司的公司责任制需要进行新一轮创新与迭代？

这次纷争背后或许也反映了当前 effective altruists, EA 和 effective accelerationism, e/acc 两种思潮在 OpenAi 的竞争。
![](https://substackcdn.com/image/fetch/w_1456,c_limit,f_webp,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Ff228dd0a-ddf0-4c34-bed7-cc2e74307252_1881x2048.jpeg)

12 月，欧盟 AI Act 法案经过 2 年多的讨论终于在欧洲议会、欧盟成员国和欧盟委员会三方达成协议[^7]。法国、德国和意大利提议将法案中关于 Foundation Model 的具体监管完全删除，有观点认为法国和德国的立场分别于法国的 Mistral 公司和德国的 Aleph Alpha 公司有关。关于监管的辩论可以参考这里 [^8]，最终对所有模型的某些透明度要求进行了妥协，但对高影响力模型的规定更加严格[^9]。

![](https://www.adalovelaceinstitute.org/wp-content/uploads/2022/04/Structure-of-risk-2048x1020.png)

彭博社的这篇报道[^10] 关注了在美国芯片禁令政策下，中国政府与华为公司的密切协作，声称中国政府正在为华为在整个芯片供应链上提供前所未有的支持，主要是秘密进行，以避免进一步的美国限制。无论是否属实，我很期待华为是否能够抓住这次前所未有的机会。毕竟，中国的芯片行业已经烧掉了数千亿美元的补贴，前面还有很长的一段路要走。

## Hardware

硬件上最大的动作是美国政府对中国禁止 H800/A800，具体讨论可以参考[In The Loop 产业速评：美国 H800 禁令解析](https://mp.weixin.qq.com/s/qXf1-XI6EfnEeRYdFpav2A) ，而用于替代它们的 H20 芯片已经推迟，而美国商务部长 Gina Raimondo 警告道：

> If you redesign a chip around a particular cut line that enables them to do AI, I’m going to control it the very next day.[^11]

10 月底，MosaicML 在一篇博文[^13]中声称，由高速网络相互连接的 128 个 AMD MI250 GPU 集群在分布式 LLM 训练中表现良好，实现了与 Nvidia A100-40GB GPU 相当的性能。
![](https://cms.databricks.com/sites/default/files/inline-images/db-822-blog-images-5.png)

## Company

人狠话不多的 Mistral 最近动作频频，这家总部位于巴黎的 GenAI 公司先是在 9 月底发布了其首个模型 Mistral 7B[^13]，并通过推特发布了该模型权重的种子链接。由于采用了 Apache 2.0 许可证并具有良好的性能，该模型受到了普遍好评：在发布时，它在 MT-Bench 上胜过了所有的 7B 模型，包括 LLama-2 13B，并且不使用任何专有数据。

![](https://mistral.ai/images/news/announcing-mistral-7b/230927_bars.png)


HuggingFace 进一步在 UltraChat 数据集上进行了微调，然后使用 UltraFeedback 数据集进行了直接偏好优化（DPO）训练。
![](https://api.wandb.ai/files/vincenttu/images/projects/38380615/3139aaab.png)

最终产生的模型 Zephyr 7B Alpha 在 MT Bench 上表现优于 Llama 70B[^15]。
![](https://api.wandb.ai/files/vincenttu/images/projects/38380615/c206223a.png)

12月 Mistral 继续发布了他们的 8x7B 的 MoE 模型[^14]，采用 top-2 路由，效果十分惊艳，开源模型基本上已经可以直接打败 GPT-3.5 了。这是首个被证明有效的开源 MoE LLM，相比于古早的 Switch-Transformer 、 GLaM 等 Research， Mixtral-8x7B 证明了 MoE 真的可以落地，且效果远好于相同激活值的 Dense 模型。
![](https://mistral.ai/images/news/mixtral-of-experts/overview.png)

Mistral 强大的模型能力助推了其估值的上涨，已在最新一轮融资中筹集了 3.85 亿欧元，约合 4.15 亿美元这次融资使这家仅有 22 名员工的公司的估值飙升至约 20 亿美元。

12 月的另一个热点是 Google DeepMind 的 Gemini 模型[^16][^17][^18]，Genimi 一开始就专注于多模态并展示了令人印象深刻的音频、视频和图像识别能力，尽管其语言和代码性能更强。

虽然 Google 在 Gemini 的宣传上翻了车，具体的测评也可以看到 Google 的模型能力进化也非常快。

![](https://substackcdn.com/image/fetch/w_1456,c_limit,f_webp,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F518e3b57-e9dd-4d44-95ad-fa96e310d569_1600x1581.png)

Inflection-2 该模型使用5,000个 H100 GPU 进行训练，在一系列推理、问答、数学和编码基准测试中，它的表现优于 Llama-2、PaLM-2、Grok-1和 Claude-2，只在与 GPT-4相比的方面表现一致[^19]。

![Inflection-2](https://www.datocms-assets.com/98476/1700653492-0000000.svg)

幻方今年成立的 DeepSeek 公司发布 DeepSeek 67B，它的基础版本在各种推理、编码和中文理解方面击败了 Llama2 70B 基准模型[^20]。
![](https://www.maginative.com/content/images/size/w1000/2023/12/mathexam.png)

李开复的 01 万物发布了 YI-34B，整体上基于 LLaMA 架构，宣传上也出了一点偏差[^21]。

![](https://user-assets.sxlcdn.com/images/987821/FqwjU_vNVvo6Uo9MarqN7tiv6Y1i.png?imageMogr2/strip/auto-orient/thumbnail/1200x9000%3E/quality/90!/format/png)

Stability AI 发布了 Stable Video Diffusion[^22] 并直接开源，给火热的视频生成领域再添一把火。

![](https://images.squarespace-cdn.com/content/v1/6213c340453c3f502425776e/02e26394-e36b-4399-bacf-fea2bb26f6bd/Graph+SVD+v+Competition0.jpg)


## Research

Research 部分觉得比较有意思的是机器人领域的进展，即 RT-X-2。10 月，Google DeepMind 等研究机构联合发布了 Open-X Embodiment 数据集，统一和标准化了来自34个机器人实验室的60个现有机器人数据集，涵盖了从单臂操纵器到双臂机器人和四足机器人的22种不同实体[^23]。同时发布的还有基于 Open-X Embodiment 数据集训练出来的 RT-2-X，相对于 RT-2 性能表现更加亮眼。

![](https://robotics-transformer-x.github.io/img/rt2x.png)


本期分享到此结束，Enjoy

[^1]: https://github.com/ruanyf/weekly
[^2]: https://en.wikipedia.org/wiki/The_Economist
[^3]: https://www.gov.uk/government/publications/ai-safety-summit-introduction/ai-safety-summit-confirmed-governments-and-organisations
[^4]: https://www.gov.uk/government/publications/ai-safety-summit-2023-the-bletchley-declaration/the-bletchley-declaration-by-countries-attending-the-ai-safety-summit-1-2-november-2023
[^5]: https://managing-ai-risks.com/managing_ai_risks.pdf
[^6]: https://nathanbenaich.substack.com/
[^7]: https://www.europarl.europa.eu/news/en/press-room/20231206IPR15699/artificial-intelligence-act-deal-on-comprehensive-rules-for-trustworthy-ai
[^8]: https://twitter.com/cedric_o/status/1728724005459235052
[^9]: https://www.consilium.europa.eu/en/press/press-releases/2023/12/09/artificial-intelligence-act-council-and-parliament-strike-a-deal-on-the-first-worldwide-rules-for-ai/
[^10]: https://www.bloomberg.com/graphics/2023-china-huawei-semiconductor/?leadSource=uverify%20wall&sref=tG3ILPLB
[^11]: https://www.fierceelectronics.com/electronics/raimondo-calls-out-nvidia-others-sell-ai-chips-china
[^12]: https://www.databricks.com/blog/training-llms-scale-amd-mi250-gpus
[^13]: https://mistral.ai/news/announcing-mistral-7b/
[^14]: https://mistral.ai/news/mixtral-of-experts/
[^15]: https://wandb.ai/vincenttu/finetuning_zephyr7b/reports/Zephyr-7B-Fine-Tuning-and-Inference-with-W-B--Vmlldzo1ODc0MTcx
[^16]: https://blog.google/technology/ai/google-gemini-ai/
[^17]: https://deepmind.google/technologies/gemini/#hands-on
[^18]: https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf
[^19]: https://inflection.ai/inflection-2
[^20]: https://www.maginative.com/article/chinese-startup-unveils-impressive-new-ai-chatbot-deepseek/
[^21]: huggingface.co/01-ai/Yi-34B/discussions/11
[^22]: https://stability.ai/news/stable-video-diffusion-open-ai-video-model
[^23]: https://robotics-transformer-x.github.io/
[^24]: https://blogs.nvidia.com/blog/eureka-robotics-research/

