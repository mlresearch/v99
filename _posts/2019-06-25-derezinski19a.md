---
abstract: " Given a fixed $n\\times d$ matrix $\\mathbf{X}$, where $n\\gg d$, we study
  the complexity of sampling from a  distribution over all subsets of rows where the
  probability of a subset is proportional to the squared volume of the parallelepiped
  spanned by the rows (a.k.a. a determinantal point process). In this task, it is
  important to minimize the preprocessing cost of the procedure (performed once) as
  well as the  sampling cost (performed repeatedly). To that end, we propose a new
  determinantal point process algorithm which has the following two properties, both
  of which are novel: (1) a preprocessing step which runs in time $O\\big(\\text{number-of-non-zeros}(\\mathbf{X})\\cdot\\log
  n\\big)+\\text{poly}(d)$, and (2) a sampling step which runs in $\\text{poly}(d)$
  time, independent of the number of rows $n$. We achieve this by introducing a new
  \\textit{regularized} determinantal point process (R-DPP), which serves as an intermediate
  distribution in the sampling procedure by reducing the number of rows from $n$ to
  $\\text{poly}(d)$. Crucially, this intermediate distribution does not distort the
  probabilities of the target sample. Our key novelty in defining the R-DPP  is the
  use of a Poisson random variable for controlling the probabilities of different
  subset sizes, leading to new determinantal formulas such as the normalization constant
  for this distribution. Our algorithm has applications in many diverse areas where
  determinantal point processes have been used, such as  machine learning, stochastic
  optimization, data summarization and low-rank matrix reconstruction."
section: contributed
title: Fast determinantal point processes via distortion-free intermediate sampling
layout: inproceedings
series: Proceedings of Machine Learning Research
id: derezinski19a
month: 0
tex_title: Fast determinantal point processes via distortion-free intermediate sampling
firstpage: 1029
lastpage: 1049
page: 1029-1049
order: 1029
cycles: false
bibtex_author: Derezi{\'n}ski, Micha{\l}
author:
- given: Michał
  family: Dereziński
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
pdf: http://proceedings.mlr.press/v99/derezinski19a/derezinski19a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
