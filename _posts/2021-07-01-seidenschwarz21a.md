---
title: Learning Intra-Batch Connections for Deep Metric Learning
abstract: The goal of metric learning is to learn a function that maps samples to
  a lower-dimensional space where similar samples lie closer than dissimilar ones.
  Particularly, deep metric learning utilizes neural networks to learn such a mapping.
  Most approaches rely on losses that only take the relations between pairs or triplets
  of samples into account, which either belong to the same class or two different
  classes. However, these methods do not explore the embedding space in its entirety.
  To this end, we propose an approach based on message passing networks that takes
  all the relations in a mini-batch into account. We refine embedding vectors by exchanging
  messages among all samples in a given batch allowing the training process to be
  aware of its overall structure. Since not all samples are equally important to predict
  a decision boundary, we use an attention mechanism during message passing to allow
  samples to weigh the importance of each neighbor accordingly. We achieve state-of-the-art
  results on clustering and image retrieval on the CUB-200-2011, Cars196, Stanford
  Online Products, and In-Shop Clothes datasets. To facilitate further research, we
  make available the code and the models at https://github.com/dvl-tum/intra_batch_connections.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: seidenschwarz21a
month: 0
tex_title: Learning Intra-Batch Connections for Deep Metric Learning
firstpage: 9410
lastpage: 9421
page: 9410-9421
order: 9410
cycles: false
bibtex_author: Seidenschwarz, Jenny Denise and Elezi, Ismail and Leal-Taix{\'e}, Laura
author:
- given: Jenny Denise
  family: Seidenschwarz
- given: Ismail
  family: Elezi
- given: Laura
  family: Leal-Taixé
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
pdf: http://proceedings.mlr.press/v139/seidenschwarz21a/seidenschwarz21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v139/seidenschwarz21a/seidenschwarz21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
