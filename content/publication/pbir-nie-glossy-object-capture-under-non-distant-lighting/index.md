---
title: "PBIR-NIE: Glossy Object Capture under Non-Distant Lighting"
publication_types:
  - "3"
authors:
  - admin
  - Fujun Luan
  - Miloš Hašan
  - Kai Zhang
  - Sai Bi
  - Zexiang Xu
  - Iliyan Georgiev
  - Shuang Zhao
doi: " https://doi.org/10.48550/arXiv.2408.06878"
abstract: Glossy objects present a significant challenge for 3D reconstruction
  from multi-view input images under natural lighting. In this paper, we
  introduce PBIR-NIE, an inverse rendering framework designed to holistically
  capture the geometry, material attributes, and surrounding illumination of
  such objects. We propose a novel parallax-aware non-distant environment map as
  a lightweight and efficient lighting representation, accurately modeling the
  near-field background of the scene, which is commonly encountered in
  real-world capture setups. This feature allows our framework to accommodate
  complex parallax effects beyond the capabilities of standard infinite-distance
  environment maps. Our method optimizes an underlying signed distance field
  (SDF) through physics-based differentiable rendering, seamlessly connecting
  surface gradients between a triangle mesh and the SDF via neural implicit
  evolution (NIE). To address the intricacies of highly glossy BRDFs in
  differentiable rendering, we integrate the antithetic sampling algorithm to
  mitigate variance in the Monte Carlo gradient estimator. Consequently, our
  framework exhibits robust capabilities in handling glossy object
  reconstruction, showcasing superior quality in geometry, relighting, and
  material estimation.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2024-09-28T20:00:16.034Z
---
