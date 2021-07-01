---
title: Nonparametric Decomposition of Sparse Tensors
abstract: Tensor decomposition is a powerful framework for multiway data analysis.
  Despite the success of existing approaches, they ignore the sparse nature of the
  tensor data in many real-world applications, explicitly or implicitly assuming dense
  tensors. To address this model misspecification and to exploit the sparse tensor
  structures, we propose Nonparametric dEcomposition of Sparse Tensors (\ours), which
  can capture both the sparse structure properties and complex relationships between
  the tensor nodes to enhance the embedding estimation. Specifically, we first use
  completely random measures to construct tensor-valued random processes. We prove
  that the entry growth is much slower than that of the corresponding tensor size,
  which implies sparsity. Given finite observations (\ie projections), we then propose
  two nonparametric decomposition models that couple Dirichlet processes and Gaussian
  processes to jointly sample the sparse entry indices and the entry values (the latter
  as a nonlinear mapping of the embeddings), so as to encode both the structure properties
  and nonlinear relationships of the tensor nodes into the embeddings. Finally, we
  use the stick-breaking construction and random Fourier features to develop a scalable,
  stochastic variational learning algorithm. We show the advantage of our approach
  in sparse tensor generation, and entry index and value prediction in several real-world
  applications.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: tillinghast21a
month: 0
tex_title: Nonparametric Decomposition of Sparse Tensors
firstpage: 10301
lastpage: 10311
page: 10301-10311
order: 10301
cycles: false
bibtex_author: Tillinghast, Conor and Zhe, Shandian
author:
- given: Conor
  family: Tillinghast
- given: Shandian
  family: Zhe
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
pdf: http://proceedings.mlr.press/v139/tillinghast21a/tillinghast21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v139/tillinghast21a/tillinghast21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
