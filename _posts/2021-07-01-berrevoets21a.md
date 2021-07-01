---
title: Learning Queueing Policies for Organ Transplantation Allocation using Interpretable
  Counterfactual Survival Analysis
abstract: Organ transplantation is often the last resort for treating end-stage illnesses,
  but managing transplant wait-lists is challenging because of organ scarcity and
  the complexity of assessing donor-recipient compatibility. In this paper, we develop
  a data-driven model for (real-time) organ allocation using observational data for
  transplant outcomes. Our model integrates a queuing-theoretic framework with unsupervised
  learning to cluster the organs into “organ types”, and then construct priority queues
  (associated with each organ type) wherein incoming patients are assigned. To reason
  about organ allocations, the model uses synthetic controls to infer a patient’s
  survival outcomes under counterfactual allocations to the different organ types{–}
  the model is trained end-to-end to optimise the trade-off between patient waiting
  time and expected survival time. The usage of synthetic controls enable patient-level
  interpretations of allocation decisions that can be presented and understood by
  clinicians. We test our model on multiple data sets, and show that it outperforms
  other organ-allocation policies in terms of added life-years, and death count. Furthermore,
  we introduce a novel organ-allocation simulator to accurately test new policies.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: berrevoets21a
month: 0
tex_title: Learning Queueing Policies for Organ Transplantation Allocation using Interpretable
  Counterfactual Survival Analysis
firstpage: 792
lastpage: 802
page: 792-802
order: 792
cycles: false
bibtex_author: Berrevoets, Jeroen and Alaa, Ahmed and Qian, Zhaozhi and Jordon, James
  and Gimson, Alexander E.S. and Van Der Schaar, Mihaela
author:
- given: Jeroen
  family: Berrevoets
- given: Ahmed
  family: Alaa
- given: Zhaozhi
  family: Qian
- given: James
  family: Jordon
- given: Alexander E.S.
  family: Gimson
- given: Mihaela
  family: Van Der Schaar
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
pdf: http://proceedings.mlr.press/v139/berrevoets21a/berrevoets21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v139/berrevoets21a/berrevoets21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
