---
title: 'Evidential DualU-Net: Single-Pass Uncertainty for Cell Instance Segmentation'
abstract: Accurate and trustworthy cell instance segmentation requires models that
  not only detect and classify nuclei but also communicate how much evidence supports
  each prediction. DualU-Net is a fast and effective two-head multi-task architecture
  for this problem, but—like most deterministic models—it provides no principled uncertainty
  estimates. We introduce Evidential DualU-Net, the first evidential framework for
  multi-task cell instance segmentation.Its segmentation head predicts Dirichlet concentration
  parameters, enabling single-pass, closed-form aleatoric, epistemic, and vacuity
  uncertainties at the pixel level, with instance-level quantities obtained via size-invariant
  pooling of pixel evidence. The centroid decoder is complemented with two lightweight
  geometric uncertainty cues that quantify localisation reliability without auxiliary
  models or sampling. Together, these evidential and geometric measures expose complementary
  failure modes and allow principled filtering of low-confidence nuclei. Across multi-tissue
  and multi-stain datasets, Evidential DualU-Net matches or surpasses deep ensembles
  and MC Dropout in error separation at a fraction of the cost, maintains or improves
  calibration over deterministic baselines, and generalises across datasets without
  retuning. This work provides an interpretable and computationally practical uncertainty
  formulation for digital pathology.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: anglada-rotger26a
month: 0
tex_title: 'Evidential DualU-Net: Single-Pass Uncertainty for Cell Instance Segmentation'
firstpage: 3103
lastpage: 3130
page: 3103-3130
order: 3103
cycles: false
bibtex_author: Anglada-Rotger, David and Marques, Ferran and Pard{\`a}s, Montse
author:
- given: David
  family: Anglada-Rotger
- given: Ferran
  family: Marques
- given: Montse
  family: Pardàs
date: 2026-05-05
address:
container-title: Proceedings of The 9th International Conference on Medical Imaging
  with Deep Learning
volume: '315'
genre: inproceedings
issued:
  date-parts:
  - 2026
  - 5
  - 5
pdf: https://raw.githubusercontent.com/mlresearch/v315/main/assets/anglada-rotger26a/anglada-rotger26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
