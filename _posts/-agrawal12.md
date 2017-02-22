---
title: Analysis of Thompson Sampling for the Multi-armed Bandit Problem
abstract: The multi-armed bandit problem is a popular model for studying exploration/exploitation
  trade-off in sequential decision problems. Many algorithms are now available for
  this well-studied problem. One of the earliest algorithms, given by W. R. Thompson,
  dates back to 1933. This algorithm, referred to as Thompson Sampling, is a natural
  Bayesian algorithm. The basic idea is to choose an arm to play according to its
  probability of being the best arm. Thompson Sampling algorithm has experimentally
  been shown to be close to optimal. In addition, it is efficient to implement and
  exhibits several desirable properties such as small regret for delayed feedback.
  However, theoretical understanding of this algorithm was quite limited. In this
  paper, for the first time, we show that Thompson Sampling algorithm achieves logarithmic
  expected regret for the stochastic multi-armed bandit problem. More precisely, for
  the stochastic two-armed bandit problem, the expected regret in time $T$ is $O(\frac{\ln
  T}{\Delta} + \frac{1}{\Delta^3})$. And, for the stochastic $N$-armed bandit problem,
  the expected regret in time $T$ is $O(\left[\left(\sum_{i=2}^N \frac{1}{\Delta_i^2}\right)^2\right]
  \ln T)$. Our bounds are optimal but for the dependence on $\Delta_i$ and the constant
  factors in big-Oh.
pdf: "./agrawal12/agrawal12.pdf"
layout: inproceedings
key: agrawal12
month: 0
firstpage: 39
lastpage: 39
origpdf: http://jmlr.org/proceedings/papers/v23/agrawal12/agrawal12.pdf
sections: 
authors:
- given: Shipra
  family: Agrawal
- given: Navin
  family: Goyal
---