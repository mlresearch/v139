---
title: Label-Only Membership Inference Attacks
abstract: Membership inference is one of the simplest privacy threats faced by machine
  learning models that are trained on private sensitive data. In this attack, an adversary
  infers whether a particular point was used to train the model, or not, by observing
  the model’s predictions. Whereas current attack methods all require access to the
  model’s predicted confidence score, we introduce a label-only attack that instead
  evaluates the robustness of the model’s predicted (hard) labels under perturbations
  of the input, to infer membership. Our label-only attack is not only as-effective
  as attacks requiring access to confidence scores, it also demonstrates that a class
  of defenses against membership inference, which we call “confidence masking” because
  they obfuscate the confidence scores to thwart attacks, are insufficient to prevent
  the leakage of private information. Our experiments show that training with differential
  privacy or strong L2 regularization are the only current defenses that meaningfully
  decrease leakage of private information, even for points that are outliers of the
  training distribution.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: choquette-choo21a
month: 0
tex_title: Label-Only Membership Inference Attacks
firstpage: 1964
lastpage: 1974
page: 1964-1974
order: 1964
cycles: false
bibtex_author: Choquette-Choo, Christopher A. and Tramer, Florian and Carlini, Nicholas
  and Papernot, Nicolas
author:
- given: Christopher A.
  family: Choquette-Choo
- given: Florian
  family: Tramer
- given: Nicholas
  family: Carlini
- given: Nicolas
  family: Papernot
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
pdf: http://proceedings.mlr.press/v139/choquette-choo21a/choquette-choo21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v139/choquette-choo21a/choquette-choo21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
