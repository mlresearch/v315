---
title: Benchmarking the Reproducibility of Brain Tissue Segmentation Across MRI Scanners
abstract: 'Accurate and reproducible brain morphometry from structural magnetic resonance
  imaging is critical for monitoring neuroanatomical changes across time and imaging
  domains. Although deep learning has accelerated segmentation workflows, scanner-induced
  variability and limited reproducibility remain major obstacles, particularly in
  longitudinal and multi-site studies. In this study, we benchmark two state-of-the-art
  segmentation pipelines, FastSurfer and SynthSeg, integrated into FreeSurfer, one
  of the most widely adopted neuroimaging tools. Using two complementary datasets—a
  17-year single-subject longitudinal cohort and a nine-site test–retest cohort—we
  quantify between-scan segmentation variability with region-wise overlap and distance
  measures, including the Dice similarity coefficient, surface Dice, the 95th percentile
  of the Hausdorff distance, and the mean absolute percentage error in regional volumes.
  Our results reveal up to 7–8% variation in the volumes of small subcortical structures
  such as the amygdala and ventral diencephalon, even under controlled test–retest
  conditions. This level of noise raises a critical question: can we reliably detect
  subtle longitudinal changes of 5–10% in small brain regions with volumes below 2
  milliliters, given the magnitude of scanner- and site-induced morphometric variability?
  We further analyze how registration choices and interpolation modes contribute additional,
  although smaller, biases, and we show that surface-based quality filtering can remove
  outlier segmentations while preserving most scans and maintaining morphometric stability.
  This work provides a reproducible benchmark of modern FreeSurfer-based segmentation
  pipelines and highlights the need for harmonization and quality-control strategies
  to enable robust morphometry in real-world neuroimaging studies.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: kondrateva26a
month: 0
tex_title: Benchmarking the Reproducibility of Brain Tissue Segmentation Across MRI
  Scanners
firstpage: 4240
lastpage: 4271
page: 4240-4271
order: 4240
cycles: false
bibtex_author: Kondrateva, Ekaterina and Mohamed, Abdalla Z and Barg, Sandzhi and
  Kofler, Florian
author:
- given: Ekaterina
  family: Kondrateva
- given: Abdalla Z
  family: Mohamed
- given: Sandzhi
  family: Barg
- given: Florian
  family: Kofler
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
pdf: https://raw.githubusercontent.com/mlresearch/v315/main/assets/kondrateva26a/kondrateva26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
