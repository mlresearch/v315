---
title: Tagged-Informed Prior for Motion Quantification in Cine CMR Using Implicit
  Neural Representations
abstract: Accurate quantification of myocardial motion from cine cardiac magnetic
  resonance (CMR) is essential for assessing cardiac function. Although tagged CMR
  provides high-fidelity measurements of myocardial deformation, its longer acquisition
  time limits routine clinical use, making cine CMR motion estimation the more widely
  applicable approach. Implicit neural representations (INRs) offer a promising framework
  for cine-based motion estimation by modelling cardiac motion as a continuous spatio-temporal
  function. However, they require subject-specific optimisation and are sensitive
  to initialization, leading to slow convergence. Furthermore, optimisation from random
  initialization can lead to large number of solutions that may not guarantee biomechanically
  plausible motion. To address these limitations, we propose a strategy to improve
  and accelerate INR-based registration of cine CMR by leveraging a population-level
  prior derived from tagged CMR data. First, we train subject-specific INRs on the
  tagged cine dataset to encode characteristic myocardial deformation patterns. Second,
  we aggregate their parameters across subjects to form a tagged-informed population
  prior. Third, we use this prior initialization to warm-start the optimization of
  cine INRs. The resulting prior provides a physiologically meaningful starting point
  for cine-only INR optimisation, reducing the search space and promoting more realistic
  cardiac motion. We develop and test the method on the UK Biobank. Compared with
  standard initialization, the proposed prior enables the INR to reach near-optimal
  performance using only half as many optimisation steps, achieving a 4% improvement
  in Dice and a 15% reduction in Hausdorff distance. These gains also translate to
  a test set of 855 subjects from a different institution, encompassing different
  pathologies, where the prior yields smoother and more physiologically plausible
  strain curves.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: alvarez-florez26a
month: 0
tex_title: Tagged-Informed Prior for Motion Quantification in Cine CMR Using Implicit
  Neural Representations
firstpage: 2003
lastpage: 2018
page: 2003-2018
order: 2003
cycles: false
bibtex_author: Alvarez-Florez, Laura and Ben Haddou, Soufiane and Tjong, Fleur V.
  Y. and Igum, Ivana
author:
- given: Laura
  family: Alvarez-Florez
- given: Soufiane
  family: Ben Haddou
- given: Fleur V. Y.
  family: Tjong
- given: Ivana
  family: Igum
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
pdf: https://raw.githubusercontent.com/mlresearch/v315/main/assets/alvarez-florez26a/alvarez-florez26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
