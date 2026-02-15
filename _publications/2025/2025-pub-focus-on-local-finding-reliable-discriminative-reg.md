---
title:          "Focus on local: Finding reliable discriminative regions for visual place recognition"
date:           2025-01-01 00:01:00 +0800
selected:       false
pub:            "Proceedings of the AAAI Conference on Artificial Intelligence"
pub_last:       ' <span class="badge badge-pill badge-custom badge-dark">Scholar Paper</span>'
pub_date:       "2025"

abstract: >-
  Visual Place Recognition (VPR) is aimed at predicting the location of a query image by referencing a database of geotagged images. For VPR task, often fewer discriminative local regions in an image produce important effects while mundane background regions do not contribute or even cause perceptual aliasing because of easy overlap. However, existing methods lack precisely modeling and full exploitation of these discriminative regions. In addition, the lack of pixel-level correspondence supervision in the VPR dataset hinders further improvement of the local feature matching capability in the re-ranking stage. In this paper, we propose the Focus on Local (FoL) approach to stimulate the performance of image retrieval and re-ranking in VPR simultaneously by mining and exploiting reliable discriminative local regions in images and introducing pseudo-correlation supervision. First, we design two losses, Extraction-Aggregation Spatial Alignment Loss (SAL) and Foreground-Background Contrast Enhancement Loss (CEL), to explicitly model reliable discriminative local regions and use them to guide the generation of global representations and efficient re-ranking. Second, we introduce a weakly-supervised local feature training strategy based on pseudo-correspondences obtained from aggregating global features to alleviate the lack of local correspondences ground truth for the VPR task. Third, we suggest an efficient re-ranking pipeline that is efficiently and precisely based on discriminative region guidance. Finally, experimental results show that our FoL achieves the state-of-the-art on multiple VPR benchmarks in both image retrieval and re …

cover:          assets/images/covers/default.png
authors:
  - Changwei Wang
  - Shunpeng Chen
  - Yukun Song
  - Rongtao Xu
  - Zherui Zhang
  - Jiguang Zhang
  - Haoran Yang
  - Yu Zhang
  - Kexue Fu
  - Shide Du
  - Zhiwei Xu
  - Longxiang Gao
  - Li Guo
  - Shibiao Xu
links:
  Paper: https://ojs.aaai.org/index.php/AAAI/article/view/32811
---
