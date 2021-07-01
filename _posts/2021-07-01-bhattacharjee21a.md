---
title: Sample Complexity of Robust Linear Classification on Separated Data
abstract: We consider the sample complexity of learning with adversarial robustness.
  Most prior theoretical results for this problem have considered a setting where
  different classes in the data are close together or overlapping. We consider, in
  contrast, the well-separated case where there exists a classifier with perfect accuracy
  and robustness, and show that the sample complexity narrates an entirely different
  story. Specifically, for linear classifiers, we show a large class of well-separated
  distributions where the expected robust loss of any algorithm is at least $\Omega(\frac{d}{n})$,
  whereas the max margin algorithm has expected standard loss $O(\frac{1}{n})$. This
  shows a gap in the standard and robust losses that cannot be obtained via prior
  techniques. Additionally, we present an algorithm that, given an instance where
  the robustness radius is much smaller than the gap between the classes, gives a
  solution with expected robust loss is $O(\frac{1}{n})$. This shows that for very
  well-separated data, convergence rates of $O(\frac{1}{n})$ are achievable, which
  is not the case otherwise. Our results apply to robustness measured in any $\ell_p$
  norm with $p > 1$ (including $p = \infty$).
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: bhattacharjee21a
month: 0
tex_title: Sample Complexity of Robust Linear Classification on Separated Data
firstpage: 884
lastpage: 893
page: 884-893
order: 884
cycles: false
bibtex_author: Bhattacharjee, Robi and Jha, Somesh and Chaudhuri, Kamalika
author:
- given: Robi
  family: Bhattacharjee
- given: Somesh
  family: Jha
- given: Kamalika
  family: Chaudhuri
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
pdf: http://proceedings.mlr.press/v139/bhattacharjee21a/bhattacharjee21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v139/bhattacharjee21a/bhattacharjee21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
