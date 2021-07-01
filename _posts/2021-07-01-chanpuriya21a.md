---
title: 'DeepWalking Backwards: From Embeddings Back to Graphs'
abstract: Low-dimensional node embeddings play a key role in analyzing graph datasets.
  However, little work studies exactly what information is encoded by popular embedding
  methods, and how this information correlates with performance in downstream learning
  tasks. We tackle this question by studying whether embeddings can be inverted to
  (approximately) recover the graph used to generate them. Focusing on a variant of
  the popular DeepWalk method \cite{PerozziAl-RfouSkiena:2014, QiuDongMa:2018}, we
  present algorithms for accurate embedding inversion – i.e., from the low-dimensional
  embedding of a graph $G$, we can find a graph $\tilde G$ with a very similar embedding.
  We perform numerous experiments on real-world networks, observing that significant
  information about $G$, such as specific edges and bulk properties like triangle
  density, is often lost in $\tilde G$. However, community structure is often preserved
  or even enhanced. Our findings are a step towards a more rigorous understanding
  of exactly what information embeddings encode about the input graph, and why this
  information is useful for learning tasks.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: chanpuriya21a
month: 0
tex_title: 'DeepWalking Backwards: From Embeddings Back to Graphs'
firstpage: 1473
lastpage: 1483
page: 1473-1483
order: 1473
cycles: false
bibtex_author: Chanpuriya, Sudhanshu and Musco, Cameron and Sotiropoulos, Konstantinos
  and Tsourakakis, Charalampos
author:
- given: Sudhanshu
  family: Chanpuriya
- given: Cameron
  family: Musco
- given: Konstantinos
  family: Sotiropoulos
- given: Charalampos
  family: Tsourakakis
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
pdf: http://proceedings.mlr.press/v139/chanpuriya21a/chanpuriya21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v139/chanpuriya21a/chanpuriya21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
