---
abstract: " There has been significant study on the sample complexity of testing properties
  of distributions over large domains.  For many properties, it is known that the
  sample complexity can be substantially smaller than the domain size. For example,
  over a domain of size $n$, distinguishing the uniform distribution from distributions
  that are far from uniform in $\\ell_1$-distance uses only $O(\\sqrt{n})$ samples.
  \ However, the picture is very different in the presence of arbitrary noise, even
  when the amount of noise is quite small.  In this case, one must distinguish if
  samples are coming from a distribution that is $\\epsilon$-close to uniform from
  the case where the distribution is $(1-\\epsilon)$-far from uniform.  The latter
  task requires nearly linear in $n$ samples (Valiant, 2008; Valiant and Valiant,
  2017a). In this work, we present a noise model that on one hand is more tractable
  for the testing problem, and on the other hand represents a rich class of noise
  families.   In our model, the noisy distribution is a mixture of the original distribution
  and noise, where the latter is known to the tester either explicitly or via sample
  access; the form of the noise is also known \\emph{a priori}.  Focusing on the identity
  and closeness testing problems leads to the following mixture testing question:
  \ Given samples of distributions $p, q_1,q_2$, can we test if $p$ is a mixture of
  $q_1$ and $q_2$?  We consider this general question in various scenarios that differ
  in terms of how the tester can access the distributions, and show that indeed this
  problem is more tractable.  Our results  show that the sample complexity of our
  testers are exactly the same as for the classical non-mixture case. "
section: contributed
title: Testing Mixtures of Discrete Distributions
layout: inproceedings
series: Proceedings of Machine Learning Research
id: aliakbarpour19b
month: 0
tex_title: Testing Mixtures of Discrete Distributions
firstpage: 83
lastpage: 114
page: 83-114
order: 83
cycles: false
bibtex_author: Aliakbarpour, Maryam and Kumar, Ravi and Rubinfeld, Ronitt
author:
- given: Maryam
  family: Aliakbarpour
- given: Ravi
  family: Kumar
- given: Ronitt
  family: Rubinfeld
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
pdf: http://proceedings.mlr.press/v99/aliakbarpour19b/aliakbarpour19b.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
