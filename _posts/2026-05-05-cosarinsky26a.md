---
title: 'CheXmask-U: Quantifying uncertainty in landmark-based anatomical segmentation
  for X-ray images'
abstract: 'In this work, we study uncertainty estimation for anatomical landmark-based
  segmentation on chest X-rays. Inspired by hybrid neural network architectures that
  combine standard image convolutional encoders with graph-based generative decoders,
  and leveraging their variational latent space, we derive two complementary measures:
  (i) latent uncertainty, captured directly from the learned distribution parameters,
  and (ii) predictive uncertainty, obtained by generating multiple stochastic output
  predictions from latent samples. Through controlled corruption experiments we show
  that both uncertainty measures increase with perturbation severity, reflecting both
  global and local degradation. We demonstrate that these uncertainty signals can
  identify unreliable predictions by comparing with manual ground-truth, and support
  out-of-distribution detection on the CheXmask dataset. More importantly, we release
  CheXmask-U (dataset), a large scale dataset of 657,566 chest X-ray landmark segmentations
  with per-node uncertainty estimates, enabling researchers to account for spatial
  variations in segmentation quality when using these anatomical masks. Our findings
  establish uncertainty estimation as a promising direction to enhance robustness
  and safe deployment of landmark-based anatomical segmentation methods in chest X-ray.
  A fully working interactive demo of the method is available at CheXmask-U-demo and
  the source code at CheXmask-U-code.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: cosarinsky26a
month: 0
tex_title: 'CheXmask-U: Quantifying uncertainty in landmark-based anatomical segmentation
  for X-ray images'
firstpage: 2192
lastpage: 2207
page: 2192-2207
order: 2192
cycles: false
bibtex_author: Cosarinsky, Matias and Gaggion, Nicolas and Echeveste, Rodrigo and
  Ferrante, Enzo
author:
- given: Matias
  family: Cosarinsky
- given: Nicolas
  family: Gaggion
- given: Rodrigo
  family: Echeveste
- given: Enzo
  family: Ferrante
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
pdf: https://raw.githubusercontent.com/mlresearch/v315/main/assets/cosarinsky26a/cosarinsky26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
