---
title: Massively Parallel and Asynchronous Tsetlin Machine Architecture Supporting
  Almost Constant-Time Scaling
abstract: Using logical clauses to represent patterns, Tsetlin Machine (TM) have recently
  obtained competitive performance in terms of accuracy, memory footprint, energy,
  and learning speed on several benchmarks. Each TM clause votes for or against a
  particular class, with classification resolved using a majority vote. While the
  evaluation of clauses is fast, being based on binary operators, the voting makes
  it necessary to synchronize the clause evaluation, impeding parallelization. In
  this paper, we propose a novel scheme for desynchronizing the evaluation of clauses,
  eliminating the voting bottleneck. In brief, every clause runs in its own thread
  for massive native parallelism. For each training example, we keep track of the
  class votes obtained from the clauses in local voting tallies. The local voting
  tallies allow us to detach the processing of each clause from the rest of the clauses,
  supporting decentralized learning. This means that the TM most of the time will
  operate on outdated voting tallies. We evaluated the proposed parallelization across
  diverse learning tasks and it turns out that our decentralized TM learning algorithm
  copes well with working on outdated data, resulting in no significant loss in learning
  accuracy. Furthermore, we show that the approach provides up to 50 times faster
  learning. Finally, learning time is almost constant for reasonable clause amounts
  (employing from 20 to 7,000 clauses on a Tesla V100 GPU). For sufficiently large
  clause numbers, computation time increases approximately proportionally. Our parallel
  and asynchronous architecture thus allows processing of more massive datasets and
  operating with more clauses for higher accuracy.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: abeyrathna21a
month: 0
tex_title: Massively Parallel and Asynchronous Tsetlin Machine Architecture Supporting
  Almost Constant-Time Scaling
firstpage: 10
lastpage: 20
page: 10-20
order: 10
cycles: false
bibtex_author: Abeyrathna, Kuruge Darshana and Bhattarai, Bimal and Goodwin, Morten
  and Gorji, Saeed Rahimi and Granmo, Ole-Christoffer and Jiao, Lei and Saha, Rupsa
  and Yadav, Rohan K.
author:
- given: Kuruge Darshana
  family: Abeyrathna
- given: Bimal
  family: Bhattarai
- given: Morten
  family: Goodwin
- given: Saeed Rahimi
  family: Gorji
- given: Ole-Christoffer
  family: Granmo
- given: Lei
  family: Jiao
- given: Rupsa
  family: Saha
- given: Rohan K.
  family: Yadav
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
pdf: http://proceedings.mlr.press/v139/abeyrathna21a/abeyrathna21a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
