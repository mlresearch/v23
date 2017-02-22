---
title: Learning DNF Expressions from Fourier Spectrum
abstract: Since its introduction by Valiant in 1984, PAC learning of DNF expressions
  remains one of the central problems in learning theory. We consider this problem
  in the setting where the underlying distribution is uniform, or more generally,
  a product distribution. Kalai, Samorodnitsky, and Teng (2009b) showed that in this
  setting a DNF expression can be efficiently approximated from its ``heavy'' low-degree
  Fourier coefficients alone. This is in contrast to previous approaches where boosting
  was used and thus Fourier coefficients of the target function modified by various
  distributions were needed. This property is crucial for learning of DNF expressions
  over smoothed product distributions, a learning model introduced by Kalai et al.
  (2009b) and inspired by the seminal smoothed analysis model of Spielman and Teng
  (2004). We introduce a new approach to learning (or approximating) a polynomial
  threshold functions which is based on creating a function with range [-1, 1] that
  approximately agrees with the unknown function on low-degree Fourier coefficients.
  We then describe conditions under which this is sufficient for learning polynomial
  threshold functions. Our approach yields a new, simple algorithm for approximating
  any polynomial-size DNF expression from its ``heavy'' low-degree Fourier coefficients
  alone. This algorithm greatly simplifies the proof of learnability of DNF expressions
  over smoothed product distributions and is simpler than all previous algorithm for
  PAC learning of DNF expression using membership queries. We also describe an application
  of our algorithm to learning monotone DNF expressions over product distributions.
  Building on the work of Servedio (2004), we give an algorithm that runs in time
  poly((\emph{s}⋅ log (\emph{s}/ε))^{log (\emph{s}/ε)}, \emph{n}), where \emph{s}
  is the size of the DNF expression and ε is the accuracy. This improves on poly((\emph{s}⋅
  log (\emph{ns}/ε))^{log (\emph{s}/ε)⋅ log(1/ε)}, \emph{n}) bound of Servedio (2004).
pdf: "./feldman12b/feldman12b.pdf"
layout: inproceedings
key: feldman12b
month: 0
firstpage: 17
lastpage: 17
origpdf: http://jmlr.org/proceedings/papers/v23/feldman12b/feldman12b.pdf
sections: 
authors:
- given: Vitaly
  family: Feldman
---