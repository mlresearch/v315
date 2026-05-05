---
title: 'Testing the Trust: Verification and Validation of Bayesian Segmentation under
  Uncertainty'
abstract: Deep learning has achieved state-of-the-art performance in medical image
  segmentation, yet safe clinical deployment requires rigorous verification and validation
  of model robustness, reliability, and uncertainty behavior. Bayesian segmentation
  methods are often viewed as more trustworthy because they provide uncertainty estimates
  that can support human decision-making, flag unreliable predictions, and mitigate
  risks in downstream clinical workflows. However, most prior studies evaluate these
  models primarily on clean test data, with limited assessment of robustness to perturbations,
  and without examining whether the predicted uncertainty meaningfully correlates
  with segmentation quality. In this work, we conduct a comprehensive and systematic
  evaluation of state-of-the-art deterministic and Bayesian segmentation models across
  multiple datasets, corruption types, and performance metrics. Beyond accuracy-based
  metrics such as DSC and HD95, we analyze over- and under-segmentation trends, predictive
  variance, and the relationship between uncertainty and segmentation correctness.
  Our results show that while all models behave similarly on clean or mildly corrupted
  data, performance diverges significantly as perturbations increase. Models that
  learn and propagate uncertainty during training tend to exhibit improved robustness
  under severe perturbations and uncertainty estimates that better correlate with
  segmentation errors, suggesting potential advantages for safety-critical deployment.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: carannante26a
month: 0
tex_title: 'Testing the Trust: Verification and Validation of Bayesian Segmentation
  under Uncertainty'
firstpage: 4217
lastpage: 4239
page: 4217-4239
order: 4217
cycles: false
bibtex_author: Carannante, Giuseppina and Bouaynaya, Nidhal C. and Dera, Dimah and
  Fathallah-Shaykh, Hassan M. and Rasool, Ghulam
author:
- given: Giuseppina
  family: Carannante
- given: Nidhal C.
  family: Bouaynaya
- given: Dimah
  family: Dera
- given: Hassan M.
  family: Fathallah-Shaykh
- given: Ghulam
  family: Rasool
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
pdf: https://raw.githubusercontent.com/mlresearch/v315/main/assets/carannante26a/carannante26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
