---
title:          "Vision Also You Need: Navigating Out-of-Distribution Detection with Multimodal Large Language Model"
date:           2026-01-01 00:01:00 +0800
selected:       false
pub:            "arXiv preprint arXiv:2601.14052"
pub_last:       ' <span class="badge badge-pill badge-custom badge-dark">Scholar Paper</span>'
pub_date:       "2026"

abstract: >-
  Out-of-Distribution (OOD) detection is a critical task that has garnered significant attention. The emergence of CLIP has spurred extensive research into zero-shot OOD detection, often employing a training-free approach. Current methods leverage expert knowledge from large language models (LLMs) to identify potential outliers. However, these approaches tend to over-rely on knowledge in the text space, neglecting the inherent challenges involved in detecting out-of-distribution samples in the image space. In this paper, we propose a novel pipeline, MM-OOD, which leverages the multimodal reasoning capabilities of MLLMs and their ability to conduct multi-round conversations for enhanced outlier detection. Our method is designed to improve performance in both near OOD and far OOD tasks. Specifically, (1) for near OOD tasks, we directly feed ID images and corresponding text prompts into MLLMs to identify potential outliers; and (2) for far OOD tasks, we introduce the sketch-generate-elaborate framework: first, we sketch outlier exposure using text prompts, then generate corresponding visual OOD samples, and finally elaborate by using multimodal prompts. Experiments demonstrate that our method achieves significant improvements on widely used multimodal datasets such as Food-101, while also validating its scalability on ImageNet-1K.

cover:          assets/images/covers/default.png
authors:
  - Haoran Xu
  - Yanlin Liu
  - Zizhao Tong
  - Jiaze Li
  - Kexue Fu
  - Yuyang Zhang
  - Longxiang Gao
  - Shuaiguang Li
  - Xingyu Li
  - Yanran Xu
  - Changwei Wang
links:
  Paper: https://arxiv.org/abs/2601.14052
---
