---
abstract: Gibbs-ERM learning is a natural idealized model of learning with stochastic
  optimization algorithms (such as SGLD and —to some extent— SGD), while it also arises
  in other contexts, including PAC-Bayesian theory, and sampling mechanisms. In this
  work we study the excess risk suffered by a Gibbs-ERM learner that uses non-convex,
  regularized empirical risk with the goal to understand the interplay between the
  data-generating distribution and learning in large hypothesis spaces. Our main results
  are \emph{distribution-dependent} upper bounds on several notions of excess risk.
  We show that, in all cases, the distribution-dependent excess risk is essentially
  controlled by the \emph{effective dimension} $\text{tr}\left(\boldsymbol{H}^{\star}
  (\boldsymbol{H}^{\star} + \lambda \boldsymbol{I})^{-1}\right)$ of the problem, where
  $\boldsymbol{H}^{\star}$ is the Hessian matrix of the risk at a local minimum. This
  is a well-established notion of effective dimension appearing in several previous
  works, including the analyses of SGD and ridge regression, but ours is the first
  work that brings this dimension to the analysis of learning using Gibbs densities.
  The distribution-dependent view we advocate here improves upon earlier results of
  Raginsky et al. 2017, and can yield much tighter bounds depending on the interplay
  between the data-generating distribution and the loss function. The first part of
  our analysis focuses on the \emph{localized} excess risk in the vicinity of a fixed
  local minimizer. This result is then extended to bounds on the \emph{global} excess
  risk, by characterizing probabilities of local minima (and their complement) under
  Gibbs densities, a results which might be of independent interest.
section: contributed
title: Distribution-Dependent Analysis of Gibbs-ERM Principle
layout: inproceedings
series: Proceedings of Machine Learning Research
id: kuzborskij19a
month: 0
tex_title: Distribution-Dependent Analysis of Gibbs-ERM Principle
firstpage: 2028
lastpage: 2054
page: 2028-2054
order: 2028
cycles: false
bibtex_author: Kuzborskij, Ilja and Cesa-Bianchi, Nicol\`{o} and Szepesv\'ari, Csaba
author:
- given: Ilja
  family: Kuzborskij
- given: Nicolò
  family: Cesa-Bianchi
- given: Csaba
  family: Szepesvári
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
pdf: http://proceedings.mlr.press/v99/kuzborskij19a/kuzborskij19a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
