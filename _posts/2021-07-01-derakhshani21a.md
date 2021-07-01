---
title: Kernel Continual Learning
abstract: This paper introduces kernel continual learning, a simple but effective
  variant of continual learning that leverages the non-parametric nature of kernel
  methods to tackle catastrophic forgetting. We deploy an episodic memory unit that
  stores a subset of samples for each task to learn task-specific classifiers based
  on kernel ridge regression. This does not require memory replay and systematically
  avoids task interference in the classifiers. We further introduce variational random
  features to learn a data-driven kernel for each task. To do so, we formulate kernel
  continual learning as a variational inference problem, where a random Fourier basis
  is incorporated as the latent variable. The variational posterior distribution over
  the random Fourier basis is inferred from the coreset of each task. In this way,
  we are able to generate more informative kernels specific to each task, and, more
  importantly, the coreset size can be reduced to achieve more compact memory, resulting
  in more efficient continual learning based on episodic memory. Extensive evaluation
  on four benchmarks demonstrates the effectiveness and promise of kernels for continual
  learning.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: derakhshani21a
month: 0
tex_title: Kernel Continual Learning
firstpage: 2621
lastpage: 2631
page: 2621-2631
order: 2621
cycles: false
bibtex_author: Derakhshani, Mohammad Mahdi and Zhen, Xiantong and Shao, Ling and Snoek,
  Cees
author:
- given: Mohammad Mahdi
  family: Derakhshani
- given: Xiantong
  family: Zhen
- given: Ling
  family: Shao
- given: Cees
  family: Snoek
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
pdf: http://proceedings.mlr.press/v139/derakhshani21a/derakhshani21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v139/derakhshani21a/derakhshani21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
