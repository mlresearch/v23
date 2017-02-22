---
title: Differentially Private Online Learning
abstract: 'In this paper, we consider the problem of preserving privacy in the context
  of online learning. Online learning involves learning from data in real-time, due
  to which the learned model as well as its predictions are continuously changing.
  This makes preserving privacy of each data point significantly more challenging
  as its effect on the learned model can be easily tracked by observing changes in
  the subsequent predictions. Furthermore, with more and more online systems (e.g.
  search engines like Bing, Google etc.) trying to learn their customers'' behavior
  by leveraging their access to sensitive customer data (through cookies etc.), the
  problem of privacy preserving online learning has become critical. We study the
  problem in the framework of online convex programming (OCP) -- a popular online
  learning setting with several theoretical and practical implications -- while using
  differential privacy as the formal measure of privacy. For this problem, we provide
  a generic framework that can be used to convert any given OCP algorithm into a private
  OCP algorithm with provable privacy as well as regret guarantees (utility), provided
  that the given OCP algorithm satisfies the following two criteria: 1) linearly decreasing
  sensitivity, i.e., the effect of the new data points on the learned model decreases
  linearly, 2) sub-linear regret. We then illustrate our approach by converting two
  popular OCP algorithms into corresponding differentially private algorithms while
  guaranteeing \emph{Õ(√T)}  regret for strongly convex functions. Next, we consider
  the practically important class of online linear regression problems, for which
  we generalize the approach by Dwork et al. (2010a) to provide a differentially private
  algorithm with just poly-log regret. Finally, we show that our online learning framework
  can be used to provide differentially private algorithms for the offline learning
  problem as well. For the offline learning problem, our approach guarantees \emph{better}
  error bounds and is more practical than the existing state-of-the-art methods (Chaudhuri
  et al., 2011; Rubinstein et al., 2009).'
pdf: "./jain12/jain12.pdf"
layout: inproceedings
key: jain12
month: 0
firstpage: 24
lastpage: 24
origpdf: http://jmlr.org/proceedings/papers/v23/jain12/jain12.pdf
sections: 
authors:
- given: Prateek
  family: Jain
- given: Pravesh
  family: Kothari
- given: Abhradeep
  family: Thakurta
---