---
title: Improving Ultrametrics Embeddings Through Coresets
abstract: 'To tackle the curse of dimensionality in data analysis and unsupervised
  learning, it is critical to be able to efficiently compute “simple” faithful representations
  of the data that helps extract information, improves understanding and visualization
  of the structure. When the dataset consists of $d$-dimensional vectors, simple representations
  of the data may consist in trees or ultrametrics, and the goal is to best preserve
  the distances (i.e.: dissimilarity values) between data elements. To circumvent
  the quadratic running times of the most popular methods for fitting ultrametrics,
  such as average, single, or complete linkage, \citet{CKL20} recently presented a
  new algorithm that for any $c \ge 1$, outputs in time $n^{1+O(1/c^2)}$ an ultrametric
  $\Delta$ such that for any two points $u, v$, $\Delta(u, v)$ is within a multiplicative
  factor of $5c$ to the distance between $u$ and $v$ in the “best” ultrametric representation.
  We improve the above result and show how to improve the above guarantee from $5c$
  to $\sqrt{2}c + \varepsilon$ while achieving the same asymptotic running time. To
  complement the improved theoretical bound, we additionally show that the performances
  of our algorithm are significantly better for various real-world datasets.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: cohen-addad21a
month: 0
tex_title: Improving Ultrametrics Embeddings Through Coresets
firstpage: 2060
lastpage: 2068
page: 2060-2068
order: 2060
cycles: false
bibtex_author: Cohen-Addad, Vincent and De Joannis De Verclos, R{\'e}mi and Lagarde,
  Guillaume
author:
- given: Vincent
  family: Cohen-Addad
- given: Rémi
  family: De Joannis De Verclos
- given: Guillaume
  family: Lagarde
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
pdf: http://proceedings.mlr.press/v139/cohen-addad21a/cohen-addad21a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
