---
title: 'Resource Allocation in Multi-armed Bandit Exploration: Overcoming Sublinear
  Scaling with Adaptive Parallelism'
abstract: We study exploration in stochastic multi-armed bandits when we have access
  to a divisible resource that can be allocated in varying amounts to arm pulls. We
  focus in particular on the allocation of distributed computing resources, where
  we may obtain results faster by allocating more resources per pull, but might have
  reduced throughput due to nonlinear scaling. For example, in simulation-based scientific
  studies, an expensive simulation can be sped up by running it on multiple cores.
  This speed-up however, is partly offset by the communication among cores, which
  results in lower throughput than if fewer cores were allocated to run more trials
  in parallel. In this paper, we explore these trade-offs in two settings. First,
  in a fixed confidence setting, we need to find the best arm with a given target
  success probability as quickly as possible. We propose an algorithm which trades
  off between information accumulation and throughput and show that the time taken
  can be upper bounded by the solution of a dynamic program whose inputs are the gaps
  between the sub-optimal and optimal arms. We also prove a matching hardness result.
  Second, we present an algorithm for a fixed deadline setting, where we are given
  a time deadline and need to maximize the probability of finding the best arm. We
  corroborate our theoretical insights with simulation experiments that show that
  the algorithms consistently match or outperform baseline algorithms on a variety
  of problem instances.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: thananjeyan21a
month: 0
tex_title: 'Resource Allocation in Multi-armed Bandit Exploration: Overcoming Sublinear
  Scaling with Adaptive Parallelism'
firstpage: 10236
lastpage: 10246
page: 10236-10246
order: 10236
cycles: false
bibtex_author: Thananjeyan, Brijen and Kandasamy, Kirthevasan and Stoica, Ion and
  Jordan, Michael and Goldberg, Ken and Gonzalez, Joseph
author:
- given: Brijen
  family: Thananjeyan
- given: Kirthevasan
  family: Kandasamy
- given: Ion
  family: Stoica
- given: Michael
  family: Jordan
- given: Ken
  family: Goldberg
- given: Joseph
  family: Gonzalez
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
pdf: http://proceedings.mlr.press/v139/thananjeyan21a/thananjeyan21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v139/thananjeyan21a/thananjeyan21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
