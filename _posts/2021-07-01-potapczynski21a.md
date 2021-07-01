---
title: Bias-Free Scalable Gaussian Processes via Randomized Truncations
abstract: 'Scalable Gaussian Process methods are computationally attractive, yet introduce
  modeling biases that require rigorous study. This paper analyzes two common techniques:
  early truncated conjugate gradients (CG) and random Fourier features (RFF). We find
  that both methods introduce a systematic bias on the learned hyperparameters: CG
  tends to underfit while RFF tends to overfit. We address these issues using randomized
  truncation estimators that eliminate bias in exchange for increased variance. In
  the case of RFF, we show that the bias-to-variance conversion is indeed a trade-off:
  the additional variance proves detrimental to optimization. However, in the case
  of CG, our unbiased learning procedure meaningfully outperforms its biased counterpart
  with minimal additional computation. Our code is available at https://github.com/
  cunningham-lab/RTGPS.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: potapczynski21a
month: 0
tex_title: Bias-Free Scalable Gaussian Processes via Randomized Truncations
firstpage: 8609
lastpage: 8619
page: 8609-8619
order: 8609
cycles: false
bibtex_author: Potapczynski, Andres and Wu, Luhuan and Biderman, Dan and Pleiss, Geoff
  and Cunningham, John P
author:
- given: Andres
  family: Potapczynski
- given: Luhuan
  family: Wu
- given: Dan
  family: Biderman
- given: Geoff
  family: Pleiss
- given: John P
  family: Cunningham
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
pdf: http://proceedings.mlr.press/v139/potapczynski21a/potapczynski21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v139/potapczynski21a/potapczynski21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
