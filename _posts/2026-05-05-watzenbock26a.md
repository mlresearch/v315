---
title: 'Chronological Contrastive Learning: Few-Shot Progression Assessment in Irreversible
  Diseases'
abstract: Quantitative disease severity scoring in medical imaging is costly, time-consuming,
  and subject to inter-reader variability. At the same time, clinical archives contain
  far more longitudinal imaging data than expert-annotated severity scores. Existing
  self-supervised methods typically ignore this chronological structure. We introduce
  ChronoCon, a contrastive learning approach that replaces label-based ranking losses
  with rankings derived solely from the visitation order of a patient’s longitudinal
  scans. Under the clinically plausible assumption of monotonic progression in irreversible
  diseases, the method learns disease-relevant representations without using any expert
  labels. This generalizes the idea of Rank-N-Contrast from label distances to temporal
  ordering. Evaluated on rheumatoid arthritis radiographs for severity assessment,
  the learned representations substantially improve label efficiency. In low-label
  settings, ChronoCon significantly outperforms a fully supervised baseline initialized
  from ImageNet weights. In a few-shot learning experiment, fine-tuning ChronoCon
  on expert scores from only five patients yields an intraclass correlation coefficient
  of 86% for severity score prediction. These results demonstrate the potential of
  chronological contrastive learning to exploit routinely available imaging metadata
  to reduce annotation requirements in the irreversible disease domain.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: watzenbock26a
month: 0
tex_title: 'Chronological Contrastive Learning: Few-Shot Progression Assessment in
  Irreversible Diseases'
firstpage: 2795
lastpage: 2817
page: 2795-2817
order: 2795
cycles: false
bibtex_author: Watzenb{\"o}ck, Clemens and Aletaha, Daniel and Deman, Micha{\"e}l
  and Deimel, Thomas and Eder, Jana and Jan\'{\i}\v{c}kov\'{a}, Ivana and Janiczek,
  Robert and Mandl, Peter and Seeb{\"o}ck, Philipp and Supp, Gabriela and Weiser,
  Paul and Langs, Georg
author:
- given: Clemens
  family: Watzenböck
- given: Daniel
  family: Aletaha
- given: Michaël
  family: Deman
- given: Thomas
  family: Deimel
- given: Jana
  family: Eder
- given: Ivana
  family: Janı́čková
- given: Robert
  family: Janiczek
- given: Peter
  family: Mandl
- given: Philipp
  family: Seeböck
- given: Gabriela
  family: Supp
- given: Paul
  family: Weiser
- given: Georg
  family: Langs
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
pdf: https://raw.githubusercontent.com/mlresearch/v315/main/assets/watzenbock26a/watzenbock26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
