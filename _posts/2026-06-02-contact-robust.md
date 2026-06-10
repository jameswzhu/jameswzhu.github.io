---
layout: post
title: Contact-Robust Trajectory Planning via Parametric Sensitivity Analysis for Hybrid Robotic Systems
subtitle: 2026 IEEE ICRA
thumbnail-img: /assets/img/soft_landing.png
share-img: /assets/img/soft_landing.png
tags: [legged robots, robust control]
---

<style>
  .button {
    display: inline-block;
    padding: 10px 15px;
    margin: 10px 0;
    font-size: 16px;
    color: #FFF5EE;
    background: #ED745E;
    text-decoration: none;
    border-radius: 5px;
    font-weight: 600;
    border: 2px solid #EDC75E
  }
  .button:hover { background: #ED745E; color: #FFF5EE; }
</style>

In this paper, we combine first-order approximations of hybrid systems (i.e., the so-called saltation matrix) with previous works on parametric sensitivity for continuous systems to propose a general framework for robust trajectory optimization of hybrid systems subject to parametric uncertainties. 
A method for computing parametric sensitivities of both continuous dynamics and hybrid events is presented. 
The obtained “hybrid parametric sensitivity” is then combined with sensitivity-based tubes that encapsulate all possible perturbed states and control trajectories given a known bounded range for the uncertain parameters. 
The proposed method is then applied to the problem of planning robust trajectories for legged robot systems, which allows obtaining trajectories that remain feasible w.r.t. the contact constraints even in presence of uncertainties in the dynamics, guard conditions, and reset maps. 
We also illustrate one of the fundamental limitations of first-order approximations, that is, the fact that the sensitivity reset time is fixed, and propose an extension to the sensitivity analysis that can form the basis for future developments.

## Read the Paper  
[Read the full paper on IEEE Xplore](https://hal.science/hal-05488973/document){: .button}
