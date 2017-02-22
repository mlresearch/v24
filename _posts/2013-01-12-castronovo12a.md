---
title: Learning Exploration/Exploitation Strategies for Single Trajectory Reinforcement
  Learning
abstract: "We consider the problem of learning high-performance Exploration/Exploitation
  (E/E) strategies for finite Markov Decision Processes (MDPs) when the MDP to be
  controlled is supposed to be drawn from a known probability distribution pM (Â·).
  The performance criterion is the sum of discounted rewards collected by the E/E
  strategy over an infinite length trajectory. We propose an approach for solving
  this problem that works by considering a rich set of candidate E/E strategies and
  by looking for the one that gives the best average performances on MDPs drawn according
  to pM (Â·). As candidate E/E strategies, we consider index-based strategies parametrized
  by small formulas combining variables that include the estimated reward function,
  the number of times each transition has occurred and the optimal value functions
  and the optimal value functions VË\x86 and QË\x86 of the estimated MDP (obtained
  through value iteration). The search for the best formula is formalized as a multi-armed
  bandit problem, each arm being associated with a formula. We experimentally compare
  the performances of the approach with R-max as well as with -Greedy strategies and
  the results are promising."
pdf: "./castronovo12a/castronovo12a.pdf"
layout: inproceedings
id: castronovo12a
month: 0
firstpage: 1
lastpage: 10
page: 1-10
origpdf: http://jmlr.org/proceedings/papers/v24/castronovo12a/castronovo12a.pdf
sections: 
author:
- given: Michael
  family: Castronovo
- given: Francis
  family: Maes
- given: Raphael
  family: Fonteneau
- given: Damien
  family: Ernst
date: '2013-01-12 00:00:01'
publisher: PMLR
---
