---
title: 'Catastrophic Fisher Explosion: Early Phase Fisher Matrix Impacts Generalization'
abstract: The early phase of training a deep neural network has a dramatic effect
  on the local curvature of the loss function. For instance, using a small learning
  rate does not guarantee stable optimization because the optimization trajectory
  has a tendency to steer towards regions of the loss surface with increasing local
  curvature. We ask whether this tendency is connected to the widely observed phenomenon
  that the choice of the learning rate strongly influences generalization. We first
  show that stochastic gradient descent (SGD) implicitly penalizes the trace of the
  Fisher Information Matrix (FIM), a measure of the local curvature, from the start
  of training. We argue it is an implicit regularizer in SGD by showing that explicitly
  penalizing the trace of the FIM can significantly improve generalization. We highlight
  that poor final generalization coincides with the trace of the FIM attaining a large
  value early in training, to which we refer as catastrophic Fisher explosion. Finally,
  to gain insight into the regularization effect of penalizing the trace of the FIM,
  we show that it limits memorization by reducing the learning speed of examples with
  noisy labels more than that of the examples with clean labels.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: jastrzebski21a
month: 0
tex_title: 'Catastrophic Fisher Explosion: Early Phase Fisher Matrix Impacts Generalization'
firstpage: 4772
lastpage: 4784
page: 4772-4784
order: 4772
cycles: false
bibtex_author: Jastrzebski, Stanislaw and Arpit, Devansh and Astrand, Oliver and Kerg,
  Giancarlo B and Wang, Huan and Xiong, Caiming and Socher, Richard and Cho, Kyunghyun
  and Geras, Krzysztof J
author:
- given: Stanislaw
  family: Jastrzebski
- given: Devansh
  family: Arpit
- given: Oliver
  family: Astrand
- given: Giancarlo B
  family: Kerg
- given: Huan
  family: Wang
- given: Caiming
  family: Xiong
- given: Richard
  family: Socher
- given: Kyunghyun
  family: Cho
- given: Krzysztof J
  family: Geras
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
pdf: http://proceedings.mlr.press/v139/jastrzebski21a/jastrzebski21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v139/jastrzebski21a/jastrzebski21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
