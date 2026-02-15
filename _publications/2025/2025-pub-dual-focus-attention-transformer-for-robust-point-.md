---
title:          "Dual Focus-Attention Transformer for Robust Point Cloud Registration"
date:           2025-01-01 00:01:00 +0800
selected:       false
pub:            "Unknown Venue"
pub_last:       ' <span class="badge badge-pill badge-custom badge-dark">Scholar Paper</span>'
pub_date:       "2025"

abstract: >-
  Recently, coarse-to-fine methods for point cloud registration have achieved great success, but few works deeply explore the impact of feature interaction at both coarse and fine scales. By visualizing attention scores and correspondences, we find that existing methods fail to achieve effective feature aggregation at the two scales during the feature interaction. To tackle this issue, we propose a Dual Focus-Attention Transformer framework, which only focuses on points relevant to the current point for feature interaction, avoiding interactions with irrelevant points. For the coarse scale, we design a superpoint focus-attention transformer guided by sparse keypoints, which are selected from the neighborhood of superpoints. For the fine scale, we only perform feature interaction between the point sets that belong to the same superpoint. Experiments show that our method achieve the state-of-the-art performance on three standard benchmarks. The code and pre-trained models will be available at Github.

cover:          assets/images/covers/default.png
authors:
  - Kexue Fu
  - Mingzhi Yuan
  - Changwei Wang
  - Weiguang Pang
  - Jing Chi
  - Manning Wang
  - Longxiang Gao
links:
  Paper: https://openaccess.thecvf.com/content/CVPR2025/html/Fu_Dual_Focus-Attention_Transformer_for_Robust_Point_Cloud_Registration_CVPR_2025_paper.html
---
