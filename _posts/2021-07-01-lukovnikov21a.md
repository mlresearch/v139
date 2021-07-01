---
title: Improving Breadth-Wise Backpropagation in Graph Neural Networks Helps Learning
  Long-Range Dependencies.
abstract: In this work, we focus on the ability of graph neural networks (GNNs) to
  learn long-range patterns in graphs with edge features. Learning patterns that involve
  longer paths in the graph, requires using deeper GNNs. However, GNNs suffer from
  a drop in performance with increasing network depth. To improve the performance
  of deeper GNNs, previous works have investigated normalization techniques and various
  types of skip connections. While they are designed to improve depth-wise backpropagation
  between the representations of the same node in successive layers, they do not improve
  breadth-wise backpropagation between representations of neighbouring nodes. To analyse
  the consequences, we design synthetic datasets serving as a testbed for the ability
  of GNNs to learn long-range patterns. Our analysis shows that several commonly used
  GNN variants with only depth-wise skip connections indeed have problems learning
  long-range patterns. They are clearly outperformed by an attention-based GNN architecture
  that we propose for improving both depth- and breadth-wise backpropagation. We also
  verify that the presented architecture is competitive on real-world data.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: lukovnikov21a
month: 0
tex_title: Improving Breadth-Wise Backpropagation in Graph Neural Networks Helps Learning
  Long-Range Dependencies.
firstpage: 7180
lastpage: 7191
page: 7180-7191
order: 7180
cycles: false
bibtex_author: Lukovnikov, Denis and Fischer, Asja
author:
- given: Denis
  family: Lukovnikov
- given: Asja
  family: Fischer
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
pdf: http://proceedings.mlr.press/v139/lukovnikov21a/lukovnikov21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v139/lukovnikov21a/lukovnikov21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
