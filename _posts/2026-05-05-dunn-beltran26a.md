---
title: 'Seeing Down the Line: Endoscopic Reconstruction with Centerline Constraints'
abstract: Colonoscopy remains the gold standard for colorectal cancer screening, but
  there is still no real-time, geometry-aware way to quantify which parts of the colon
  have been inspected during a procedure. We revisit 3D Gaussian endoscopic reconstruction
  as a representation and geometry problem rather than a new network design. Assuming
  known camera poses and off-the-shelf depth or photometric supervision, we add a
  simple centerline-based coordinate system and priors on top of an existing Gaussian
  mapping backbone. From the noisy pose stream we maintain an online centerline and
  Bishop frame, assign each Gaussian tubular coordinates $(s,r,\theta)$, and use these
  coordinates both to regularize the map toward a hollow tube and to accumulate coverage
  statistics in colon-intrinsic space. On long C3VD phantom colonoscopy sequences,
  this lightweight modification achieves Chamfer distance comparable to or better
  than an endoscopy-specific 3D Gaussian SLAM baseline while running at frame rates
  close to MonoGS and yielding improved rendering quality, with negligible additional
  computation. At the same time, the same representation produces unrolled colon views
  and segment-wise coverage summaries essentially "for free", making centerline-aware
  Gaussian mapping a practical drop-in component for future real-time quality monitoring
  tools in colonoscopy.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: dunn-beltran26a
month: 0
tex_title: 'Seeing Down the Line: Endoscopic Reconstruction with Centerline Constraints'
firstpage: 360
lastpage: 378
page: 360-378
order: 360
cycles: false
bibtex_author: Dunn Beltran, Andrea and Hardy, Romain and Rajpurkar, Pranav
author:
- given: Andrea
  family: Dunn Beltran
- given: Romain
  family: Hardy
- given: Pranav
  family: Rajpurkar
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
pdf: https://raw.githubusercontent.com/mlresearch/v315/main/assets/dunn-beltran26a/dunn-beltran26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
