---
title:          "CurriFlow: Curriculum-Guided Depth Fusion with Optical Flow-Based Temporal Alignment for 3D Semantic Scene Completion"
date:           2025-01-01 00:01:00 +0800
selected:       false
pub:            "arXiv preprint arXiv:2510.12362"
pub_last:       ' <span class="badge badge-pill badge-custom badge-dark">Scholar Paper</span>'
pub_date:       "2025"

abstract: >-
  Semantic Scene Completion (SSC) aims to infer complete 3D geometry and semantics from monocular images, serving as a crucial capability for camera-based perception in autonomous driving. However, existing SSC methods relying on temporal stacking or depth projection often lack explicit motion reasoning and struggle with occlusions and noisy depth supervision. We propose CurriFlow, a novel semantic occupancy prediction framework that integrates optical flow-based temporal alignment with curriculum-guided depth fusion. CurriFlow employs a multi-level fusion strategy to align segmentation, visual, and depth features across frames using pre-trained optical flow, thereby improving temporal consistency and dynamic object understanding. To enhance geometric robustness, a curriculum learning mechanism progressively transitions from sparse yet accurate LiDAR depth to dense but noisy stereo depth during training, ensuring stable optimization and seamless adaptation to real-world deployment. Furthermore, semantic priors from the Segment Anything Model (SAM) provide category-agnostic supervision, strengthening voxel-level semantic learning and spatial consistency. Experiments on the SemanticKITTI benchmark demonstrate that CurriFlow achieves state-of-the-art performance with a mean IoU of 16.9, validating the effectiveness of our motion-guided and curriculum-aware design for camera-based 3D semantic scene completion.

cover:          assets/images/covers/default.png
authors:
  - Jinzhou Lin
  - Jie Zhou
  - Wenhao Xu
  - Rongtao Xu
  - Changwei Wang
  - Shunpeng Chen
  - Kexue Fu
  - Yihua Shao
  - Li Guo
  - Shibiao Xu
links:
  Paper: https://arxiv.org/abs/2510.12362
---
