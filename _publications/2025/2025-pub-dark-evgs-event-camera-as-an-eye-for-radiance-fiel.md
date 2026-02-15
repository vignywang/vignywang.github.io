---
title:          "Dark-EvGS: Event Camera as an Eye for Radiance Field in the Dark"
date:           2025-01-01 00:01:00 +0800
selected:       false
pub:            "arXiv preprint arXiv:2507.11931"
pub_last:       ' <span class="badge badge-pill badge-custom badge-dark">Scholar Paper</span>'
pub_date:       "2025"

abstract: >-
  In low-light environments, conventional cameras often struggle to capture clear multi-view images of objects due to dynamic range limitations and motion blur caused by long exposure. Event cameras, with their high-dynamic range and high-speed properties, have the potential to mitigate these issues. Additionally, 3D Gaussian Splatting (GS) enables radiance field reconstruction, facilitating bright frame synthesis from multiple viewpoints in low-light conditions. However, naively using an event-assisted 3D GS approach still faced challenges because, in low light, events are noisy, frames lack quality, and the color tone may be inconsistent. To address these issues, we propose Dark-EvGS, the first event-assisted 3D GS framework that enables the reconstruction of bright frames from arbitrary viewpoints along the camera trajectory. Triplet-level supervision is proposed to gain holistic knowledge, granular details, and sharp scene rendering. The color tone matching block is proposed to guarantee the color consistency of the rendered frames. Furthermore, we introduce the first real-captured dataset for the event-guided bright frame synthesis task via 3D GS-based radiance field reconstruction. Experiments demonstrate that our method achieves better results than existing methods, conquering radiance field reconstruction under challenging low-light conditions. The code and sample data are included in the supplementary material.

cover:          assets/images/covers/default.png
authors:
  - Jingqian Wu
  - Peiqi Duan
  - Zongqiang Wang
  - Changwei Wang
  - Boxin Shi
  - Edmund Y Lam
links:
  Paper: https://arxiv.org/abs/2507.11931
---
