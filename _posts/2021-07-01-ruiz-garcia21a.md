---
title: 'Tilting the playing field: Dynamical loss functions for machine learning'
abstract: We show that learning can be improved by using loss functions that evolve
  cyclically during training to emphasize one class at a time. In underparameterized
  networks, such dynamical loss functions can lead to successful training for networks
  that fail to find deep minima of the standard cross-entropy loss. In overparameterized
  networks, dynamical loss functions can lead to better generalization. Improvement
  arises from the interplay of the changing loss landscape with the dynamics of the
  system as it evolves to minimize the loss. In particular, as the loss function oscillates,
  instabilities develop in the form of bifurcation cascades, which we study using
  the Hessian and Neural Tangent Kernel. Valleys in the landscape widen and deepen,
  and then narrow and rise as the loss landscape changes during a cycle. As the landscape
  narrows, the learning rate becomes too large and the network becomes unstable and
  bounces around the valley. This process ultimately pushes the system into deeper
  and wider regions of the loss landscape and is characterized by decreasing eigenvalues
  of the Hessian. This results in better regularized models with improved generalization
  performance.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ruiz-garcia21a
month: 0
tex_title: 'Tilting the playing field: Dynamical loss functions for machine learning'
firstpage: 9157
lastpage: 9167
page: 9157-9167
order: 9157
cycles: false
bibtex_author: Ruiz-Garcia, Miguel and Zhang, Ge and Schoenholz, Samuel S and Liu,
  Andrea J.
author:
- given: Miguel
  family: Ruiz-Garcia
- given: Ge
  family: Zhang
- given: Samuel S
  family: Schoenholz
- given: Andrea J.
  family: Liu
date: 2021-07-01
address:
container-title: Proceedings of the 38th International Conference on Machine Learning
volume: '139'
genre: inproceedings
issued:
  date-parts:
  - 2021
  - 7
  - 1
pdf: http://proceedings.mlr.press/v139/ruiz-garcia21a/ruiz-garcia21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v139/ruiz-garcia21a/ruiz-garcia21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
