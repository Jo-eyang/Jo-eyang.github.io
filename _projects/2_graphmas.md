---
layout: page
title: "GraphMAS: Multi-Agent Coordination for Graph Learning"
description: When do specialized LLM agents help on graphs, and how should they coordinate?
period: May 2026 – Sep 2026
advisor: Prof. Qiaoyu Tan
venue: Under review at ICLR 2027
category: research
importance: 1
links:
  - name: Paper
    url: https://arxiv.org/abs/2609.39777
---

- Proposed **GraphMAS**, a systematic framework for multi-agent graph learning, studying when specialized LLM agents benefit from complementary structural and semantic graph perspectives and how their coordination should be designed.
- Designed a unified benchmark spanning **four coordination paradigms** and **seven representative methods** across node classification and link prediction on seven graphs. Gains arise primarily from specialist complementarity and structured reasoning decomposition, not from more communication alone.
- Developed **instance-adaptive routing**, the strongest accuracy–efficiency trade-off among training-free methods, and further optimized the coordination policy with **PPO** over frozen specialists — improving average LP accuracy from 79.6% to 87.3% and NC accuracy from 68.4% to 72.4%, with transfer to held-out graphs.
