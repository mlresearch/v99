---
abstract: 'We investigate the problem of identity testing for multidimensional histogram
  distributions. A distribution $p: D \to \mathbb{R}_+$, where $D \subseteq \mathbb{R}^d$,
  is called a $k$-histogram if there exists a partition of the domain  into $k$ axis-aligned
  rectangles such that $p$ is constant within each such rectangle. Histograms are
  one of the most fundamental nonparametric families of distributions and have been
  extensively studied in computer science and statistics. We give the first identity
  tester for this problem with {\em sub-learning} sample complexity in any fixed dimension
  and a nearly-matching sample complexity lower bound. In more detail, let $q$ be
  an unknown $d$-dimensional $k$-histogram distribution in fixed dimension $d$,  and
  $p$ be an explicitly given $d$-dimensional $k$-histogram. We want to correctly distinguish,
  with probability at least $2/3$, between the case that $p = q$ versus $\|p-q\|_1
  \geq \epsilon$. We design an algorithm for this hypothesis testing problem with
  sample complexity $O((\sqrt{k}/\epsilon^2) 2^{d/2} \log^{2.5 d}(k/\epsilon))$ that
  runs in sample-polynomial time. Our algorithm is robust to model misspecification,
  i.e., succeeds even if $q$ is only promised  to be {\em close} to a $k$-histogram.
  Moreover, for $k = 2^{\Omega(d)}$, we show a sample complexity lower bound of $(\sqrt{k}/\epsilon^2)
  \cdot \Omega(\log(k)/d)^{d-1}$ when $d\geq 2$.  That is, for any fixed dimension
  $d$, our upper and lower bounds are nearly matching. Prior to our work, the sample
  complexity of the $d=1$ case was well-understood, but no algorithm with sub-learning
  sample complexity was known, even for $d=2$. Our new upper and lower bounds have
  interesting conceptual implications regarding the relation between learning and
  testing in this setting.'
section: contributed
title: Testing Identity of Multidimensional Histograms
layout: inproceedings
series: Proceedings of Machine Learning Research
id: diakonikolas19b
month: 0
tex_title: Testing Identity of Multidimensional Histograms
firstpage: 1107
lastpage: 1131
page: 1107-1131
order: 1107
cycles: false
bibtex_author: Diakonikolas, Ilias and Kane, Daniel M. and Peebles, John
author:
- given: Ilias
  family: Diakonikolas
- given: Daniel M.
  family: Kane
- given: John
  family: Peebles
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
pdf: http://proceedings.mlr.press/v99/diakonikolas19b/diakonikolas19b.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
