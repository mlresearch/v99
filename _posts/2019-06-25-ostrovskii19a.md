---
abstract: In this work we provide an estimator for the covariance matrix of a heavy-tailed
  multivariate distribution. We prove that the proposed estimator $\widehat{\mathbf{S}}$
  admits an \textit{affine-invariant} bound of the form \[ (1-\varepsilon) \mathbf{S}
  \preccurlyeq \widehat{\mathbf{S}} \preccurlyeq (1+\varepsilon) \mathbf{S} \]{in}
  high probability, where $\mathbf{S}$ is the unknown covariance matrix, and $\preccurlyeq$
  is the positive semidefinite order on symmetric matrices. The result only requires
  the existence of fourth-order moments, and allows for $\varepsilon = O(\sqrt{\kappa^4
  d\log(d/\delta)/n})$ where $\kappa^4$ is a measure of kurtosis of the distribution,
  $d$ is the dimensionality of the space, $n$ is the sample size, and $1-\delta$ is
  the desired confidence level. More generally, we can allow for regularization with
  level $\lambda$, then $d$ gets replaced with the degrees of freedom number. Denoting
  $\text{cond}(\mathbf{S})$ the condition number of $\mathbf{S}$, the computational
  cost of the novel estimator is $O(d^2 n + d^3\log(\text{cond}(\mathbf{S})))$, which
  is comparable to the cost of the sample covariance estimator in the statistically
  interesing regime $n \ge d$. We consider applications of our estimator to eigenvalue
  estimation with relative error, and to ridge regression with heavy-tailed random
  design.
section: contributed
title: Affine Invariant Covariance Estimation for Heavy-Tailed Distributions
layout: inproceedings
series: Proceedings of Machine Learning Research
id: ostrovskii19a
month: 0
tex_title: Affine Invariant Covariance Estimation for Heavy-Tailed Distributions
firstpage: 2531
lastpage: 2550
page: 2531-2550
order: 2531
cycles: false
bibtex_author: Ostrovskii, Dmitrii M. and Rudi, Alessandro
author:
- given: Dmitrii M.
  family: Ostrovskii
- given: Alessandro
  family: Rudi
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
pdf: http://proceedings.mlr.press/v99/ostrovskii19a/ostrovskii19a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
