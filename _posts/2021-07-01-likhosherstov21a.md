---
title: Debiasing a First-order Heuristic for Approximate Bi-level Optimization
abstract: Approximate bi-level optimization (ABLO) consists of (outer-level) optimization
  problems, involving numerical (inner-level) optimization loops. While ABLO has many
  applications across deep learning, it suffers from time and memory complexity proportional
  to the length $r$ of its inner optimization loop. To address this complexity, an
  earlier first-order method (FOM) was proposed as a heuristic which omits second
  derivative terms, yielding significant speed gains and requiring only constant memory.
  Despite FOM’s popularity, there is a lack of theoretical understanding of its convergence
  properties. We contribute by theoretically characterizing FOM’s gradient bias under
  mild assumptions. We further demonstrate a rich family of examples where FOM-based
  SGD does not converge to a stationary point of the ABLO objective. We address this
  concern by proposing an unbiased FOM (UFOM) enjoying constant memory complexity
  as a function of $r$. We characterize the introduced time-variance tradeoff, demonstrate
  convergence bounds, and find an optimal UFOM for a given ABLO problem. Finally,
  we propose an efficient adaptive UFOM scheme.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: likhosherstov21a
month: 0
tex_title: Debiasing a First-order Heuristic for Approximate Bi-level Optimization
firstpage: 6621
lastpage: 6630
page: 6621-6630
order: 6621
cycles: false
bibtex_author: Likhosherstov, Valerii and Song, Xingyou and Choromanski, Krzysztof
  and Davis, Jared Q and Weller, Adrian
author:
- given: Valerii
  family: Likhosherstov
- given: Xingyou
  family: Song
- given: Krzysztof
  family: Choromanski
- given: Jared Q
  family: Davis
- given: Adrian
  family: Weller
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
pdf: http://proceedings.mlr.press/v139/likhosherstov21a/likhosherstov21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v139/likhosherstov21a/likhosherstov21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
