---
title: A Comprehensive Benchmarking and Systematic Analysis of Deep Learning Models
  for Sonomammogram Segmentation
abstract: Accurate segmentation of breast lesions in sonomammograms supports computer
  assisted diagnosis and early breast cancer detection. Existing public ultrasound
  datasets contain duplicates, mislabeled cases, and non-breast images, which leads
  to unreliable model evaluation. To address this, we construct a curated multi-centre
  dataset of 3,494 images with expert-verified annotations and patient-level splits.
  Using this dataset, we define a unified benchmarking protocol and evaluate eleven
  representative architectures, including nnU Net variants, SegResNet, SwinUNETR,
  U Mamba, and SAMed. All models are trained and assessed under identical preprocessing,
  training, and evaluation settings. Performance is measured with Dice, Sensitivity,
  Specificity, Accuracy, and Hausdorff Distance metrics. We also analyse how loss
  function choice and training data volume influence performance. SAMed p512 obtains
  the best Dice score at 0.860 $\pm$ 0.141 and the lowest Hausdorff Distance at 3.896
  $\pm$ 5.472. The benchmark provides a reproducible reference for breast ultrasound
  segmentation and clarifies how architecture design and data-related factors shape
  performance in this setting.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: gunawardhana26a
month: 0
tex_title: A Comprehensive Benchmarking and Systematic Analysis of Deep Learning Models
  for Sonomammogram Segmentation
firstpage: 4342
lastpage: 4355
page: 4342-4355
order: 4342
cycles: false
bibtex_author: Gunawardhana, Malitha and Zolek, Norbert
author:
- given: Malitha
  family: Gunawardhana
- given: Norbert
  family: Zolek
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
pdf: https://raw.githubusercontent.com/mlresearch/v315/main/assets/gunawardhana26a/gunawardhana26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
