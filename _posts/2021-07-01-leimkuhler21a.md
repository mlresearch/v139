---
title: Better Training using Weight-Constrained Stochastic Dynamics
abstract: We employ constraints to control the parameter space of deep neural networks
  throughout training. The use of customised, appropriately designed constraints can
  reduce the vanishing/exploding gradients problem, improve smoothness of classification
  boundaries, control weight magnitudes and stabilize deep neural networks, and thus
  enhance the robustness of training algorithms and the generalization capabilities
  of neural networks. We provide a general approach to efficiently incorporate constraints
  into a stochastic gradient Langevin framework, allowing enhanced exploration of
  the loss landscape. We also present specific examples of constrained training methods
  motivated by orthogonality preservation for weight matrices and explicit weight
  normalizations. Discretization schemes are provided both for the overdamped formulation
  of Langevin dynamics and the underdamped form, in which momenta further improve
  sampling efficiency. These optimisation schemes can be used directly, without needing
  to adapt neural network architecture design choices or to modify the objective with
  regularization terms, and see performance improvements in classification tasks.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: leimkuhler21a
month: 0
tex_title: Better Training using Weight-Constrained Stochastic Dynamics
firstpage: 6200
lastpage: 6211
page: 6200-6211
order: 6200
cycles: false
bibtex_author: Leimkuhler, Benedict and Vlaar, Tiffany J and Pouchon, Timoth{\'e}e
  and Storkey, Amos
author:
- given: Benedict
  family: Leimkuhler
- given: Tiffany J
  family: Vlaar
- given: Timothée
  family: Pouchon
- given: Amos
  family: Storkey
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
pdf: http://proceedings.mlr.press/v139/leimkuhler21a/leimkuhler21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v139/leimkuhler21a/leimkuhler21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
