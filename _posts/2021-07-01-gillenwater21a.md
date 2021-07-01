---
title: Differentially Private Quantiles
abstract: 'Quantiles are often used for summarizing and understanding data. If that
  data is sensitive, it may be necessary to compute quantiles in a way that is differentially
  private, providing theoretical guarantees that the result does not reveal private
  information. However, when multiple quantiles are needed, existing differentially
  private algorithms fare poorly: they either compute quantiles individually, splitting
  the privacy budget, or summarize the entire distribution, wasting effort. In either
  case the result is reduced accuracy. In this work we propose an instance of the
  exponential mechanism that simultaneously estimates exactly $m$ quantiles from $n$
  data points while guaranteeing differential privacy. The utility function is carefully
  structured to allow for an efficient implementation that returns estimates of all
  $m$ quantiles in time $O(mn\log(n) + m^2n)$. Experiments show that our method significantly
  outperforms the current state of the art on both real and synthetic data while remaining
  efficient enough to be practical.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: gillenwater21a
month: 0
tex_title: Differentially Private Quantiles
firstpage: 3713
lastpage: 3722
page: 3713-3722
order: 3713
cycles: false
bibtex_author: Gillenwater, Jennifer and Joseph, Matthew and Kulesza, Alex
author:
- given: Jennifer
  family: Gillenwater
- given: Matthew
  family: Joseph
- given: Alex
  family: Kulesza
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
pdf: http://proceedings.mlr.press/v139/gillenwater21a/gillenwater21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v139/gillenwater21a/gillenwater21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
