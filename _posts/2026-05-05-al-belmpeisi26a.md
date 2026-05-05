---
title: 'Deep Learning for Liver Disease Stratification: Findings from UKBB MRI'
abstract: Metabolic dysfunction-associated steatotic liver disease (MASLD) and its
  progressive form, metabolic dysfunction-associated steatohepatitis (MASH), have
  become more prevalent, spurring interest in using magnetic resonance imaging (MRI)
  sequences for diagnosis. In this study, we propose a method that uses deep learning
  to diagnose MASLD and MASH with significant fibrosis from single-slice (2D) and
  volumetric (3D) MRI sequences that originate from the UK Biobank. In this paper,
  we focus on transparent decision-making. Our study shows that imposing anatomically
  informed constraints by using a liver segmentation mask on the network’s input has
  minimal impact on diagnostic performance. Still, it redirects attention to clinically
  relevant liver regions, preventing shortcut learning from extrahepatic features,
  such as subcutaneous fat. These constraints shift the focus of the model toward
  proton density fat fraction (PDFF) maps for healthy liver assessment, $T_1$ maps
  for MASLD diagnosis, and both sequences to identify MASH with significant fibrosis.
  Our top-performing models achieve AUCs of 0.89/0.96/0.79 for the diagnosis of the
  healthy/MASLD/MASH groups with significant fibrosis, respectively. Despite label
  noise and limited sequence specificity, which primarily hinder predictive performance
  in cases of MASH with significant fibrosis, the identified indicators are frequently
  located in liver regions consistent with prior understanding of disease progression.
  In conclusion, we find that 2D MRI sequences are sufficient for diagnosing MASLD/MASH
  with significant fibrosis, as performance decreases and computation time increases
  when using 3D volumes.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: al-belmpeisi26a
month: 0
tex_title: 'Deep Learning for Liver Disease Stratification: Findings from UKBB MRI'
firstpage: 4384
lastpage: 4400
page: 4384-4400
order: 4384
cycles: false
bibtex_author: Al-Belmpeisi, Rami and Sundgaard, Josefine Vilsb ll and Larsen, Peter
  Hj rringgaard and Dahl, Anders Bjorholm
author:
- given: Rami
  family: Al-Belmpeisi
- given: Josefine Vilsb ll
  family: Sundgaard
- given: Peter Hj rringgaard
  family: Larsen
- given: Anders Bjorholm
  family: Dahl
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
pdf: https://raw.githubusercontent.com/mlresearch/v315/main/assets/al-belmpeisi26a/al-belmpeisi26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
