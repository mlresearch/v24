---
title: Actor-Critic Reinforcement Learning with Energy-Based Policies
abstract: We consider reinforcement learning in Markov decision processes with high
  dimensional state and action spaces. We parametrize policies using energy-based
  models (particularly restricted Boltzmann machines), and train them using policy
  gradient learning. Our approach builds upon Sallans and Hinton (2004), who parameterized
  value functions using energy-based models, trained using a non-linear variant of
  temporal-difference (TD) learning. Unfortunately, non-linear TD is known to diverge
  in theory and practice. We introduce the first sound and efficient algorithm for
  training energy-based policies, based on an actor-critic architecture. Our algorithm
  is computationally efficient, converges close to a local optimum, and outperforms
  Sallans and Hinton (2004) in several high dimensional domains.
pdf: "./heess12a/heess12a.pdf"
layout: inproceedings
key: heess12a
month: 0
firstpage: 45
lastpage: 58
origpdf: http://jmlr.org/proceedings/papers/v24/heess12a/heess12a.pdf
sections: 
authors:
- given: Nicolas
  family: Heess
- given: David
  family: Silver
- given: Yee Whye
  family: Teh
---
