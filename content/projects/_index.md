---
title: "Projects"
description: "Research projects on conversational recommendation and dialogue systems by Victor Li Chuang."
---

### [A Conversation is Worth A Thousand Recommendations: A Survey of Holistic Conversational Recommendation Systems](/projects/project1/)

[Paper](https://arxiv.org/abs/2309.07682), [Github](https://github.com/lichuangnus/CRS-Paper-List)

Conversational recommendation systems (CRS) generate recommendations through an interactive process. However, not all CRS approaches use human conversations as their source of interaction data; the majority of prior CRS work simulates interactions by exchanging entity-level information. As a result, claims of prior CRS work do not generalise to real-world settings where conversations take unexpected turns, or where conversational and intent understanding is not perfect. To tackle this challenge, the research community has started to examine *holistic CRS*, which are trained using conversational data collected from real-world scenarios. We present a comprehensive survey of holistic CRS methods.

### [Zero-shot Dialogue State Tracking with Unlabelled Data](/projects/project2/)

In previous zero-shot DST, transferring learning methods are adopted while the unlabelled data in the target domain is ignored. We leverage the unlabelled data in the zero-shot DST by transforming the zero-shot problem into a few-shot problem with a two-step training strategy. Our proposed methods outperform the baseline by 8%.

### [Incorporating External Knowledge and Goal Guidance for LLM-based Conversational Recommender Systems (ChatCRS)](/projects/project3/)

[Paper](https://arxiv.org/abs/2405.01868), [Github](https://github.com/lichuangnus/ChatCRS)

Even the most advanced LLMs struggle to generate grounded, recommendation-oriented responses, or to proactively steer a conversation through different dialogue goals. We introduce ChatCRS, a framework that decomposes conversational recommendation into a knowledge retrieval agent, which reasons over external knowledge bases through a tool-augmented approach, and a goal-planning agent that predicts the next dialogue goal. Combining knowledge grounding with explicit goal planning improves informativeness by 17% and proactivity by 27%, and boosts recommendation accuracy by up to 10x on multi-goal recommendation datasets.

### [Improving Conversational Recommendation with Contextual Adaptation of External Recommenders and LLM-Based Reranking (CARE)](/projects/project4/)

[Paper](https://arxiv.org/pdf/2508.13889), [Github](https://github.com/lichuangnus/CARE-CRS_ECIR2026)

LLMs used directly as conversational recommenders frequently suggest items outside the target catalogue, and lean almost entirely on dialogue context for content-based suggestions — neglecting the collaborative signals among item sequences that traditional recommenders capture well. CARE combines an external recommender system, acting as a domain expert grounded in collaborative signals, with an LLM functioning as a reranker over its candidates using the full conversational context. This contextual adaptation improves recommendation accuracy by an average of 54% on ReDial and 25% on INSPIRED over using either component alone, even in low-resource settings.
