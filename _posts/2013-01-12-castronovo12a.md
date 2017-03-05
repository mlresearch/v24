---
title: Learning Exploration/Exploitation Strategies for Single Trajectory Reinforcement
  Learning
abstract: "We consider the problem of learning high-performance Exploration/Exploitation
  (E/E) strategies for finite Markov Decision Processes (MDPs) when the MDP to be
  controlled is supposed to be drawn from a known probability distribution $p_\mathcal{M}(\cdot)$.
  The performance criterion is the sum of discounted rewards collected by the E/E
  strategy over an infinite length trajectory. We propose an approach for solving
  this problem that works by considering a rich set of candidate E/E strategies and
  by looking for the one that gives the best average performances on MDPs drawn according
  to $p_\mathcal{M}(\cdot)$. As candidate E/E strategies, we consider index-based strategies parametrized
  by small formulas combining variables that include the estimated reward function,
  the number of times each transition has occurred and the optimal value functions
  and the optimal value functions $\hat{V}$ and $\hat{Q}$ of the estimated MDP (obtained
  through value iteration). The search for the best formula is formalized as a multi-armed
  bandit problem, each arm being associated with a formula. We experimentally compare
  the performances of the approach with R-max as well as with $\epsilon$-Greedy strategies and
  the results are promising."
pdf: http://proceedings.mlr.press/v24/castronovo12a/castronovo12a.pdf
layout: inproceedings
series: Proceedings of Machine Learning Research
id: castronovo12a
month: 0
tex_title: Learning Exploration/Exploitation Strategies for Single Trajectory Reinforcement
  Learning
firstpage: 1
lastpage: 10
page: 1-10
order: 1
cycles: false
author:
- given: Michael
  family: Castronovo
- given: Francis
  family: Maes
- given: Raphael
  family: Fonteneau
- given: Damien
  family: Ernst
date: 2013-01-12
address: Edinburgh, Scotland
publisher: PMLR
container-title: Proceedings of the Tenth European Workshop on Reinforcement Learning
volume: '24'
genre: inproceedings
issued:
  date-parts:
  - 2013
  - 1
  - 12
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
