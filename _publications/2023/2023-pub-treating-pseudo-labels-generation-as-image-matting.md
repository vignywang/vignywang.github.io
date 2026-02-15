---
title:          "Treating pseudo-labels generation as image matting for weakly supervised semantic segmentation"
date:           2023-02-15 00:01:00 +0800
selected:       false
pub:            "Unknown Venue"
pub_last:       ' <span class="badge badge-pill badge-custom badge-dark">Scholar Paper</span>'
pub_date:       "2023"

abstract: >-
  Generating accurate pseudo-labels under the supervision of image categories is a crucial step in Weakly Supervised Semantic Segmentation (WSSS). In this work, we propose a Mat-Label pipeline that provides a fresh way to treat WSSS pseudo-labels generation as an image matting task. By taking a trimap as input which specifies the foreground, background and unknown regions, the image matting task outputs an object mask with fine edges. The intuition behind our Mat-Label is that generating trimap is much easier than generating pseudo-labels directly under weakly supervised setting. Although current CAM-based methods are off-the-shelf solutions for generating a trimap, they suffer from cross-category and foreground-background pixel prediction confusion. To solve this problem, we develop a Double Decoupled Class Activation Map (D2CAM) for Mat-Label to generate a high-quality trimap. By drawing on the idea of metric learning, we explicitly model class activation map with category decoupling and foreground-background decoupling. We also design two simple yet effective refinement constraints for D2CAM to stabilize optimization and eliminate non-exclusive activation. Extensive experiments validate that our Mat-Label achieves substantial and consistent performance gains compared to current state-of-the-art WSSS approaches. Our code is available at supplementary material.

cover:          assets/images/covers/default.png
authors:
  - Changwei Wang
  - Rongtao Xu
  - Shibiao Xu
  - Weiliang Meng
  - Xiaopeng Zhang
links:
  Paper: http://openaccess.thecvf.com/content/ICCV2023/html/Wang_Treating_Pseudo-labels_Generation_as_Image_Matting_for_Weakly_Supervised_Semantic_ICCV_2023_paper.html
---
