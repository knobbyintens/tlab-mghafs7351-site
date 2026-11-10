---
title: "Thermodynamic Consistency of Learned Free-Energy Surrogates"
authors: ["Maya Okafor", "Rasmus Lindqvist", "Sriram Bhattacharya"]
venue: "Journal of Chemical Physics"
venue_type: "journal"
year: 2024
archive_ref: "ART-2023-017"
revision: "v2"
permalink: "/publications/free-energy-surrogates/"
---
Learned free-energy surrogates promise to accelerate molecular simulations, but their thermodynamic consistency has been difficult to certify. We present a calibrated surrogate architecture that enforces a Gibbs-Duhem constraint during training and evaluate it on five organic liquids across microsecond trajectories. The constrained surrogate reproduces pair-correlation functions within one percent error and holds mean potential-energy drift below three kilojoules per mole, an order of magnitude lower than unconstrained baselines. Ablation experiments isolate the entropy correction as the source of the improvement, and the method transfers to two unseen solvents without retraining.
