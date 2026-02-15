---
title:          "MLIP: Efficient Multi-Perspective Language-Image Pretraining with Exhaustive Data Utilization"
date:           2024-02-15 00:01:00 +0800
selected:       false
pub:            "ICML 2024"
pub_last:       ' <span class="badge badge-pill badge-custom badge-dark">Scholar Paper</span>'
pub_date:       "2024"

abstract: >-
  Contrastive Language-Image Pretraining (CLIP) has achieved remarkable success, leading to rapid advancements in multimodal studies. However, CLIP faces a notable challenge in terms of inefficient data utilization. It relies on a single contrastive supervision for each image-text pair during representation learning, disregarding a substantial amount of valuable information that could offer richer supervision. Additionally, the retention of non-informative tokens leads to increased computational demands and time costs, particularly in CLIP's ViT image encoder. To address these issues, we propose Multi-Perspective Language-Image Pretraining (MLIP). In MLIP, we leverage the frequency transform's sensitivity to both high and low-frequency variations, which complements the spatial domain's sensitivity limited to low-frequency variations only. By incorporating frequency transforms and token-level alignment, we expand CILP's single supervision into multi-domain and multi-level supervision, enabling a more thorough exploration of informative image features. Additionally, we introduce a token merging method guided by comprehensive semantics from the frequency and spatial domains. This allows us to merge tokens to multi-granularity tokens with a controllable compression rate to accelerate CLIP. Extensive experiments validate the effectiveness of our design.

cover:          assets/images/covers/default.png
authors:
  - Yu Zhang
  - Qi Zhang
  - Zixuan Gong
  - Yiwei Shi
  - Yepeng Liu
  - Duoqian Miao
  - Yang Liu
  - Ke Liu
  - Kun Yi
  - Wei Fan
  - Liang Hu
  - Changwei Wang
links:
  Paper: https://arxiv.org/abs/2406.01460
---
