---
title: "Provable Convergence of Adaptive Low-Rank Optimizers"
authors: ["Kenji Arata", "Sofia Marchetti", "Daniel Owusu"]
venue: "International Conference on Machine Learning 2024"
venue_type: "conference"
year: 2024
archive_ref: "ART-2023-052"
revision: "v1"
permalink: "/publications/adaptive-low-rank-optimizers/"
---
Low-rank adaptive optimizers reduce the memory cost of training large models by projecting gradients onto a learned subspace, yet their convergence guarantees have been established only for fixed subspaces. We analyze a family of optimizers that periodically refresh the projection basis and show that, under a relaxed smoothness condition, they converge to stationary points at the same rate as full-rank adaptive methods, up to logarithmic factors in the rank. The analysis yields a practical rule for the refresh interval, which we validate on language-model pre-training and on a suite of vision transformers, matching full-rank baselines while using 41 percent less optimizer state memory.
