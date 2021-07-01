---
title: The Heavy-Tail Phenomenon in SGD
abstract: 'In recent years, various notions of capacity and complexity have been proposed
  for characterizing the generalization properties of stochastic gradient descent
  (SGD) in deep learning. Some of the popular notions that correlate well with the
  performance on unseen data are (i) the ‘flatness’ of the local minimum found by
  SGD, which is related to the eigenvalues of the Hessian, (ii) the ratio of the stepsize
  $\eta$ to the batch-size $b$, which essentially controls the magnitude of the stochastic
  gradient noise, and (iii) the ‘tail-index’, which measures the heaviness of the
  tails of the network weights at convergence. In this paper, we argue that these
  three seemingly unrelated perspectives for generalization are deeply linked to each
  other. We claim that depending on the structure of the Hessian of the loss at the
  minimum, and the choices of the algorithm parameters $\eta$ and $b$, the SGD iterates
  will converge to a \emph{heavy-tailed} stationary distribution. We rigorously prove
  this claim in the setting of quadratic optimization: we show that even in a simple
  linear regression problem with independent and identically distributed data whose
  distribution has finite moments of all order, the iterates can be heavy-tailed with
  infinite variance. We further characterize the behavior of the tails with respect
  to algorithm parameters, the dimension, and the curvature. We then translate our
  results into insights about the behavior of SGD in deep learning. We support our
  theory with experiments conducted on synthetic data, fully connected, and convolutional
  neural networks.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: gurbuzbalaban21a
month: 0
tex_title: The Heavy-Tail Phenomenon in SGD
firstpage: 3964
lastpage: 3975
page: 3964-3975
order: 3964
cycles: false
bibtex_author: Gurbuzbalaban, Mert and Simsekli, Umut and Zhu, Lingjiong
author:
- given: Mert
  family: Gurbuzbalaban
- given: Umut
  family: Simsekli
- given: Lingjiong
  family: Zhu
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
pdf: http://proceedings.mlr.press/v139/gurbuzbalaban21a/gurbuzbalaban21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v139/gurbuzbalaban21a/gurbuzbalaban21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
