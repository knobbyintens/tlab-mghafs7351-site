---
title: "Spectral Sparsification for Graph Neural Message Passing"
authors: ["Ana Lucia Ferreira", "Tomas Rivera", "Wei-Lun Hsu"]
venue: "Conference on Neural Information Processing Systems 2024"
venue_type: "conference"
year: 2024
archive_ref: "ART-2023-096"
revision: "v1"
permalink: "/publications/spectral-graph-sparsification/"
---
Neighborhood aggregation dominates the cost of message passing on large graphs, and spectral methods can sparsify this computation by retaining only a subset of edges. We give a spectral sparsification procedure tailored to graph neural networks that preserves the top eigenvalues of the normalized adjacency with high probability while removing a constant fraction of edges. The resulting sparsified graphs train two-layer networks with 38 percent fewer aggregation operations and match dense accuracy on five node-classification benchmarks, including heterophilous graphs where degree-based sparsification fails.
