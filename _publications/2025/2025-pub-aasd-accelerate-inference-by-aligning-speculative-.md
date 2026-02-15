---
title:          "AASD: Accelerate Inference by Aligning Speculative Decoding in Multimodal Large Language Models"
date:           2025-01-01 00:01:00 +0800
selected:       false
pub:            "Unknown Venue"
pub_last:       ' <span class="badge badge-pill badge-custom badge-dark">Scholar Paper</span>'
pub_date:       "2025"

abstract: >-
  Multimodal Large Language Models (MLLMs) have achieved notable success in visual instruction tuning, yet their inference is time-consuming due to the auto-regressive decoding of Large Language Model (LLM) backbone. Traditional methods for accelerating inference, including model compression and migration from language model acceleration, often compromise output quality or face challenges in effectively integrating multimodal features. To address these issues, we propose AASD, a novel framework for Accelerating inference with refined KV Cache and Aligning speculative decoding in MLLMs. Our approach leverages the target model’s cached KeyValue (KV) pairs to extract vital information for generating draft tokens, enabling efficient speculative decoding. To reduce the computational burden associated with long multimodal token sequences, we introduce a KV Projector to compress the KV Cache while …

cover:          assets/images/covers/default.png
authors:
  - Chaoqun Yang
  - Ran Chen
  - Muyang Zhang
  - Weiguang Pang
  - Yuzhi Chen
  - Rongtao Xu
  - Kexue Fu
  - Changwei Wang
  - Longxiang Gao
links:
  Paper: https://ieeexplore.ieee.org/abstract/document/11132960/
---
