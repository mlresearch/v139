---
title: Robust Asymmetric Learning in POMDPs
abstract: 'Policies for partially observed Markov decision processes can be efficiently
  learned by imitating expert policies generated using asymmetric information. Unfortunately,
  existing approaches for this kind of imitation learning have a serious flaw: the
  expert does not know what the trainee cannot see, and as a result may encourage
  actions that are sub-optimal or unsafe under partial information. To address this
  issue, we derive an update which, when applied iteratively to an expert, maximizes
  the expected reward of the trainee’s policy. Using this update, we construct a computationally
  efficient algorithm, adaptive asymmetric DAgger (A2D), that jointly trains the expert
  and trainee policies. We then show that A2D allows the trainee to safely imitate
  the modified expert, and outperforms policies learned either by imitating a fixed
  expert or through direct reinforcement learning.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: warrington21a
month: 0
tex_title: Robust Asymmetric Learning in POMDPs
firstpage: 11013
lastpage: 11023
page: 11013-11023
order: 11013
cycles: false
bibtex_author: Warrington, Andrew and Lavington, Jonathan W and Scibior, Adam and
  Schmidt, Mark and Wood, Frank
author:
- given: Andrew
  family: Warrington
- given: Jonathan W
  family: Lavington
- given: Adam
  family: Scibior
- given: Mark
  family: Schmidt
- given: Frank
  family: Wood
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
pdf: http://proceedings.mlr.press/v139/warrington21a/warrington21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v139/warrington21a/warrington21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
