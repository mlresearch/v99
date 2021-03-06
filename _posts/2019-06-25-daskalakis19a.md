---
abstract: " We provide a computationally and statistically efficient estimator for
  the classical problem of truncated linear regression, where the dependent variable
  $y = \\vec{w}^{\\rm T} \\vec{x}+{\\varepsilon}$ and its corresponding vector of
  covariates $\\vec{x} \\in \\mathbb{R}^k$ are only revealed if the dependent variable
  falls in some subset $S \\subseteq \\mathbb{R}$; otherwise the existence of the
  pair $(\\vec{x},y)$ is hidden. This problem has remained a challenge since the early
  works of Tobin 1958, Amemiya et al. 1973, HAusman et al 1977, Breen et al. 1996,
  its applications are abundant, and its history dates back even further to the work
  of Galton 1897, Pearson 1908, Lee 1915, and Fisher 1931. While consistent estimators
  of the regression coefficients have been identified, the error rates are not well-understood,
  especially in high-dimensional settings. Under a “thickness assumption” about the
  covariance matrix of the covariates in the revealed sample, we provide a computationally
  efficient estimator for the coefficient vector $\\vec{w}$ from $n$ revealed samples
  that attains $\\ell_2$ error $\\tilde{O}(\\sqrt{k / n})$, almost recovering the
  guarantees of least squares in the standard (untruncated) linear regression setting.
  Our estimator uses Projected Stochastic Gradient Descent (PSGD) on the negative
  log-likelihood of the truncated sample, and only needs oracle access to the set
  $S$, which may otherwise be arbitrary, and in particular may be non-convex. PSGD
  must be restricted to an appropriately defined convex cone to guarantee that the
  negative log-likelihood is strongly convex, which in turn is established using concentration
  of matrices on variables with sub-exponential tails. We perform experiments on simulated
  data to illustrate the accuracy of our estimator. As a corollary of our work, we
  show that SGD provably learns the parameters of single-layer neural networks with
  noisy Relu activation functions (see Nair and Hinton 2010, Bengio et al. 2013, Gulcehre
  et al. 2016), given linearly many, in the number of network parameters, input-output
  pairs in the realizable setting."
section: contributed
title: Computationally and Statistically Efficient Truncated Regression
layout: inproceedings
series: Proceedings of Machine Learning Research
id: daskalakis19a
month: 0
tex_title: Computationally and Statistically Efficient Truncated Regression
firstpage: 955
lastpage: 960
page: 955-960
order: 955
cycles: false
bibtex_author: Daskalakis, Constantinos and Gouleakis, Themis and Tzamos, Christos
  and Zampetakis, Manolis
author:
- given: Constantinos
  family: Daskalakis
- given: Themis
  family: Gouleakis
- given: Christos
  family: Tzamos
- given: Manolis
  family: Zampetakis
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
pdf: http://proceedings.mlr.press/v99/daskalakis19a/daskalakis19a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
