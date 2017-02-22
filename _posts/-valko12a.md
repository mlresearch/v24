---
title: Semi-Supervised Apprenticeship Learning
abstract: "In apprenticeship learning we aim to learn a good policy by observing the
  behavior of an expert or a set of experts. In particular, we consider the case where
  the expert acts so as to maximize an unknown reward function defined as a linear
  combination of a set of state features. In this paper, we consider the setting where
  we observe many sample trajectories (i.e., sequences of states) but only one or
  a few of them are labeled as expertsâ\x80\x99 trajectories. We investigate the conditions
  under which the remaining unlabeled trajectories can help in learning a policy with
  a good performance. In particular, we define an extension to the max-margin inverse
  reinforcement learning proposed by Abbeel and Ng [2004] where, at each iteration,
  the max-margin optimization step is replaced by a semi-supervised optimiza- tion
  problem which favors classifiers separating clusters of trajectories. Finally, we
  report empirical results on two grid-world domains showing that the semi-supervised
  algorithm is able to output a better policy in fewer iterations than the related
  algorithm that does not take the unlabeled trajectories into account."
pdf: "./valko12a/valko12a.pdf"
layout: inproceedings
key: valko12a
month: 0
firstpage: 131
lastpage: 142
origpdf: http://jmlr.org/proceedings/papers/v24/valko12a/valko12a.pdf
sections: 
authors:
- given: Michal
  family: Valko
- given: Mohammad
  family: Ghavamzadeh
- given: Alessandro
  family: Lazaric
---