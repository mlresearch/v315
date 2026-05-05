---
title: Discriminative Self-Supervised Pre-Training for Esophagitis Detection in Upper
  GI Endoscopy Images
abstract: Early and accurate detection of esophagitis in upper gastrointestinal endoscopy
  is essential for guiding targeted treatment and preventing progression to severe
  diseases such as esophageal cancer. Although deep learning methods have shown promise
  in supporting esophagitis diagnosis, their performance heavily relies on large amounts
  of labeled data, which are scarce. Consequently, supervised models often struggle
  to generalize to the high visual variability and subtle lesion differences encountered
  in real-world endoscopic examinations. In this work, we study discriminative self-supervised
  pre-training as a means of leveraging large-scale unlabeled data for robust representation
  learning. Multiple Vision Transformer models are pre-trained using the DINO framework
  on 395,201 unlabeled gastrointestinal endoscopy images and subsequently fine-tuned
  on a curated esophagitis dataset from three clinical centers. Our results demonstrate
  that self-supervised pre-training on in-domain endoscopic images significantly improves
  esophagitis detection performance compared to supervised pre-training on natural
  image datasets such as ImageNet. Specifically, in-domain DINO pre-training yields
  an average performance gain of 6.60 percentage points in AUPRC on the downstream
  detection task, with the best-performing model achieving an AUPRC of 89.82%. These
  findings highlight the importance of in-domain self-supervised learning for reducing
  annotation dependency and improving model robustness in upper GI endoscopy analysis.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: friedetzki26a
month: 0
tex_title: Discriminative Self-Supervised Pre-Training for Esophagitis Detection in
  Upper GI Endoscopy Images
firstpage: 1137
lastpage: 1152
page: 1137-1152
order: 1137
cycles: false
bibtex_author: Friedetzki, Tobias and Chandraiah, Naveen and Svoboda, Emil and Pecina,
  Pavel and Puppe, Frank and Krenzer, Adrian
author:
- given: Tobias
  family: Friedetzki
- given: Naveen
  family: Chandraiah
- given: Emil
  family: Svoboda
- given: Pavel
  family: Pecina
- given: Frank
  family: Puppe
- given: Adrian
  family: Krenzer
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
pdf: https://raw.githubusercontent.com/mlresearch/v315/main/assets/friedetzki26a/friedetzki26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
