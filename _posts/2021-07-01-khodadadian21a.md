---
title: Finite-Sample Analysis of Off-Policy Natural Actor-Critic Algorithm
abstract: In this paper, we provide finite-sample convergence guarantees for an off-policy
  variant of the natural actor-critic (NAC) algorithm based on Importance Sampling.
  In particular, we show that the algorithm converges to a global optimal policy with
  a sample complexity of $\mathcal{O}(\epsilon^{-3}\log^2(1/\epsilon))$ under an appropriate
  choice of stepsizes. In order to overcome the issue of large variance due to Importance
  Sampling, we propose the $Q$-trace algorithm for the critic, which is inspired by
  the V-trace algorithm (Espeholt et al., 2018). This enables us to explicitly control
  the bias and variance, and characterize the trade-off between them. As an advantage
  of off-policy sampling, a major feature of our result is that we do not need any
  additional assumptions, beyond the ergodicity of the Markov chain induced by the
  behavior policy.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: khodadadian21a
month: 0
tex_title: Finite-Sample Analysis of Off-Policy Natural Actor-Critic Algorithm
firstpage: 5420
lastpage: 5431
page: 5420-5431
order: 5420
cycles: false
bibtex_author: Khodadadian, Sajad and Chen, Zaiwei and Maguluri, Siva Theja
author:
- given: Sajad
  family: Khodadadian
- given: Zaiwei
  family: Chen
- given: Siva Theja
  family: Maguluri
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
pdf: http://proceedings.mlr.press/v139/khodadadian21a/khodadadian21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v139/khodadadian21a/khodadadian21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
