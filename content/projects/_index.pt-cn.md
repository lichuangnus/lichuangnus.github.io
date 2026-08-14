---
title: "项目"
description: "李闯在会话推荐与对话系统方向的研究项目介绍。"
---

### A Conversation is Worth A Thousand Recommendations: A Survey of Holistic Conversational Recommendation Systems

[Paper](https://arxiv.org/abs/2309.07682), [Github](https://github.com/lichuangnus/CRS-Paper-List)

会话推荐系统 (CRS) 通过与用户的交互式对话来生成推荐。然而，以往大多数 CRS 研究并不使用真实的人类对话作为交互数据，而是通过交换实体级别的信息来模拟交互过程，导致这些方法难以推广到真实场景中——对话可能出现意料之外的转折，或者对话理解本身并不完美。为应对这一挑战，学术界开始关注基于真实对话数据训练的 *整体式会话推荐系统 (holistic CRS)*。我们对整体式 CRS 方法进行了一次全面的综述。

### Zero-shot Dialogue State Tracking with Unlabelled Data

以往的零样本对话状态追踪 (DST) 研究大多采用迁移学习方法，却忽略了目标领域中未标注数据的价值。我们提出了一种两阶段训练策略，将零样本问题转化为少样本问题，从而充分利用目标领域的未标注数据，效果较基线方法提升了 8%。

### Incorporating External Knowledge and Goal Guidance for LLM-based Conversational Recommender Systems (ChatCRS)

[Paper](https://arxiv.org/abs/2405.01868), [Github](https://github.com/lichuangnus/ChatCRS)

即便是最先进的大语言模型，在会话推荐任务中依然难以生成有理有据、面向推荐目标的回复，也难以主动引导对话朝不同的对话目标推进。我们提出 ChatCRS 框架，将会话推荐拆分为两个专门的模块：一个基于工具增强方法在外部知识库中进行推理的知识检索智能体，以及一个预测下一步对话目标的目标规划智能体。结合知识支撑与目标规划，ChatCRS 在多目标推荐数据集上将信息量提升 17%，主动性提升 27%，推荐准确率最高提升达 10 倍。

### Improving Conversational Recommendation with Contextual Adaptation of External Recommenders and LLM-Based Reranking (CARE)

[Paper](https://arxiv.org/pdf/2508.13889), [Github](https://github.com/lichuangnus/CARE-CRS_ECIR2026)

当大语言模型被直接用作会话推荐器时，常常会推荐出不在目标商品库中的物品，也过度依赖对话上下文进行基于内容的推荐，而忽视了传统推荐系统所擅长捕捉的物品序列间的协同关系。CARE 将外部推荐系统（作为掌握协同信号的领域专家）与担任重排序器角色的大语言模型相结合：外部推荐系统基于协同信号提出候选集合，大语言模型再结合完整对话上下文对候选项进行重排序与筛选。这种情境适配方法在 ReDial 和 INSPIRED 数据集上分别将推荐准确率平均提升了 54% 和 25%，在低资源场景下同样有效。
