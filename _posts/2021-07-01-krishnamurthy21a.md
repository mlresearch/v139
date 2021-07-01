---
title: Adapting to misspecification in contextual bandits with offline regression
  oracles
abstract: Computationally efficient contextual bandits are often based on estimating
  a predictive model of rewards given contexts and arms using past data. However,
  when the reward model is not well-specified, the bandit algorithm may incur unexpected
  regret, so recent work has focused on algorithms that are robust to misspecification.
  We propose a simple family of contextual bandit algorithms that adapt to misspecification
  error by reverting to a good safe policy when there is evidence that misspecification
  is causing a regret increase. Our algorithm requires only an offline regression
  oracle to ensure regret guarantees that gracefully degrade in terms of a measure
  of the average misspecification level. Compared to prior work, we attain similar
  regret guarantees, but we do no rely on a master algorithm, and do not require more
  robust oracles like online or constrained regression oracles (e.g., Foster et al.
  (2020), Krishnamurthy et al. (2020)). This allows us to design algorithms for more
  general function approximation classes.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: krishnamurthy21a
month: 0
tex_title: Adapting to misspecification in contextual bandits with offline regression
  oracles
firstpage: 5805
lastpage: 5814
page: 5805-5814
order: 5805
cycles: false
bibtex_author: Krishnamurthy, Sanath Kumar and Hadad, Vitor and Athey, Susan
author:
- given: Sanath Kumar
  family: Krishnamurthy
- given: Vitor
  family: Hadad
- given: Susan
  family: Athey
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
pdf: http://proceedings.mlr.press/v139/krishnamurthy21a/krishnamurthy21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v139/krishnamurthy21a/krishnamurthy21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
