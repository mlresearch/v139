---
title: Automatic variational inference with cascading flows
abstract: The automation of probabilistic reasoning is one of the primary aims of
  machine learning. Recently, the confluence of variational inference and deep learning
  has led to powerful and flexible automatic inference methods that can be trained
  by stochastic gradient descent. In particular, normalizing flows are highly parameterized
  deep models that can fit arbitrarily complex posterior densities. However, normalizing
  flows struggle in highly structured probabilistic programs as they need to relearn
  the forward-pass of the program. Automatic structured variational inference (ASVI)
  remedies this problem by constructing variational programs that embed the forward-pass.
  Here, we combine the flexibility of normalizing flows and the prior-embedding property
  of ASVI in a new family of variational programs, which we named cascading flows.
  A cascading flows program interposes a newly designed highway flow architecture
  in between the conditional distributions of the prior program such as to steer it
  toward the observed data. These programs can be constructed automatically from an
  input probabilistic program and can also be amortized automatically. We evaluate
  the performance of the new variational programs in a series of structured inference
  problems. We find that cascading flows have much higher performance than both normalizing
  flows and ASVI in a large set of structured inference problems.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ambrogioni21a
month: 0
tex_title: Automatic variational inference with cascading flows
firstpage: 254
lastpage: 263
page: 254-263
order: 254
cycles: false
bibtex_author: Ambrogioni, Luca and Silvestri, Gianluigi and van Gerven, Marcel
author:
- given: Luca
  family: Ambrogioni
- given: Gianluigi
  family: Silvestri
- given: Marcel
  prefix: van
  family: Gerven
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
pdf: http://proceedings.mlr.press/v139/ambrogioni21a/ambrogioni21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v139/ambrogioni21a/ambrogioni21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
