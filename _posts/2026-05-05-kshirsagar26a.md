---
title: Learning Structure-Aware Foundational Representation of Rat Testicular Tubules
  Using Multiple Instance Learning
abstract: Testicular toxicity is a critical factor in preclinical drug safety assessment,
  yet automated modelling of testicular abnormalities remains largely unexplored.
  Unlike liver or kidney tissue, the testis tissue is organized into tubules that
  vary substantially in size and structure, making fixed-resolution patch classification
  ineffective. We first demonstrate that resizing tubules significantly degrades performance
  particularly for larger sized tubules and a Multiple Instance Learning (MIL) model
  offers substantial improvements. Building on this, we introduce TBA-MIL, a transformer-based
  aggregation model with learnable positional embeddings that encodes the structure
  of tubules and is pre-trained using a self-supervised Masked Instance Modelling
  (MIM-MIL) framework, learning tubule representations from large-scale unlabeled
  data. Across four tubule types, TBA-MIL with MIM-MIL outperforms state-of-the-art
  MIL models and establishes a strong baseline for automated testicular toxicity assessment.
  Additionally, we evaluate the proposed framework on an independent toxicological
  study and show that the predicted abnormality distributions significantly differentiate
  control and treated animal tissues, consistent with expert pathologists’ assessment.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: kshirsagar26a
month: 0
tex_title: Learning Structure-Aware Foundational Representation of Rat Testicular
  Tubules Using Multiple Instance Learning
firstpage: 3131
lastpage: 3149
page: 3131-3149
order: 3131
cycles: false
bibtex_author: Kshirsagar, Vedang and Juturu, Saketh and Raipuria, Geetank and Singhal,
  Nitin
author:
- given: Vedang
  family: Kshirsagar
- given: Saketh
  family: Juturu
- given: Geetank
  family: Raipuria
- given: Nitin
  family: Singhal
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
pdf: https://raw.githubusercontent.com/mlresearch/v315/main/assets/kshirsagar26a/kshirsagar26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
