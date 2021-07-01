---
title: 'EMaQ: Expected-Max Q-Learning Operator for Simple Yet Effective Offline and
  Online RL'
abstract: Off-policy reinforcement learning (RL) holds the promise of sample-efficient
  learning of decision-making policies by leveraging past experience. However, in
  the offline RL setting – where a fixed collection of interactions are provided and
  no further interactions are allowed – it has been shown that standard off-policy
  RL methods can significantly underperform. In this work, we closely investigate
  an important simplification of BCQ (Fujimoto et al., 2018) – a prior approach for
  offline RL – removing a heuristic design choice. Importantly, in contrast to their
  original theoretical considerations, we derive this simplified algorithm through
  the introduction of a novel backup operator, Expected-Max Q-Learning (EMaQ), which
  is more closely related to the resulting practical algorithm. Specifically, in addition
  to the distribution support, EMaQ explicitly considers the number of samples and
  the proposal distribution, allowing us to derive new sub-optimality bounds. In the
  offline RL setting – the main focus of this work – EMaQ matches and outperforms
  prior state-of-the-art in the D4RL benchmarks (Fu et al., 2020). In the online RL
  setting, we demonstrate that EMaQ is competitive with Soft Actor Critic (SAC). The
  key contributions of our empirical findings are demonstrating the importance of
  careful generative model design for estimating behavior policies, and an intuitive
  notion of complexity for offline RL problems. With its simple interpretation and
  fewer moving parts, such as no explicit function approximator representing the policy,
  EMaQ serves as a strong yet easy to implement baseline for future work.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ghasemipour21a
month: 0
tex_title: 'EMaQ: Expected-Max Q-Learning Operator for Simple Yet Effective Offline
  and Online RL'
firstpage: 3682
lastpage: 3691
page: 3682-3691
order: 3682
cycles: false
bibtex_author: Ghasemipour, Seyed Kamyar Seyed and Schuurmans, Dale and Gu, Shixiang
  Shane
author:
- given: Seyed Kamyar Seyed
  family: Ghasemipour
- given: Dale
  family: Schuurmans
- given: Shixiang Shane
  family: Gu
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
pdf: http://proceedings.mlr.press/v139/ghasemipour21a/ghasemipour21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v139/ghasemipour21a/ghasemipour21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
