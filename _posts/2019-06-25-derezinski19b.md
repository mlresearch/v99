---
abstract: 'In experimental design, we are given a large collection of vectors, each
  with a hidden response value that we assume derives from an underlying linear model,
  and we wish to pick a small subset of the vectors such that querying the corresponding
  responses will lead to a good estimator of the model.   A classical approach in
  statistics is to assume the responses are linear, plus zero-mean i.i.d. Gaussian
  noise, in which case the goal is to provide an unbiased estimator with smallest
  mean squared error (A-optimal design).   A related approach, more common in computer
  science, is to assume the responses are arbitrary but fixed, in which case the goal
  is to estimate the least squares solution using few responses, as quickly as possible,
  for worst-case inputs.    Despite many attempts, characterizing the relationship
  between these two approaches has proven elusive.   We address this by proposing
  a framework for experimental  design where the responses are produced by an arbitrary
  unknown distribution.   We show that there is an efficient randomized experimental
  design procedure that achieves strong variance bounds for an unbiased estimator
  using few responses  in this general model. Nearly tight bounds for the classical
  A-optimality criterion, as well as improved bounds for worst-case responses, emerge
  as special cases of this result.   In the process, we develop a new algorithm for
  a joint sampling distribution called volume sampling, and we propose a new i.i.d.
  importance sampling method: inverse score sampling.   A key novelty of our analysis
  is in developing new expected error bounds for worst-case regression by controlling
  the tail behavior of i.i.d. sampling via the jointness of volume sampling.   Our
  result motivates a new minimax-optimality criterion for experimental design with
  unbiased estimators, which can be viewed as an extension of both A-optimal design
  and sampling for worst-case regression. '
section: contributed
title: 'Minimax experimental design: Bridging the gap between statistical and worst-case
  approaches to least squares regression'
layout: inproceedings
series: Proceedings of Machine Learning Research
id: derezinski19b
month: 0
tex_title: 'Minimax experimental design: Bridging the gap between statistical and
  worst-case approaches to least squares regression'
firstpage: 1050
lastpage: 1069
page: 1050-1069
order: 1050
cycles: false
bibtex_author: Derezi{\'n}ski, Micha{\l} and Clarkson, Kenneth L. and Mahoney, Michael
  W. and Warmuth, Manfred K.
author:
- given: Michał
  family: Dereziński
- given: Kenneth L.
  family: Clarkson
- given: Michael W.
  family: Mahoney
- given: Manfred K.
  family: Warmuth
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
pdf: http://proceedings.mlr.press/v99/derezinski19b/derezinski19b.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
