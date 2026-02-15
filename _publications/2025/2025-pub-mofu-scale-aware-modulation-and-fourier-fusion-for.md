---
title:          "MoFu: Scale-Aware Modulation and Fourier Fusion for Multi-Subject Video Generation"
date:           2025-01-01 00:01:00 +0800
selected:       false
pub:            "arXiv preprint arXiv:2512.22310"
pub_last:       ' <span class="badge badge-pill badge-custom badge-dark">Scholar Paper</span>'
pub_date:       "2025"

abstract: >-
  Multi-subject video generation aims to synthesize videos from textual prompts and multiple reference images, ensuring that each subject preserves natural scale and visual fidelity. However, current methods face two challenges: scale inconsistency, where variations in subject size lead to unnatural generation, and permutation sensitivity, where the order of reference inputs causes subject distortion. In this paper, we propose MoFu, a unified framework that tackles both challenges. For scale inconsistency, we introduce Scale-Aware Modulation (SMO), an LLM-guided module that extracts implicit scale cues from the prompt and modulates features to ensure consistent subject sizes. To address permutation sensitivity, we present a simple yet effective Fourier Fusion strategy that processes the frequency information of reference features via the Fast Fourier Transform to produce a unified representation. Besides, we design a Scale-Permutation Stability Loss to jointly encourage scale-consistent and permutation-invariant generation. To further evaluate these challenges, we establish a dedicated benchmark with controlled variations in subject scale and reference permutation. Extensive experiments demonstrate that MoFu significantly outperforms existing methods in preserving natural scale, subject fidelity, and overall visual quality.

cover:          assets/images/covers/default.png
authors:
  - Run Ling
  - Ke Cao
  - Jian Lu
  - Ao Ma
  - Haowei Liu
  - Runze He
  - Changwei Wang
  - Rongtao Xu
  - Yihua Shao
  - Zhanjie Zhang
  - Peng Wu
  - Guibing Guo
  - Wei Feng
  - Zheng Zhang
  - Jingjing Lv
  - Junjie Shen
  - Ching Law
  - Xingwei Wang
links:
  Paper: https://arxiv.org/abs/2512.22310
---
