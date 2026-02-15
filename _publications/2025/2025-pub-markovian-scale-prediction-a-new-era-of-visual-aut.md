---
title:          "Markovian Scale Prediction: A New Era of Visual Autoregressive Generation"
date:           2025-01-01 00:01:00 +0800
selected:       false
pub:            "arXiv preprint arXiv:2511.23334"
pub_last:       ' <span class="badge badge-pill badge-custom badge-dark">Scholar Paper</span>'
pub_date:       "2025"

abstract: >-
  Visual AutoRegressive modeling (VAR) based on next-scale prediction has revitalized autoregressive visual generation. Although its full-context dependency, i.e., modeling all previous scales for next-scale prediction, facilitates more stable and comprehensive representation learning by leveraging complete information flow, the resulting computational inefficiency and substantial overhead severely hinder VAR's practicality and scalability. This motivates us to develop a new VAR model with better performance and efficiency without full-context dependency. To address this, we reformulate VAR as a non-full-context Markov process, proposing Markov-VAR. It is achieved via Markovian Scale Prediction: we treat each scale as a Markov state and introduce a sliding window that compresses certain previous scales into a compact history vector to compensate for historical information loss owing to non-full-context dependency. Integrating the history vector with the Markov state yields a representative dynamic state that evolves under a Markov process. Extensive experiments demonstrate that Markov-VAR is extremely simple yet highly effective: Compared to VAR on ImageNet, Markov-VAR reduces FID by 10.5% (256  256) and decreases peak memory consumption by 83.8% (1024  1024). We believe that Markov-VAR can serve as a foundation for future research on visual autoregressive generation and other downstream tasks.

cover:          assets/images/covers/default.png
authors:
  - Yu Zhang
  - Jingyi Liu
  - Yiwei Shi
  - Qi Zhang
  - Duoqian Miao
  - Changwei Wang
  - Longbing Cao
links:
  Paper: https://arxiv.org/abs/2511.23334
---
