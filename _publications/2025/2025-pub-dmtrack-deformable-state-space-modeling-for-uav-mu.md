---
title:          "DMTrack: Deformable State-Space Modeling for UAV Multi-Object Tracking with Kalman Fusion and Uncertainty-Aware Association"
date:           2025-01-01 00:01:00 +0800
selected:       false
pub:            "arXiv preprint arXiv:2510.17860"
pub_last:       ' <span class="badge badge-pill badge-custom badge-dark">Scholar Paper</span>'
pub_date:       "2025"

abstract: >-
  Multi-object tracking (MOT) from unmanned aerial vehicles (UAVs) presents unique challenges due to unpredictable object motion, frequent occlusions, and limited appearance cues inherent to aerial viewpoints. These issues are further exacerbated by abrupt UAV movements, leading to unreliable trajectory estimation and identity switches. Conventional motion models, such as Kalman filters or static sequence encoders, often fall short in capturing both linear and non-linear dynamics under such conditions. To tackle these limitations, we propose DMTrack, a deformable motion tracking framework tailored for UAV-based MOT. Our DMTrack introduces three key components: DeformMamba, a deformable state-space predictor that dynamically aggregates historical motion states for adaptive trajectory modeling; MotionGate, a lightweight gating module that fuses Kalman and Mamba predictions based on motion context and uncertainty; and an uncertainty-aware association strategy that enhances identity preservation by aligning motion trends with prediction confidence. Extensive experiments on the VisDrone-MOT and UAVDT benchmarks demonstrate that our DMTrack achieves state-of-the-art performance in identity consistency and tracking accuracy, particularly under high-speed and non-linear motion. Importantly, our method operates without appearance models and maintains competitive efficiency, highlighting its practicality for robust UAV-based tracking.

cover:          assets/images/covers/default.png
authors:
  - Zenghuang Fu
  - Xiaofeng Han
  - Mingda Jia
  - Qi Zeng
  - Muyang Zahng
  - Changwei Wang
  - Weiliang Meng
  - Xiaopeng Zhang
links:
  Paper: https://arxiv.org/abs/2510.17860
---
