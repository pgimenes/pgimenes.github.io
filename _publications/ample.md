---
title: "AMPLE: Event-Driven Accelerator for Mixed-Precision Inference of Graph Neural Networks"
collection: publications
category: preprints
permalink: /publication/ample
date: 2024-10-14
venue: 'Arxiv'
paperurl: 'https://pgimenes.github.io/files/ample.pdf'
---

<!-- [Arxiv link](https://arxiv.org/abs/2410.06722) -->

Graph Neural Networks (GNNs) have recently gained attention due to their performance on non-Euclidean data. The use of custom hardware architectures proves particularly beneficial for GNNs due to their irregular memory access patterns, resulting from the sparse structure of graphs. However, existing FPGA accelerators are limited by their double buffering mechanism, which doesn’t account for the irregular node distribution in typical graph datasets. To address this, we introduce AMPLE (Accelerated Message Passing Logic Engine), an FPGA accelerator leveraging a new event-driven programming flow. We develop a mixed-arithmetic architecture, enabling GNN inference to be quantized at a node-level granularity. Finally, prefetcher for data and instructions is implemented to optimize off-chip memory access and maximize node parallelism. Evaluation on citation and social media graph datasets ranging from 2K to 700K nodes showed a mean speedup of 243× and 7.2× against CPU and GPU counterparts, respectively.