---
title: 'Bayesian Algorithm Execution: Estimating Computable Properties of Black-box
  Functions Using Mutual Information'
abstract: In many real world problems, we want to infer some property of an expensive
  black-box function f, given a budget of T function evaluations. One example is budget
  constrained global optimization of f, for which Bayesian optimization is a popular
  method. Other properties of interest include local optima, level sets, integrals,
  or graph-structured information induced by f. Often, we can find an algorithm A
  to compute the desired property, but it may require far more than T queries to execute.
  Given such an A, and a prior distribution over f, we refer to the problem of inferring
  the output of A using T evaluations as Bayesian Algorithm Execution (BAX). To tackle
  this problem, we present a procedure, InfoBAX, that sequentially chooses queries
  that maximize mutual information with respect to the algorithm’s output. Applying
  this to Dijkstra’s algorithm, for instance, we infer shortest paths in synthetic
  and real-world graphs with black-box edge costs. Using evolution strategies, we
  yield variants of Bayesian optimization that target local, rather than global, optima.
  On these problems, InfoBAX uses up to 500 times fewer queries to f than required
  by the original algorithm. Our method is closely connected to other Bayesian optimal
  experimental design procedures such as entropy search methods and optimal sensor
  placement using Gaussian processes.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: neiswanger21a
month: 0
tex_title: 'Bayesian Algorithm Execution: Estimating Computable Properties of Black-box
  Functions Using Mutual Information'
firstpage: 8005
lastpage: 8015
page: 8005-8015
order: 8005
cycles: false
bibtex_author: Neiswanger, Willie and Wang, Ke Alexander and Ermon, Stefano
author:
- given: Willie
  family: Neiswanger
- given: Ke Alexander
  family: Wang
- given: Stefano
  family: Ermon
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
pdf: http://proceedings.mlr.press/v139/neiswanger21a/neiswanger21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v139/neiswanger21a/neiswanger21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
