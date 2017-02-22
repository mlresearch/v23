---
title: Towards Minimax Policies for Online Linear Optimization with Bandit Feedback
abstract: 'We address the online linear optimization problem with bandit feedback.
  Our contribution is twofold. First, we provide an algorithm (based on exponential
  weights) with a regret of order √\emph{dn} log \emph{N} for any finite action set
  with \emph{N} actions, under the assumption that the instantaneous loss is bounded
  by 1. This shaves off an extraneous √\emph{d} factor compared to previous works,
  and gives a regret bound of order \emph{d}√\emph{n} log \emph{n} for any compact
  set of actions. Without further assumptions on the action set, this last bound is
  minimax optimal up to a logarithmic factor. Interestingly, our result also shows
  that the minimax regret for bandit linear optimization with expert advice in \emph{d}
  dimension is the same as for the basic \emph{d}-armed bandit with expert advice.
  Our second contribution is to show how to use the Mirror Descent algorithm to obtain
  computationally efficient strategies with minimax optimal regret bounds in specific
  examples. More precisely we study two canonical action sets: the hypercube and the
  Euclidean ball. In the former case, we obtain the first computationally efficient
  algorithm with a \emph{d}√\emph{n} regret, thus improving by a factor √\emph{d}
  log \emph{n} over the best known result for a computationally efficient algorithm.
  In the latter case, our approach gives the first algorithm with a √\emph{dn} log
  \emph{n}, again shaving off an extraneous √\emph{d} compared to previous works.'
pdf: "./bubeck12a/bubeck12a.pdf"
layout: inproceedings
key: bubeck12a
month: 0
firstpage: 41
lastpage: 41
origpdf: http://jmlr.org/proceedings/papers/v23/bubeck12a/bubeck12a.pdf
sections: 
authors:
- given: SÃ©bastien
  family: Bubeck
- given: Nicolo
  family: Cesa-Bianchi
- given: Sham M.
  family: Kakade
---
