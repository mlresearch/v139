---
title: Discovering symbolic policies with deep reinforcement learning
abstract: Deep reinforcement learning (DRL) has proven successful for many difficult
  control problems by learning policies represented by neural networks. However, the
  complexity of neural network-based policies{—}involving thousands of composed non-linear
  operators{—}can render them problematic to understand, trust, and deploy. In contrast,
  simple policies comprising short symbolic expressions can facilitate human understanding,
  while also being transparent and exhibiting predictable behavior. To this end, we
  propose deep symbolic policy, a novel approach to directly search the space of symbolic
  policies. We use an autoregressive recurrent neural network to generate control
  policies represented by tractable mathematical expressions, employing a risk-seeking
  policy gradient to maximize performance of the generated policies. To scale to environments
  with multi-dimensional action spaces, we propose an "anchoring" algorithm that distills
  pre-trained neural network-based policies into fully symbolic policies, one action
  dimension at a time. We also introduce two novel methods to improve exploration
  in DRL-based combinatorial optimization, building on ideas of entropy regularization
  and distribution initialization. Despite their dramatically reduced complexity,
  we demonstrate that discovered symbolic policies outperform seven state-of-the-art
  DRL algorithms in terms of average rank and average normalized episodic reward across
  eight benchmark environments.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: landajuela21a
month: 0
tex_title: Discovering symbolic policies with deep reinforcement learning
firstpage: 5979
lastpage: 5989
page: 5979-5989
order: 5979
cycles: false
bibtex_author: Landajuela, Mikel and Petersen, Brenden K and Kim, Sookyung and Santiago,
  Claudio P and Glatt, Ruben and Mundhenk, Nathan and Pettit, Jacob F and Faissol,
  Daniel
author:
- given: Mikel
  family: Landajuela
- given: Brenden K
  family: Petersen
- given: Sookyung
  family: Kim
- given: Claudio P
  family: Santiago
- given: Ruben
  family: Glatt
- given: Nathan
  family: Mundhenk
- given: Jacob F
  family: Pettit
- given: Daniel
  family: Faissol
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
pdf: http://proceedings.mlr.press/v139/landajuela21a/landajuela21a.pdf
extras:
- label: Supplementary ZIP
  link: http://proceedings.mlr.press/v139/landajuela21a/landajuela21a-supp.zip
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
