---
abstract: 'Given a Boolean formula F, the problem of model counting, also referred
  to as #SAT is to compute the number of solutions of F. Model counting is a fundamental
  problem in artificial intelligence with a wide range of applications including probabilistic
  reasoning, decision making under uncertainty, quantified information flow, and the
  like. Motivated by the success of SAT solvers, there has been surge of interest
  in the design of hashing-based techniques for approximate model counting for the
  past decade. We profiled the state of the art approximate model counter ApproxMC3
  and observed that over 99.99% of time is consumed by the underlying SAT solver,
  CryptoMinisat. This observation motivated us to ask: Can we design an efficient
  underlying CNF-XOR SAT solver that can take advantage of the structure of hashing-based
  algorithms and would this lead to an efficient approximate model counter? The primary
  contribution of this paper is an affirmative answer to the above question. We present
  a novel architecture, called BIRD, to handle CNF-XOR formulas arising from hashing-based
  techniques. The resulting hashing-based approximate model counter, called ApproxMC3,
  employs the BIRD framework in its underlying SAT solver, CryptoMinisat. To the best
  of our knowledge, we conducted the most comprehensive study of evaluation performance
  of counting algorithms involving 1896 benchmarks with computational effort totaling
  86400 computational hours. Our experimental evaluation demonstrates significant
  runtime performance improvement for ApproxMC3 over ApproMC2. In particular, we solve
  648 benchmarks more than ApproMC2, the state of the art approximate model counter
  and for all the formulas where both ApproMC2 and ApproxMC3 did not timeout and took
  more than 1 seconds, the mean speedup is 284.40 -- more than two orders of magnitude. '
authors:
- Mate Soos
- Kuldeep S. Meel
date: 2019-01-01 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of AAAI Conference on Artificial Intelligence (AAAI)*
publication_types:
- '1'
selected: true
title: 'BIRD: Engineering an Efficient CNF-XOR SAT Solver and its Applications to
  Approximate Model Counting'
url_code: https://github.com/meelgroup/approxmc
url_pdf: https://www.comp.nus.edu.sg/~meel/Papers/aaai19-sm.pdf
url_slides: files/slides/AAAI19_BIRD.pdf
---

