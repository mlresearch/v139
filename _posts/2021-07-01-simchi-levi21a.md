---
title: Dynamic Planning and Learning under Recovering Rewards
abstract: 'Motivated by emerging applications such as live-streaming e-commerce, promotions
  and recommendations, we introduce a general class of multi-armed bandit problems
  that have the following two features: (i) the decision maker can pull and collect
  rewards from at most $K$ out of $N$ different arms in each time period; (ii) the
  expected reward of an arm immediately drops after it is pulled, and then non-parametrically
  recovers as the idle time increases. With the objective of maximizing expected cumulative
  rewards over $T$ time periods, we propose, construct and prove performance guarantees
  for a class of “Purely Periodic Policies”. For the offline problem when all model
  parameters are known, our proposed policy obtains an approximation ratio that is
  at the order of $1-\mathcal O(1/\sqrt{K})$, which is asymptotically optimal when
  $K$ grows to infinity. For the online problem when the model parameters are unknown
  and need to be learned, we design an Upper Confidence Bound (UCB) based policy that
  approximately has $\widetilde{\mathcal O}(N\sqrt{T})$ regret against the offline benchmark.
  Our framework and policy design may have the potential to be adapted into other
  offline planning and online learning applications with non-stationary and recovering
  rewards.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: simchi-levi21a
month: 0
tex_title: Dynamic Planning and Learning under Recovering Rewards
firstpage: 9702
lastpage: 9711
page: 9702-9711
order: 9702
cycles: false
bibtex_author: Simchi-Levi, David and Zheng, Zeyu and Zhu, Feng
author:
- given: David
  family: Simchi-Levi
- given: Zeyu
  family: Zheng
- given: Feng
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
pdf: http://proceedings.mlr.press/v139/simchi-levi21a/simchi-levi21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v139/simchi-levi21a/simchi-levi21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
