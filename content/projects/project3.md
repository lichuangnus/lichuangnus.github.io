---
title: "Incorporating External Knowledge and Goal Guidance for LLM-based Conversational Recommender Systems (ChatCRS)"
description: "ChatCRS: Incorporating External Knowledge and Goal Guidance for LLM-based Conversational Recommender Systems."
---

[Paper](https://arxiv.org/abs/2405.01868), [Github](https://github.com/lichuangnus/ChatCRS)

Large language models, even the most advanced ones, still struggle in conversational recommendation: they find it difficult to generate grounded, recommendation-oriented responses, or to proactively steer the conversation through different dialogue goals rather than passively responding to the user. As a result, LLM-based conversational recommenders often produce generic suggestions that are not well grounded in domain knowledge, and fail to guide the conversation strategically towards a successful recommendation.

We introduce *ChatCRS*, a framework that decomposes conversational recommendation into two specialised components: a *knowledge retrieval agent*, which uses a tool-augmented approach to reason over external knowledge bases, and a *goal-planning agent*, which predicts the next dialogue goal to keep the conversation moving productively towards a recommendation. By combining explicit knowledge grounding with goal-oriented planning, ChatCRS improves informativeness by 17% and proactivity by 27%, and boosts recommendation accuracy by up to 10x on multi-goal recommendation datasets.
