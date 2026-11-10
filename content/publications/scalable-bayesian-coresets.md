---
title: "Scalable Bayesian Coresets for Variational Inference"
authors: ["Helena Vogt", "Arjun Mehta"]
venue: "Journal of Computational and Graphical Statistics"
venue_type: "journal"
year: 2024
archive_ref: "ART-2023-088"
revision: "v1"
permalink: "/publications/scalable-bayesian-coresets/"
---
Bayesian coresets compress a large dataset into a weighted subset that preserves posterior expectations, but constructing them requires repeated passes over the full data. We present a streaming coreset algorithm whose memory footprint is independent of the dataset size and prove that its posterior error decays at the same rate as the batch construction. On three large-scale regression and classification problems the streaming coresets reach the accuracy of full-data variational inference with two percent of the observations, and we provide practical guidance for choosing the sensitivity bound.
