---
title:          "Representation Mutual Learning for End-to-End Weakly-Supervised Semantic Segmentation"
date:           2026-01-01 00:01:00 +0800
selected:       false
pub:            "Unknown Venue"
pub_last:       ' <span class="badge badge-pill badge-custom badge-dark">Scholar Paper</span>'
pub_date:       "2026"

abstract: >-
  In recent years, end-to-end solutions for Weakly Supervised Semantic Segmentation (WSSS) with image-level labels have been developed rapidly. Previous end-to-end methods usually rely on segmentation branches or decoders to predict segmentation masks, bringing additional parameter numbers and consumption time. In this paper, we propose a decoder-free Representation Mutual Learning (RML) framework to directly predict segmentation masks, which leverages collaborative learning and mutual teaching among multi-level feature representations to improve segmentation performance. Our RML is a straightforward and efficient end-to-end WSSS framework, which incorporates the instance-level, feature-level and pixel-level representation mutual learning strategies to improve segmentation quality. To enhance the Class Activation Map (CAM) representations, we propose a CAM-driven Instance-leave Mutual Learning strategy that preserves the equivariance of CAMs and expands the distance between different classes of semantic prototypes. Besides, we design a Multi-scale Feature-leave Mutual Learning strategy, which can align aggregated contextual representations and facilitate the representation capability of contextual representations. Furthermore, we also provide an Affinity-aware Pixel-level Mutual Learning strategy to learn semantic affinity representations. Experiments validate that our RML yields a significant performance improvement over recent end-to-end methods on the Pascal VOC 2012 dataset and the MS COCO 2014 dataset. The release code is available at supplementary material.

cover:          assets/images/covers/default.png
authors:
  - Rongtao Xu
  - Changwei Wang
  - Shibiao Xu
  - Weiliang Meng
  - Xiaopeng Zhang
links:
  Paper: https://openreview.net/forum?id=BnznzofWMi
---
