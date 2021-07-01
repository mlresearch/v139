---
title: Learning a Universal Template for Few-shot Dataset Generalization
abstract: 'Few-shot dataset generalization is a challenging variant of the well-studied
  few-shot classification problem where a diverse training set of several datasets
  is given, for the purpose of training an adaptable model that can then learn classes
  from \emph{new datasets} using only a few examples. To this end, we propose to utilize
  the diverse training set to construct a \emph{universal template}: a partial model
  that can define a wide array of dataset-specialized models, by plugging in appropriate
  components. For each new few-shot classification problem, our approach therefore
  only requires inferring a small number of parameters to insert into the universal
  template. We design a separate network that produces an initialization of those
  parameters for each given task, and we then fine-tune its proposed initialization
  via a few steps of gradient descent. Our approach is more parameter-efficient, scalable
  and adaptable compared to previous methods, and achieves the state-of-the-art on
  the challenging Meta-Dataset benchmark.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: triantafillou21a
month: 0
tex_title: Learning a Universal Template for Few-shot Dataset Generalization
firstpage: 10424
lastpage: 10433
page: 10424-10433
order: 10424
cycles: false
bibtex_author: Triantafillou, Eleni and Larochelle, Hugo and Zemel, Richard and Dumoulin,
  Vincent
author:
- given: Eleni
  family: Triantafillou
- given: Hugo
  family: Larochelle
- given: Richard
  family: Zemel
- given: Vincent
  family: Dumoulin
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
pdf: http://proceedings.mlr.press/v139/triantafillou21a/triantafillou21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v139/triantafillou21a/triantafillou21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
