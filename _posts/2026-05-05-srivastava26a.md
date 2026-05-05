---
title: 'CWCD: Category-Wise Contrastive Decoding for Structured Medical Report Generation'
abstract: Interpreting chest X-rays is inherently challenging due to the overlap between
  anatomical structures and the subtle presentation of many clinically significant
  pathologies, making accurate diagnosis time-consuming even for experienced radiologists.
  Recent radiology-focused foundation models, such as LLaVA-Rad and Maira-2, have
  positioned multi-modal large language models (MLLMs) at the forefront of automated
  radiology report generation (RRG). However, despite these advances, current foundation
  models generate reports in a single forward pass. This decoding strategy diminishes
  attention to visual tokens and increases reliance on language priors as generation
  proceeds, which in turn introduce spurious pathology co-occurrences in the generated
  reports. To mitigate these limitations, we propose Category-Wise Contrastive Decoding
  (CWCD), a novel and modular framework designed to enhance structured radiology report
  generation (SRRG). Our approach introduces category-specific parameterization and
  generates category-wise reports by contrasting normal X-rays with masked X-rays
  using category-specific visual prompts. Experimental results demonstrate that CWCD
  consistently outperforms baseline methods across both clinical efficacy and natural
  language generation metrics. An ablation study further elucidates the contribution
  of each architectural component to overall performance.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: srivastava26a
month: 0
tex_title: 'CWCD: Category-Wise Contrastive Decoding for Structured Medical Report
  Generation'
firstpage: 868
lastpage: 893
page: 868-893
order: 868
cycles: false
bibtex_author: Srivastava, Shantam and Bhosale, Mahesh and Doermann, David and Gao,
  Mingchen
author:
- given: Shantam
  family: Srivastava
- given: Mahesh
  family: Bhosale
- given: David
  family: Doermann
- given: Mingchen
  family: Gao
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
pdf: https://raw.githubusercontent.com/mlresearch/v315/main/assets/srivastava26a/srivastava26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
