---
title:          "Mim-hd: Making smaller masked autoencoder better with efficient distillation"
date:           2024-02-15 00:01:00 +0800
selected:       false
pub:            "Unknown Venue"
pub_last:       ' <span class="badge badge-pill badge-custom badge-dark">Scholar Paper</span>'
pub_date:       "2024"

abstract: >-
  Self-supervised learning and knowledge distillation intersect to achieve exceptional performance on downstream tasks across diverse network capacities. This paper introduces MIM-HD, which implements enhancements for masked image modeling (MIM) distillation, in two key aspects. First, a vision transformer head-level relation adaptive distillation approach is proposed, allowing the student to dynamically draw multi-source knowledge from the teacher based on its evolving state, compatible with scenarios where teacherstudent transformer block head count differs. Second, to address the overemphasis on the encoder and neglect of the decoder role in maintaining representation consistency in previous MIM distillations, a dual-view decoding strategy for latent visual representations is introduced, reusing the teacher’s decoder to alleviate MIM burdens on smaller networks. MIM-HD effectiveness is demonstrated through evaluations on ADE20K (mIoU) and ImageNet-1K (Acc), achieving+ 1.4% and+ 0.5% improved performance, respectively, compared to state-of-the-art methods, with substantial advantages on smaller pretraining datasets. Moreover, MIM-HD achieves superior efficiency, reducing pre-training epochs from 300 to 100.

cover:          assets/images/covers/default.png
authors:
  - Zherui Zhang
  - Changwei Wang
  - Rongtao Xu
  - Wenhao Xu
  - Shibiao Xu
  - Li Guo
  - Jiguang Zhang
  - Xiaoqiang Teng
  - Wenbo Xu
links:
  Paper: https://pdfs.semanticscholar.org/66bf/24f7034e89251bc5536205bc4e7a6ef45db4.pdf
---
