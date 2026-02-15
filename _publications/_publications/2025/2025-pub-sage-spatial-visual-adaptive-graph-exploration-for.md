---
title:          "Sage: Spatial-visual adaptive graph exploration for visual place recognition"
date:           2025-02-15 00:01:00 +0800
selected:       false
pub:            "ICLR2026"
pub_last:       ' <span class="badge badge-pill badge-custom badge-dark">Scholar Paper</span>'
pub_date:       "2025"

abstract: >-
  Visual Place Recognition (VPR) requires robust retrieval of geotagged images despite large appearance, viewpoint, and environmental variation. Prior methods focus on descriptor fine-tuning or fixed sampling strategies yet neglect the dynamic interplay between spatial context and visual similarity during training. We present SAGE (Spatial-visual Adaptive Graph Exploration), a unified training pipeline that enhances granular spatial-visual discrimination by jointly improving local feature aggregation, organize samples during training, and hard sample mining. We introduce a lightweight Soft Probing module that learns residual weights from training data for patch descriptors before bilinear aggregation, boosting distinctive local cues. During training we reconstruct an online geo-visual graph that fuses geographic proximity and current visual similarity so that candidate neighborhoods reflect the evolving embedding landscape. To concentrate learning on the most informative place neighborhoods, we seed clusters from high-affinity anchors and iteratively expand them with a greedy weighted clique expansion sampler. Implemented with a frozen DINOv2 backbone and parameter-efficient fine-tuning, SAGE achieves SOTA across eight benchmarks. It attains 98.9%, 95.8%, 94.5%, and 96.0% Recall@1 on SPED, Pitts30k-test, MSLS-val, and Nordland, respectively. Notably, our method obtains 100% Recall@10 on SPED only using 4096D global descriptors. Code and models will be released upon acceptance.

cover:          assets/images/covers/default.png
authors:
  - Shunpeng Chen
  - Changwei Wang
  - Rongtao Xu
  - Xingtian Pei
  - Yukun Song
  - Jinzhou Lin
  - Wenhao Xu
  - Jingyi Zhang
  - Li Guo
  - Shibiao Xu
links:
  Paper: https://arxiv.org/abs/2509.25723
---
