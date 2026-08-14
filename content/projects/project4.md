---
title: "Improving Conversational Recommendation with Contextual Adaptation of External Recommenders and LLM-Based Reranking (CARE)"
description: "CARE: Contextual Adaptation of Recommenders for LLM-based Conversational Recommendation."
date: 2026-01-01
---

[Paper](https://arxiv.org/pdf/2508.13889), [Github](https://github.com/lichuangnus/CARE-CRS_ECIR2026)

When large language models are used directly as conversational recommenders, they frequently recommend items that fall outside the target item catalogue, since they have no explicit grounding in it. They also tend to rely almost entirely on the dialogue context for content-based suggestions, neglecting the collaborative relationships among item sequences that traditional recommender systems are specifically designed to capture.

*CARE* (Contextual Adaptation of Recommenders) addresses this by combining an external recommender system, which acts as a domain expert grounded in collaborative signals, with an LLM that functions as a reranker: the external recommender proposes a candidate set from the target catalogue, and the LLM reranks and selects among them using the full conversational context. This division of labour lets each component do what it is best at, significantly improving recommendation accuracy of LLM-based conversational recommenders by an average of 54% on ReDial and 25% on INSPIRED, even in low-resource settings.
