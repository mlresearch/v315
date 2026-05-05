---
title: Comparing SAM 2 and SAM 3 for Zero-Shot Segmentation of 3D Medical Data
abstract: 'Foundation models, such as the Segment Anything Model (SAM), have heightened
  interest in promptable zero-shot segmentation. Although these models perform strongly
  on natural images, their behavior on medical data remains insufficiently characterized.
  While SAM 2 has been widely adopted for annotation in 3D medical workflows, the
  recently released SAM 3 introduces a new architecture that may change how visual
  prompts are interpreted and propagated. Therefore, to assess whether SAM 3 can serve
  as an out-of-the-box replacement for SAM 2 for zero-shot segmentation of 3D medical
  data, we present the first controlled comparison of both models by evaluating SAM
  3 in its Promptable Visual Segmentation (PVS) mode using a variety of prompting
  strategies. We benchmark on 16 public datasets (CT, MRI, Ultrasound, endoscopy)
  covering 54 anatomical structures, pathologies, and surgical instruments. We further
  quantify three failure modes: prompt-frame over-segmentation, over-propagation after
  object disappearance, and temporal retention of well-initialized predictions. Our
  results show that SAM 3 is consistently stronger under click prompting across modalities,
  with fewer prompt-frame over-segmentation failures and slower prediction retention
  decay compared to SAM 2. Under bounding-box and mask prompts, performance gaps narrow
  in few structures of CT/MR and the models trade off termination behavior, while
  SAM 3 remains stronger on ultrasound and endoscopy sequences. The overall results
  position SAM 3 as the superior default choice for most medical segmentation tasks,
  while clarifying when SAM 2 remains a preferable propagator.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: chakrabarty26a
month: 0
tex_title: Comparing SAM 2 and SAM 3 for Zero-Shot Segmentation of 3D Medical Data
firstpage: 4356
lastpage: 4383
page: 4356-4383
order: 4356
cycles: false
bibtex_author: Chakrabarty, Satrajit and Soni, Ravi
author:
- given: Satrajit
  family: Chakrabarty
- given: Ravi
  family: Soni
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
pdf: https://raw.githubusercontent.com/mlresearch/v315/main/assets/chakrabarty26a/chakrabarty26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
