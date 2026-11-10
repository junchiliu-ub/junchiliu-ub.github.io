---
title: "Efficient, Adaptive Near-Field Beam Training based on Posterior Sampling"
collection: publications
authors:
  - Junchi Liu
  - Zijun Wang
  - Rui Zhang
category: conferences
status: published
permalink: /publication/2026-10-12-efficient-adaptive-near-field-beam-training-posterior-sampling
redirect_from:
  - /publication/2026-03-10-efficient-adaptive-near-field-beam-training-linear-bandit
excerpt: 'A linear bandit-based near-field beam training framework under multipath channels with up to 90% pilot overhead reduction and over 2 dB SNR gain.'
date: 2026-10-12
venue: 'IEEE MILCOM Workshop'
paperurl: 'https://arxiv.org/abs/2603.09893'
citation: 'Junchi Liu, Zijun Wang, Rui Zhang. (2026). &quot;Efficient, Adaptive Near-Field Beam Training based on Posterior Sampling.&quot; <i>IEEE MILCOM Workshop</i>.'
---

**Abstract:**  
This letter proposes a linear bandit-based beam training framework for near-field communication under multi-path channels. By leveraging Thompson Sampling (TS), the framework adaptively balances exploration and exploitation to maximize cumulative beamforming gain under limited pilot overhead. To ensure data-efficient learning, we incorporate a correlated Gaussian prior in the DFT domain, using a Gaussian kernel to capture spatial correlations and near-field energy leakage. We develop three TS strategies: codebook-constrained search for rapid convergence via structural regularization, continuous-space search to achieve near-optimal performance, and a two-stage hybrid refinement scheme that balances convergence speed and estimation accuracy. Simulation results show that the proposed framework reduces pilot overhead by up to 90% while achieving more than a 2dB SNR gain over baselines in multipath environments. Furthermore, the continuous-space search is shown to be asymptotically optimal, approaching the full-CSI bound when the pilot overhead is unconstrained.
