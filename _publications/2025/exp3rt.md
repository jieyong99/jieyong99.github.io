---
title: "Review-driven Personalized Preference Reasoning with Large Language Models for Recommendation"
date: 2025-04-05
selected: true
pub: "Special Interest Group on Information Retrieval (SIGIR)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last: ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date: "2025"

abstract: >-
  Recent advancements in Large Language Models (LLMs) have demonstrated exceptional performance across a wide range of tasks, generating significant interest in their application to recommendation systems. However, existing methods have not fully capitalized on the potential of LLMs, often constrained by limited input information or failing to fully utilize their advanced reasoning capabilities. To address these limitations, we introduce EXP3RT, a novel LLM-based recommender designed to leverage rich preference information contained in user and item reviews. EXP3RT is basically fine-tuned through distillation from a teacher LLM to perform three key tasks in order: EXP3RT first extracts and encapsulates essential subjective preferences from raw reviews, aggregates and summarizes them according to specific criteria to create user and item profiles. It then generates detailed step-by-step reasoning followed by predicted rating, i.e., reasoning-enhanced rating prediction, by considering both subjective and objective information from user/item profiles and item descriptions. This personalized preference reasoning from EXP3RT enhances rating prediction accuracy and also provides faithful and reasonable explanations for recommendation. Extensive experiments show that EXP3RT outperforms existing methods on both rating prediction and candidate item reranking for top-k recommendation, while significantly enhancing the explainability of recommendation systems.
cover: assets/images/covers/exp3rt_figure.png
authors:
  - Jieyong Kim*
  - Hyunseo Kim*
  - Hyunjin Cho
  - SeongKu Kang
  - Buru Chang
  - Jinyoung Yeo
  - Dongha Lee#
links:
  Paper: https://arxiv.org/abs/2408.06276
---
