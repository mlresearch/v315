---
title: 'BTReport: A Framework for Brain Tumor Radiology Report Generation with Clinically
  Relevant Features'
abstract: Recent advances in radiology report generation (RRG) have been driven by
  large paired image-text datasets; however, progress in neuro-oncology RRG has been
  limited due to a scarcity in open paired image-report datasets. Here, we introduce
  BTReport, an open-source framework for brain tumor RRG that constructs natural language
  radiology reports using reliably extracted quantitative imaging features. Unlike
  existing approaches that rely on general-purpose or fine-tuned vision-language models
  for both image interpretation and report composition, BTReport performs deterministic
  feature extraction of clinically-relevant features, then uses large language models
  only for syntactic structuring and narrative synthesis. By separating RRG into deterministic
  feature extraction and report generation stages, synthetically generated reports
  are completely interpretable and contain reliable numerical measurements, a key
  component lacking in existing RRG frameworks. We validate the clinical relevance
  of BTReport-derived features, and demonstrate that BTReport-generated reports more
  closely resemble reference clinical reports when compared to existing baseline RRG
  methods. To further research in neuro-oncology RRG, we introduce BTReport-BraTS,
  a companion dataset that augments BraTS imaging with synthetic radiology reports
  generated with BTReport, and BTReview, a web-based platform for validating the clinical
  quality of synthetically generated radiology reports.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: heras-rivera26a
month: 0
tex_title: 'BTReport: A Framework for Brain Tumor Radiology Report Generation with
  Clinically Relevant Features'
firstpage: 1445
lastpage: 1472
page: 1445-1472
order: 1445
cycles: false
bibtex_author: Heras Rivera, Juampablo E. and Chen, Dickson T. and Ren, Tianyi and
  Low, Daniel K. and Ruzevick, Jacob and Ben Abacha, Asma and Santamaria-Pang, Alberto
  and Kurt, Mehmet
author:
- given: Juampablo E.
  family: Heras Rivera
- given: Dickson T.
  family: Chen
- given: Tianyi
  family: Ren
- given: Daniel K.
  family: Low
- given: Jacob
  family: Ruzevick
- given: Asma
  family: Ben Abacha
- given: Alberto
  family: Santamaria-Pang
- given: Mehmet
  family: Kurt
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
pdf: https://raw.githubusercontent.com/mlresearch/v315/main/assets/heras-rivera26a/heras-rivera26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
