---
title: Cross-Gradient Aggregation for Decentralized Learning from Non-IID Data
abstract: Decentralized learning enables a group of collaborative agents to learn
  models using a distributed dataset without the need for a central parameter server.
  Recently, decentralized learning algorithms have demonstrated state-of-the-art results
  on benchmark data sets, comparable with centralized algorithms. However, the key
  assumption to achieve competitive performance is that the data is independently
  and identically distributed (IID) among the agents which, in real-life applications,
  is often not applicable. Inspired by ideas from continual learning, we propose Cross-Gradient
  Aggregation (CGA), a novel decentralized learning algorithm where (i) each agent
  aggregates cross-gradient information, i.e., derivatives of its model with respect
  to its neighbors’ datasets, and (ii) updates its model using a projected gradient
  based on quadratic programming (QP). We theoretically analyze the convergence characteristics
  of CGA and demonstrate its efficiency on non-IID data distributions sampled from
  the MNIST and CIFAR-10 datasets. Our empirical comparisons show superior learning
  performance of CGA over existing state-of-the-art decentralized learning algorithms,
  as well as maintaining the improved performance under information compression to
  reduce peer-to-peer communication overhead. The code is available here on GitHub.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: esfandiari21a
month: 0
tex_title: Cross-Gradient Aggregation for Decentralized Learning from Non-IID Data
firstpage: 3036
lastpage: 3046
page: 3036-3046
order: 3036
cycles: false
bibtex_author: Esfandiari, Yasaman and Tan, Sin Yong and Jiang, Zhanhong and Balu,
  Aditya and Herron, Ethan and Hegde, Chinmay and Sarkar, Soumik
author:
- given: Yasaman
  family: Esfandiari
- given: Sin Yong
  family: Tan
- given: Zhanhong
  family: Jiang
- given: Aditya
  family: Balu
- given: Ethan
  family: Herron
- given: Chinmay
  family: Hegde
- given: Soumik
  family: Sarkar
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
pdf: http://proceedings.mlr.press/v139/esfandiari21a/esfandiari21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v139/esfandiari21a/esfandiari21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
