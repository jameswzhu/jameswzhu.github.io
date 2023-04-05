---
layout: post
title: Convergent iLQR for Safe Trajectory Planning and Control of Legged Robots
subtitle: Submitted to IEEE CDC 2023
cover-img: /assets/img/quad_comparison.jpg
thumbnail-img: /assets/img/quad_comparison.jpg
share-img: /assets/img/quad_comparison.jpg
tags: [hybrid systems]
---

In order to perform highly dynamic and agile maneuvers, legged robots typically spend time in underactuated domains (e.g. with feet off the ground) where the system has limited command of its acceleration and a constrained amount of time before transitioning to a new domain (e.g. foot touchdown). Meanwhile, these transitions can have instantaneous, unbounded effects on perturbations. These properties make it difficult for local feedback controllers to effectively recover from disturbances as the system evolves through underactuated domains and hybrid impact events. To address this, we utilize the fundamental solution matrix that characterizes the evolution of perturbations through a hybrid trajectory and its 2-norm, which represents the worst-case growth of perturbations. In this paper, the worst-case perturbation analysis is used to explicitly reason about the tracking performance of a hybrid trajectory and is incorporated in an iLQR framework to optimize a trajectory while taking into account the closed-loop convergence of the trajectory under an LQR tracking controller. The generated convergent trajectories are able to recover more effectively from perturbations, are more robust to large disturbances, and use less feedback control effort than trajectories generated with traditional optimization methods.

Read the paper [here](https://arxiv.org/abs/2304.00346)
