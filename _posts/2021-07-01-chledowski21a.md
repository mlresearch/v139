---
title: 'Robust Learning-Augmented Caching: An Experimental Study'
abstract: Effective caching is crucial for performance of modern-day computing systems.
  A key optimization problem arising in caching – which item to evict to make room
  for a new item – cannot be optimally solved without knowing the future. There are
  many classical approximation algorithms for this problem, but more recently researchers
  started to successfully apply machine learning to decide what to evict by discovering
  implicit input patterns and predicting the future. While machine learning typically
  does not provide any worst-case guarantees, the new field of learning-augmented
  algorithms proposes solutions which leverage classical online caching algorithms
  to make the machine-learned predictors robust. We are the first to comprehensively
  evaluate these learning-augmented algorithms on real-world caching datasets and
  state-of-the-art machine-learned predictors. We show that a straightforward method
  – blindly following either a predictor or a classical robust algorithm, and switching
  whenever one becomes worse than the other – has only a low overhead over a well-performing
  predictor, while competing with classical methods when the coupled predictor fails,
  thus providing a cheap worst-case insurance.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: chledowski21a
month: 0
tex_title: 'Robust Learning-Augmented Caching: An Experimental Study'
firstpage: 1920
lastpage: 1930
page: 1920-1930
order: 1920
cycles: false
bibtex_author: Ch{\l}{\k{e}}dowski, Jakub and Polak, Adam and Szabucki, Bartosz and
  {\.Z}o{\l}na, Konrad Tomasz
author:
- given: Jakub
  family: Chłędowski
- given: Adam
  family: Polak
- given: Bartosz
  family: Szabucki
- given: Konrad Tomasz
  family: Żołna
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
pdf: http://proceedings.mlr.press/v139/chledowski21a/chledowski21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v139/chledowski21a/chledowski21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
