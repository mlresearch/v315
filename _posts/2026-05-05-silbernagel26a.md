---
title: 'RNCA: Self-Repairing Segmentation Masks'
abstract: 'Accurately predicting topologically correct masks remains a difficult task
  for general segmentation models, which often produce fragmented or disconnected
  outputs. Fixing these artifacts typically requires handcrafted refinement rules
  or architectures specialized to a particular task. Here, we show that Neural Cellular
  Automata (NCA) can be directly repurposed as an effective refinement mechanism,
  using local, iterative updates guided by image context to repair segmentation masks.
  By training on imperfect masks and ground truths, the automaton learns the structural
  properties of the target shape while relying solely on local information. When applied
  to coarse, globally predicted masks, the learned dynamics progressively reconnect
  broken regions, prune loose fragments and converge towards stable, topologically
  consistent results. We show how refinement NCA () can be easily applied to repair
  common topological errors produced by different base segmentation models and tasks:
  for fragmented retinal vessels, it yields 2–3% gains in Dice/clDice and improves
  Betti Errors, reducing $\beta_0$ errors by 60% and $\beta_1$ by 20%; for myocardium,
  it repairs 61.5% of broken cases in a zero-shot setting while lowering ASSD and
  HD by 19% and 16%, respectively. This showcases NCA as effective and broadly applicable
  refiners.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: silbernagel26a
month: 0
tex_title: 'RNCA: Self-Repairing Segmentation Masks'
firstpage: 2474
lastpage: 2495
page: 2474-2495
order: 2474
cycles: false
bibtex_author: Silbernagel, Malte and Alonso, Albert and Petersen, Jens and Ibragimov,
  Bulat and de Bruijne, Marleen and Wyburd, Madeleine K.
author:
- given: Malte
  family: Silbernagel
- given: Albert
  family: Alonso
- given: Jens
  family: Petersen
- given: Bulat
  family: Ibragimov
- given: Marleen
  family: Bruijne
  prefix: de
- given: Madeleine K.
  family: Wyburd
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
pdf: https://raw.githubusercontent.com/mlresearch/v315/main/assets/silbernagel26a/silbernagel26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
