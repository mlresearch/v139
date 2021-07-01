---
title: Learning Binary Decision Trees by Argmin Differentiation
abstract: We address the problem of learning binary decision trees that partition
  data for some downstream task. We propose to learn discrete parameters (i.e., for
  tree traversals and node pruning) and continuous parameters (i.e., for tree split
  functions and prediction functions) simultaneously using argmin differentiation.
  We do so by sparsely relaxing a mixed-integer program for the discrete parameters,
  to allow gradients to pass through the program to continuous parameters. We derive
  customized algorithms to efficiently compute the forward and backward passes. This
  means that our tree learning procedure can be used as an (implicit) layer in arbitrary
  deep networks, and can be optimized with arbitrary loss functions. We demonstrate
  that our approach produces binary trees that are competitive with existing single
  tree and ensemble approaches, in both supervised and unsupervised settings. Further,
  apart from greedy approaches (which do not have competitive accuracies), our method
  is faster to train than all other tree-learning baselines we compare with.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: zantedeschi21a
month: 0
tex_title: Learning Binary Decision Trees by Argmin Differentiation
firstpage: 12298
lastpage: 12309
page: 12298-12309
order: 12298
cycles: false
bibtex_author: Zantedeschi, Valentina and Kusner, Matt and Niculae, Vlad
author:
- given: Valentina
  family: Zantedeschi
- given: Matt
  family: Kusner
- given: Vlad
  family: Niculae
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
pdf: http://proceedings.mlr.press/v139/zantedeschi21a/zantedeschi21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v139/zantedeschi21a/zantedeschi21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
