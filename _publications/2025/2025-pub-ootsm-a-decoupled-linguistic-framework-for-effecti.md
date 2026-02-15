---
title:          "OOTSM: A Decoupled Linguistic Framework for Effective Scene Graph Anticipation"
date:           2025-01-01 00:01:00 +0800
selected:       false
pub:            "Unknown Venue"
pub_last:       ' <span class="badge badge-pill badge-custom badge-dark">Scholar Paper</span>'
pub_date:       "2025"

abstract: >-
  A scene graph is a structured representation of objects and their spatio-temporal relationships in dynamic scenes. Scene Graph Anticipation (SGA) involves predicting future scene graphs from video clips, enabling applications in intelligent surveillance and human-machine collaboration. While recent SGA approaches excel at leveraging visual evidence, long-horizon forecasting fundamentally depends on semantic priors and commonsense temporal regularities that are challenging to extract purely from visual features. We therefore propose Linguistic Scene Graph Anticipation (LSGA) as an independent forecasting task in the language domain, treating visual detection as a pluggable front-end while focusing on how temporal relational dynamics should be modeled and evaluated. Concretely, we introduce Object -Oriented Two -Staged Method (OOTSM), an object-oriented two-stage framework that enhances LSGA through dynamic object prediction and relationship forecasting with temporal consistency constraints, accompanied by a dedicated LSGA benchmark derived from Action Genome annotations. Extensive experiments demonstrate that compact open-source LLMs fine-tuned for LSGA surpass strong zero-shot APIs (i.e., GPT-4o, GPT-4o-mini, DeepSeek-V3) in most evaluation metrics under equivalent input conditions and context-window constraints. In particular, integration with frozen scene-graph detectors enables these LSGA advancements to yield superior video-based SGA performance, especially in long-horizon prediction scenarios (+21.9% mR@50), highlighting the substantial complementarity for the SGA task. Code is available …

cover:          assets/images/covers/default.png
authors:
  - Xiaomeng Zhu
  - Changwei Wang
  - Haozhe Wang
  - Xinyu Liu
  - Fangzhen Lin
links:
  Paper: https://openreview.net/forum?id=azZZukIriZ
---
