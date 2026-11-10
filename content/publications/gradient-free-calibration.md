---
title: "Gradient-Free Calibration of Coarse-Grained Molecular Models"
authors: ["Elif Karaca", "Benedikt Sturm", "Priya Nair"]
venue: "International Conference on Learning Representations 2025"
venue_type: "conference"
year: 2025
archive_ref: "ART-2024-041"
revision: "v1"
permalink: "/publications/gradient-free-calibration/"
---
Coarse-grained molecular models require calibrating interaction parameters against reference observables, and gradient-based calibration is expensive because every parameter perturbation demands a fresh simulation. We propose a derivative-free calibration scheme that combines Bayesian quadrature with an active-learning acquisition over a low-dimensional summary space. On three polymer systems, the method reaches reference densities and diffusion coefficients in fewer than forty simulation batches, roughly one third of the cost of finite-difference calibration, while producing calibrated uncertainty estimates that identify the remaining model discrepancy.
