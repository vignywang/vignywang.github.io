---
title:          "S2A: A Unified Framework for Parameter and Memory Efficient Transfer Learning"
date:           2025-02-15 00:01:00 +0800
selected:       false
pub:            "arXiv preprint arXiv:2503.08154"
pub_last:       ' <span class="badge badge-pill badge-custom badge-dark">Scholar Paper</span>'
pub_date:       "2025"

abstract: >-
  Parameter-efficient transfer learning (PETL) aims to reduce the scales of pretrained models for multiple downstream tasks. However, as the models keep scaling up, the memory footprint of existing PETL methods is not significantly reduced compared to the reduction of learnable parameters. This limitation hinders the practical deployment of PETL methods on memory-constrained devices. To this end, we proposed a new PETL framework, called Structure to Activation (S2A), to reduce the memory footprint of activation during fine-tuning. Specifically, our framework consists of: 1) Activation modules design(i.e., bias, prompt and side modules) in the parametric model structure, which results in a significant reduction of adjustable parameters and activation memory; 2) 4-bit quantization of activations based on their derivatives for non-parametric structures (e.g., nonlinear functions), which maintains accuracy while significantly reducing memory usage. Our S2A method consequently offers a lightweight solution in terms of both parameters and memory footprint. We evaluated S2A with different backbones and performed extensive experiments on various datasets to evaluate the effectiveness. The results show that our methods not only outperform existing PETL techniques, achieving a fourfold reduction in GPU memory footprint on average, but also shows competitive performance in accuracy with fewer tunable parameters. These demonstrate that our method is highly suitable for practical transfer learning on hardware-constrained devices.

cover:          assets/images/covers/default.png
authors:
  - Tian Jin
  - Enjun Du
  - Changwei Wang
  - Wenhao Xu
  - Ding Luo
links:
  Paper: https://arxiv.org/abs/2503.08154
---
