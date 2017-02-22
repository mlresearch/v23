---
title: 'Unsupervised SVMs: On the Complexity of the Furthest Hyperplane Problem'
abstract: This paper introduces the Furthest Hyperplane Problem (FHP), which is an
  unsupervised counterpart of Support Vector Machines. Given a set of $n$ points in
  $R^{d}$, the objective is to produce the hyperplane (passing through the origin)
  which maximizes the separation margin, that is, the minimal distance between the
  hyperplane and any input point. To the best of our knowledge, this is the first
  paper achieving provable results regarding FHP. We provide both lower and upper
  bounds to this NP-hard problem. First, we give a simple randomized algorithm whose
  running time is $n^{O(1/\theta^{2})}$ where $\theta$ is the optimal separation margin.
  We show that its exponential dependency on $1/\theta^{2}$ is tight, up to sub-polynomial
  factors, assuming SAT cannot be solved in sub-exponential time. Next, we give an
  efficient approximation algorithm. For any $\alpha \in [0, 1]$, the algorithm produces
  a hyperplane whose distance from at least $1 - 3\alpha$ fraction of the points is
  at least $\alpha$ times the optimal separation margin. Finally, we show that FHP
  does not admit a PTAS by presenting a gap preserving reduction from a particular
  version of the PCP theorem.
pdf: "./karnin12/karnin12.pdf"
layout: inproceedings
key: karnin12
month: 0
firstpage: 2
lastpage: 2
origpdf: http://jmlr.org/proceedings/papers/v23/karnin12/karnin12.pdf
sections: 
authors:
- given: Zohar
  family: Karnin
- given: Edo
  family: Liberty
- given: Shachar
  family: Lovett
- given: Roy
  family: Schwartz
- given: Omri
  family: Weinstein
---