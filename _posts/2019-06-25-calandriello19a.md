---
abstract: " Gaussian processes (GP) are a stochastic processes, used  as Bayesian
  approach for the optimization of black-box functions. Despite their effectiveness
  in simple problems, GP-based algorithms hardly scale to high-dimensional functions,
  as their per-iteration time and space cost is at least \\emph{quadratic} in the
  number of dimensions $d$ and iterations $t$. Given a set of $A$ alternatives to
  choose from, the overall runtime $O(t^3 A)$ is prohibitive.  In this paper, we introduce
  BKB (\\textit{budgeted kernelized bandit}), a new approximate GP algorithm for optimization
  under bandit feedback that achieves near-optimal regret (and hence near-optimal
  convergence rate) with near-constant per-iteration complexity and remarkably no
  assumption on the input space or covariance of the GP. We combine a kernelized linear
  bandit algorithm (GP-UCB)  leverage score sampling as a randomized matrix sketching
  and  prove that selecting inducing points based on their posterior variance gives
  an accurate low-rank approximation of the GP, preserving variance estimates and
  confidence intervals. As a consequence, BKB does not suffer from \\emph{variance
  starvation}, an important problem faced by many previous sparse GP approximations.
  Moreover, we show that our procedure selects at most $\\widetilde{O}(d_{eff})$ points,
  where $d_{eff}$ is the \\emph{effective} dimension of the explored space, which
  is typically much smaller than both $d$ and $t$. This greatly reduces the dimensionality
  of the problem, thus leading to a $O(T A d_{eff}^2)$ runtime and $O(A d_{eff})$
  space complexity."
section: contributed
title: 'Gaussian Process Optimization with Adaptive Sketching: Scalable and No Regret'
layout: inproceedings
series: Proceedings of Machine Learning Research
id: calandriello19a
month: 0
tex_title: 'Gaussian Process Optimization with Adaptive Sketching: Scalable and No
  Regret'
firstpage: 533
lastpage: 557
page: 533-557
order: 533
cycles: false
bibtex_author: Calandriello, Daniele and Carratino, Luigi and Lazaric, Alessandro
  and Valko, Michal and Rosasco, Lorenzo
author:
- given: Daniele
  family: Calandriello
- given: Luigi
  family: Carratino
- given: Alessandro
  family: Lazaric
- given: Michal
  family: Valko
- given: Lorenzo
  family: Rosasco
date: 2019-06-25
address: 
publisher: PMLR
container-title: Proceedings of the Thirty-Second Conference on Learning Theory
volume: '99'
genre: inproceedings
issued:
  date-parts:
  - 2019
  - 6
  - 25
pdf: http://proceedings.mlr.press/v99/calandriello19a/calandriello19a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
