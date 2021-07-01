---
title: Improved Algorithms for Agnostic Pool-based Active Classification
abstract: We consider active learning for binary classification in the agnostic pool-based
  setting. The vast majority of works in active learning in the agnostic setting are
  inspired by the CAL algorithm where each query is uniformly sampled from the disagreement
  region of the current version space. The sample complexity of such algorithms is
  described by a quantity known as the disagreement coefficient which captures both
  the geometry of the hypothesis space as well as the underlying probability space.
  To date, the disagreement coefficient has been justified by minimax lower bounds
  only, leaving the door open for superior instance dependent sample complexities.
  In this work we propose an algorithm that, in contrast to uniform sampling over
  the disagreement region, solves an experimental design problem to determine a distribution
  over examples from which to request labels. We show that the new approach achieves
  sample complexity bounds that are never worse than the best disagreement coefficient-based
  bounds, but in specific cases can be dramatically smaller. From a practical perspective,
  the proposed algorithm requires no hyperparameters to tune (e.g., to control the
  aggressiveness of sampling), and is computationally efficient by means of assuming
  access to an empirical risk minimization oracle (without any constraints). Empirically,
  we demonstrate that our algorithm is superior to state of the art agnostic active
  learning algorithms on image classification datasets.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: katz-samuels21a
month: 0
tex_title: Improved Algorithms for Agnostic Pool-based Active Classification
firstpage: 5334
lastpage: 5344
page: 5334-5344
order: 5334
cycles: false
bibtex_author: Katz-Samuels, Julian and Zhang, Jifan and Jain, Lalit and Jamieson,
  Kevin
author:
- given: Julian
  family: Katz-Samuels
- given: Jifan
  family: Zhang
- given: Lalit
  family: Jain
- given: Kevin
  family: Jamieson
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
pdf: http://proceedings.mlr.press/v139/katz-samuels21a/katz-samuels21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v139/katz-samuels21a/katz-samuels21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
