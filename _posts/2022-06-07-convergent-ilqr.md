---
layout: post
title: Convergent iLQR for Underactuated Hybrid Dynamical Systems
subtitle: Accepted to RSS 2022 Risk Aware Decision Making Workshop
cover-img: /assets/img/cl_hist.jpg
thumbnail-img: /assets/img/cl_hist.jpg
share-img: /assets/img/cl_hist.jpg
tags: [hybrid systems]
---

In order to perform highly dynamic and agile maneuvers, legged systems often must spend a significant amount of time in underactuated domains 
(i.e. with feet off the ground during a jump), where the system can not command an acceleration in every direction of its state space. 
Additionally, these systems usually only have a limited amount of time before transitioning to a new domain (i.e. foot touchdown). Even if the
system is controllable in these underactuated domains, standard LQR controllers only guarantee stability over some finite time that may exceed the amount of time
the system spends in the underactuated domain. This work proposes a modification to iLQR for hybrid systems to generate trajectories that are more 
open-loop convergent, making them easier to stabilize with the associated time-varying LQR controller. Examples demonstrate how this convergent iLQR
can improve performance of underactuated legged robotic systems.
