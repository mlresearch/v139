---
title: One-sided Frank-Wolfe algorithms for saddle problems
abstract: We study a class of convex-concave saddle-point problems of the form $\min_x\max_y
  ⟨Kx,y⟩+f_{\cal P}(x)-h^*(y)$ where $K$ is a linear operator, $f_{\cal P}$ is the
  sum of a convex function $f$ with a Lipschitz-continuous gradient and the indicator
  function of a bounded convex polytope ${\cal P}$, and $h^\ast$ is a convex (possibly
  nonsmooth) function. Such problem arises, for example, as a Lagrangian relaxation
  of various discrete optimization problems. Our main assumptions are the existence
  of an efficient {\em linear minimization oracle} ($lmo$) for $f_{\cal P}$ and an
  efficient {\em proximal map} ($prox$) for $h^*$ which motivate the solution via
  a blend of proximal primal-dual algorithms and Frank-Wolfe algorithms. In case $h^*$
  is the indicator function of a linear constraint and function $f$ is quadratic,
  we show a $O(1/n^2)$ convergence rate on the dual objective, requiring $O(n \log
  n)$ calls of $lmo$. If the problem comes from the constrained optimization problem
  $\min_{x\in\mathbb R^d}\{f_{\cal P}(x)\:|\:Ax-b=0\}$ then we additionally get bound
  $O(1/n^2)$ both on the primal gap and on the infeasibility gap. In the most general
  case, we show a $O(1/n)$ convergence rate of the primal-dual gap again requiring
  $O(n\log n)$ calls of $lmo$. To the best of our knowledge, this improves on the
  known convergence rates for the considered class of saddle-point problems. We show
  applications to labeling problems frequently appearing in machine learning and computer
  vision.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: kolmogorov21a
month: 0
tex_title: One-sided Frank-Wolfe algorithms for saddle problems
firstpage: 5665
lastpage: 5675
page: 5665-5675
order: 5665
cycles: false
bibtex_author: Kolmogorov, Vladimir and Pock, Thomas
author:
- given: Vladimir
  family: Kolmogorov
- given: Thomas
  family: Pock
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
pdf: http://proceedings.mlr.press/v139/kolmogorov21a/kolmogorov21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v139/kolmogorov21a/kolmogorov21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
