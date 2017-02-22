---
title: Online Optimization with Gradual Variations
abstract: We study the online convex optimization problem, in which an online algorithm
  has to make repeated decisions with convex loss functions and hopes to achieve a
  small regret. We consider a natural restriction of this problem in which the loss
  functions have a small deviation, measured by the sum of the distances between every
  two consecutive loss functions, according to some distance metrics. We show that
  for the linear and general smooth convex loss functions, an online algorithm modified
  from the gradient descend algorithm can achieve a regret which only scales as the
  square root of the deviation. For the closely related problem of prediction with
  expert advice, we show that an online algorithm modified  from the multiplicative
  update algorithm can also achieve a similar regret bound for a different measure
  of deviation. Finally, for loss functions which are strictly convex, we show that
  an online algorithm modified from the online Newton step algorithm can achieve a
  regret which is only logarithmic in terms of the deviation, and as an application,
  we can also have such a logarithmic regret for the portfolio management problem.
pdf: "./chiang12/chiang12.pdf"
layout: inproceedings
key: chiang12
month: 0
firstpage: 6
lastpage: 6
origpdf: http://jmlr.org/proceedings/papers/v23/chiang12/chiang12.pdf
sections: 
authors:
- given: Chao-Kai
  family: Chiang
- given: Tianbao
  family: Yang
- given: Chia-Jung
  family: Lee
- given: Mehrdad
  family: Mahdavi
- given: Chi-Jen
  family: Lu
- given: Rong
  family: Jin
- given: Shenghuo
  family: Zhu
---