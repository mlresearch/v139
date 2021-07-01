---
title: Optimizing Black-box Metrics with Iterative Example Weighting
abstract: We consider learning to optimize a classification metric defined by a black-box
  function of the confusion matrix. Such black-box learning settings are ubiquitous,
  for example, when the learner only has query access to the metric of interest, or
  in noisy-label and domain adaptation applications where the learner must evaluate
  the metric via performance evaluation using a small validation sample. Our approach
  is to adaptively learn example weights on the training dataset such that the resulting
  weighted objective best approximates the metric on the validation sample. We show
  how to model and estimate the example weights and use them to iteratively post-shift
  a pre-trained class probability estimator to construct a classifier. We also analyze
  the resulting procedure’s statistical properties. Experiments on various label noise,
  domain shift, and fair classification setups confirm that our proposal compares
  favorably to the state-of-the-art baselines for each application.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: hiranandani21a
month: 0
tex_title: Optimizing Black-box Metrics with Iterative Example Weighting
firstpage: 4239
lastpage: 4249
page: 4239-4249
order: 4239
cycles: false
bibtex_author: Hiranandani, Gaurush and Mathur, Jatin and Narasimhan, Harikrishna
  and Fard, Mahdi Milani and Koyejo, Sanmi
author:
- given: Gaurush
  family: Hiranandani
- given: Jatin
  family: Mathur
- given: Harikrishna
  family: Narasimhan
- given: Mahdi Milani
  family: Fard
- given: Sanmi
  family: Koyejo
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
pdf: http://proceedings.mlr.press/v139/hiranandani21a/hiranandani21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v139/hiranandani21a/hiranandani21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
