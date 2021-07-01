---
title: Newton Method over Networks is Fast up to the Statistical Precision
abstract: 'We propose a distributed cubic regularization of the Newton method for
  solving (constrained) empirical risk minimization problems over a network of agents,
  modeled as undirected graph. The algorithm employs an inexact, preconditioned Newton
  step at each agent’s side: the gradient of the centralized loss is iteratively estimated
  via a gradient-tracking consensus mechanism and the Hessian is subsampled over the
  local data sets. No Hessian matrices are exchanged over the network. We derive global
  complexity bounds for convex and strongly convex losses. Our analysis reveals an
  interesting interplay between sample and iteration/communication complexity: statistically
  accurate solutions are achievable in roughly the same number of iterations of the
  centralized cubic Newton, with a communication cost per iteration of the order of
  $\widetilde{\mathcal{O}}\big(1/\sqrt{1-\rho}\big)$, where $\rho$ characterizes the
  connectivity of the network. This represents a significant improvement with respect
  to existing, statistically oblivious, distributed Newton-based methods over networks.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: daneshmand21a
month: 0
tex_title: Newton Method over Networks is Fast up to the Statistical Precision
firstpage: 2398
lastpage: 2409
page: 2398-2409
order: 2398
cycles: false
bibtex_author: Daneshmand, Amir and Scutari, Gesualdo and Dvurechensky, Pavel and
  Gasnikov, Alexander
author:
- given: Amir
  family: Daneshmand
- given: Gesualdo
  family: Scutari
- given: Pavel
  family: Dvurechensky
- given: Alexander
  family: Gasnikov
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
pdf: http://proceedings.mlr.press/v139/daneshmand21a/daneshmand21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v139/daneshmand21a/daneshmand21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
