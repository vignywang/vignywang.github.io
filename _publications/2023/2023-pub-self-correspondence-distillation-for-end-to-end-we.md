---
title:          "Self correspondence distillation for end-to-end weakly-supervised semantic segmentation"
date:           2023-02-15 00:01:00 +0800
selected:       false
pub:            "Proceedings of the AAAI Conference on Artificial Intelligence"
pub_last:       ' <span class="badge badge-pill badge-custom badge-dark">Scholar Paper</span>'
pub_date:       "2023"

abstract: >-
  Efficiently training accurate deep models for weakly supervised semantic segmentation (WSSS) with image-level labels is challenging and important. Recently, end-to-end WSSS methods have become the focus of research due to their high training efficiency. However, current methods suffer from insufficient extraction of comprehensive semantic information, resulting in low-quality pseudo-labels and sub-optimal solutions for end-to-end WSSS. To this end, we propose a simple and novel Self Correspondence Distillation (SCD) method to refine pseudo-labels without introducing external supervision. Our SCD enables the network to utilize feature correspondence derived from itself as a distillation target, which can enhance the network's feature learning process by complementing semantic information. In addition, to further improve the segmentation accuracy, we design a Variation-aware Refine Module to enhance the local consistency of pseudo-labels by computing pixel-level variation. Finally, we present an efficient end-to-end Transformer-based framework (TSCD) via SCD and Variation-aware Refine Module for the accurate WSSS task. Extensive experiments on the PASCAL VOC 2012 and MS COCO 2014 datasets demonstrate that our method significantly outperforms other state-of-the-art methods. Our code is available at https://github. com/Rongtao-Xu/RepresentationLearning/tree/main/SCD-AAAI2023.

cover:          assets/images/covers/default.png
authors:
  - Rongtao Xu
  - Changwei Wang
  - Jiaxi Sun
  - Shibiao Xu
  - Weiliang Meng
  - Xiaopeng Zhang
links:
  Paper: https://ojs.aaai.org/index.php/AAAI/article/view/25408
---
