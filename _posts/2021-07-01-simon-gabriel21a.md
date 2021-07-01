---
title: 'PopSkipJump: Decision-Based Attack for Probabilistic Classifiers'
abstract: Most current classifiers are vulnerable to adversarial examples, small input
  perturbations that change the classification output. Many existing attack algorithms
  cover various settings, from white-box to black-box classifiers, but usually assume
  that the answers are deterministic and often fail when they are not. We therefore
  propose a new adversarial decision-based attack specifically designed for classifiers
  with probabilistic outputs. It is based on the HopSkipJump attack by Chen et al.
  (2019), a strong and query efficient decision-based attack originally designed for
  deterministic classifiers. Our P(robabilisticH)opSkipJump attack adapts its amount
  of queries to maintain HopSkipJump’s original output quality across various noise
  levels, while converging to its query efficiency as the noise level decreases. We
  test our attack on various noise models, including state-of-the-art off-the-shelf
  randomized defenses, and show that they offer almost no extra robustness to decision-based
  attacks. Code is available at https://github.com/cjsg/PopSkipJump.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: simon-gabriel21a
month: 0
tex_title: 'PopSkipJump: Decision-Based Attack for Probabilistic Classifiers'
firstpage: 9712
lastpage: 9721
page: 9712-9721
order: 9712
cycles: false
bibtex_author: Simon-Gabriel, Carl-Johann and Sheikh, Noman Ahmed and Krause, Andreas
author:
- given: Carl-Johann
  family: Simon-Gabriel
- given: Noman Ahmed
  family: Sheikh
- given: Andreas
  family: Krause
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
pdf: http://proceedings.mlr.press/v139/simon-gabriel21a/simon-gabriel21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v139/simon-gabriel21a/simon-gabriel21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
