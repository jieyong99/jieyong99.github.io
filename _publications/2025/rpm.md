---
title: "LLMs Think, But Not In Your Flow: Reasoning-Level Personalization for Black-Box Large Language Models"
date: 2025-05-23
selected: true
# pub: "International Conference on Machine Learning (ICML)"
# pub_pre:        "Submitted to "
pub_post: "Under review."
# pub_last: ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date: "2025"

abstract: >-
  Large language models (LLMs) have recently achieved impressive performance across a wide range of natural language tasks and are now widely used in real-world applications. Among them, black-box LLMs--served via APIs without access to model internals--are especially dominant due to their scalability and ease of deployment. Despite their strong capabilities, these models typically produce generalized responses that overlook personal preferences and reasoning styles. This has led to growing interest in black-box LLM personalization, which aims to tailor model outputs to user-specific context without modifying model parameters. However, existing approaches primarily focus on response-level personalization, attempting to match final outputs without modeling personal thought process. To address this limitation, we propose RPM, a framework for reasoning-level personalization that aligns the model's reasoning process with a user's personalized logic. RPM first constructs statistical user-specific factors by extracting and grouping response-influential features from user history. It then builds personalized reasoning paths that reflect how these factors are used in context. In the inference stage, RPM retrieves reasoning-aligned examples for new queries via feature-level similarity and performs inference conditioned on the structured factors and retrieved reasoning paths, enabling the model to follow user-specific reasoning trajectories. This reasoning-level personalization enhances both predictive accuracy and interpretability by grounding model outputs in user-specific logic through structured information. Extensive experiments across diverse tasks show that RPM consistently outperforms response-level personalization methods, demonstrating the effectiveness of reasoning-level personalization in black-box LLMs.
cover: assets/images/covers/rpm_figure.png
authors:
  - Jieyong Kim*
  - Tongyoung Kim*
  - Soojin Yoon
  - Jaehyung Kim
  - Dongha Lee#
links:
  Paper: https://arxiv.org/abs/2505.21082
---
