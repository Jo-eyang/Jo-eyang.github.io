---
layout: page
title: "OMG-VLM: One Model, Many Graphs"
description: A single vision-language model that learns over text-, image-, and multimodal-attributed graphs.
period: Mar 2025 – May 2026
advisor: Prof. Qiaoyu Tan
venue: EMNLP 2026
category: research
importance: 2
links:
  - name: Paper
    url: https://arxiv.org/abs/2607.19128
  - name: Code
    url: https://github.com/Jo-eyang/OMG-VLM
---

- Introduced **unified attributed graph learning under heterogeneous modality schemas**, enabling a single model to operate across text-attributed, image-attributed, and multimodal graphs.
- Proposed **OMG-VLM**, a unified generative framework that uses a pretrained VLM as a shared backbone and incorporates graph neighborhoods through target-aware textual aggregation and graph-aware visual representation learning within the VLM's native embedding space — no separate modality-specific architectures.
- Across nine graph benchmarks and multiple GNN-, LLM-, and multimodal baselines, OMG-VLM outperforms the strongest baselines by **3.38 points** on four in-domain graphs and **15.09 points** on five unseen graphs, with gains of up to **20.15 points** under cross-graph transfer.
