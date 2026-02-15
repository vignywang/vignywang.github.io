---
title:          "Federated Balanced Learning"
date:           2026-01-01 00:01:00 +0800
selected:       false
pub:            "arXiv preprint arXiv:2601.14042"
pub_last:       ' <span class="badge badge-pill badge-custom badge-dark">Scholar Paper</span>'
pub_date:       "2026"

abstract: >-
  Federated learning is a paradigm of joint learning in which clients collaborate by sharing model parameters instead of data. However, in the non-iid setting, the global model experiences client drift, which can seriously affect the final performance of the model. Previous methods tend to correct the global model that has already deviated based on the loss function or gradient, overlooking the impact of the client samples. In this paper, we rethink the role of the client side and propose Federated Balanced Learning, i.e., FBL, to prevent this issue from the beginning through sample balance on the client side. Technically, FBL allows unbalanced data on the client side to achieve sample balance through knowledge filling and knowledge sampling using edge-side generation models, under the limitation of a fixed number of data samples on clients. Furthermore, we design a Knowledge Alignment Strategy to bridge the gap between synthetic and real data, and a Knowledge Drop Strategy to regularize our method. Meanwhile, we scale our method to real and complex scenarios, allowing different clients to adopt various methods, and extend our framework to further improve performance. Numerous experiments show that our method outperforms state-of-the-art baselines. The code is released upon acceptance.

cover:          assets/images/covers/default.png
authors:
  - Jiaze Li
  - Haoran Xu
  - Wanyi Wu
  - Changwei Wang
  - Shuaiguang Li
  - Jianzhong Ju
  - Zhenbo Luo
  - Jian Luan
  - Youyang Qu
  - Longxiang Gao
  - Xudong Yang
  - Lumin Xing
links:
  Paper: https://arxiv.org/abs/2601.14042
---
