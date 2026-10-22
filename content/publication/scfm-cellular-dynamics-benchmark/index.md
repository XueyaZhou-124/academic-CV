---
title: 'Benchmarking zero-shot single-cell foundation model embeddings for cellular dynamics reconstruction'

authors:
  - admin
  - Zihan Wang
  - Yue Ling
  - Qinxue Tian
  - Zhenyi Zhang
  - Yongge Li
  - Luonan Chen
  - Peijie Zhou

date: '2026-03-12T00:00:00Z'
doi: '10.64898/2026.03.10.710748'

publishDate: '2026-03-12T00:00:00Z'

publication_types: ['article']

publication: '*bioRxiv*'
publication_short: ''

abstract: Reconstructing cellular trajectories from time-resolved single-cell transcriptomics is fundamental to understanding processes from embryonic development to cancer progression. While single-cell foundation models (scFMs) promise universal biological representations through large-scale pretraining, their capacity to capture the non-linear dynamics governing cell-fate decisions remains uncharacterized. Here we systematically benchmark multiple scFMs across challenging biomedical scenarios involving branching lineages and continuous state transitions. By coupling zero-shot scFM embeddings with dynamic optimal transport, we evaluated their performance against a traditional highly variable gene (HVG) baseline in backtracking progenitor states, interpolating transition intermediates, and extrapolating future fates. We find that zero-shot scFM embeddings underperform the HVG baseline across diverse biological systems, particularly in recovering the distributional complexity of unobserved cells. Mechanistic analysis reveals that current scFM architectures tend to over-compress subtle temporal signals, causing an artificial "linearization" of branched biological structures that may obscure critical divergence points in disease progression. Our findings suggest that while scFMs provide unified cell-state views, the HVG baseline remains more robust for trajectory inference, identifying a fundamental "temporal-compression" bottleneck that must be addressed to develop next-generation, dynamics-aware foundation models.

summary: A benchmark of zero-shot single-cell foundation model embeddings for reconstructing cellular dynamics with dynamic optimal transport.

tags:
  - Single-cell
  - Foundation Models
  - Optimal Transport

featured: false

url_pdf: 'https://www.biorxiv.org/content/10.64898/2026.03.10.710748v1.full.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://doi.org/10.64898/2026.03.10.710748'
url_video: ''

projects: []
slides: ''
---
