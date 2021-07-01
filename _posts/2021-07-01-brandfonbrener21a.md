---
title: Offline Contextual Bandits with Overparameterized Models
abstract: Recent results in supervised learning suggest that while overparameterized
  models have the capacity to overfit, they in fact generalize quite well. We ask
  whether the same phenomenon occurs for offline contextual bandits. Our results are
  mixed. Value-based algorithms benefit from the same generalization behavior as overparameterized
  supervised learning, but policy-based algorithms do not. We show that this discrepancy
  is due to the \emph{action-stability} of their objectives. An objective is action-stable
  if there exists a prediction (action-value vector or action distribution) which
  is optimal no matter which action is observed. While value-based objectives are
  action-stable, policy-based objectives are unstable. We formally prove upper bounds
  on the regret of overparameterized value-based learning and lower bounds on the
  regret for policy-based algorithms. In our experiments with large neural networks,
  this gap between action-stable value-based objectives and unstable policy-based
  objectives leads to significant performance differences.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: brandfonbrener21a
month: 0
tex_title: Offline Contextual Bandits with Overparameterized Models
firstpage: 1049
lastpage: 1058
page: 1049-1058
order: 1049
cycles: false
bibtex_author: Brandfonbrener, David and Whitney, William and Ranganath, Rajesh and
  Bruna, Joan
author:
- given: David
  family: Brandfonbrener
- given: William
  family: Whitney
- given: Rajesh
  family: Ranganath
- given: Joan
  family: Bruna
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
pdf: http://proceedings.mlr.press/v139/brandfonbrener21a/brandfonbrener21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v139/brandfonbrener21a/brandfonbrener21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
