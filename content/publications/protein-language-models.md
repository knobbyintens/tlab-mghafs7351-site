---
title: "Structure-Aware Protein Language Models"
authors: ["Mateo Contreras", "Sara Lindahl", "Viktor Ivanov"]
venue: "International Conference on Learning Representations 2025"
venue_type: "conference"
year: 2025
archive_ref: "ART-2024-079"
revision: "v1"
permalink: "/publications/protein-language-models/"
---
Protein language models trained on sequences alone capture evolutionary statistics but remain blind to geometric constraints that determine function. We inject backbone geometry as a relative-position bias inside a masked language model and train on structures predicted at inference time. The resulting model improves mutation-effect prediction by 9 percent over strong sequence baselines on a held-out assay suite, and its learned representations cluster known protein families without supervision, indicating that geometry adds information beyond evolutionary covariation.
