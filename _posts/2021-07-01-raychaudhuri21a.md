---
title: Cross-domain Imitation from Observations
abstract: Imitation learning seeks to circumvent the difficulty in designing proper
  reward functions for training agents by utilizing expert behavior. With environments
  modeled as Markov Decision Processes (MDP), most of the existing imitation algorithms
  are contingent on the availability of expert demonstrations in the same MDP as the
  one in which a new imitation policy is to be learned. In this paper, we study the
  problem of how to imitate tasks when discrepancies exist between the expert and
  agent MDP. These discrepancies across domains could include differing dynamics,
  viewpoint, or morphology; we present a novel framework to learn correspondences
  across such domains. Importantly, in contrast to prior works, we use unpaired and
  unaligned trajectories containing only states in the expert domain, to learn this
  correspondence. We utilize a cycle-consistency constraint on both the state space
  and a domain agnostic latent space to do this. In addition, we enforce consistency
  on the temporal position of states via a normalized position estimator function,
  to align the trajectories across the two domains. Once this correspondence is found,
  we can directly transfer the demonstrations on one domain to the other and use it
  for imitation. Experiments across a wide variety of challenging domains demonstrate
  the efficacy of our approach.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: raychaudhuri21a
month: 0
tex_title: Cross-domain Imitation from Observations
firstpage: 8902
lastpage: 8912
page: 8902-8912
order: 8902
cycles: false
bibtex_author: Raychaudhuri, Dripta S. and Paul, Sujoy and Vanbaar, Jeroen and Roy-Chowdhury,
  Amit K.
author:
- given: Dripta S.
  family: Raychaudhuri
- given: Sujoy
  family: Paul
- given: Jeroen
  family: Vanbaar
- given: Amit K.
  family: Roy-Chowdhury
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
pdf: http://proceedings.mlr.press/v139/raychaudhuri21a/raychaudhuri21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v139/raychaudhuri21a/raychaudhuri21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
