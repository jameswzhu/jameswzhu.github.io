---
layout: post
title: Convergent iLQR for Safe Trajectory Planning and Control of Legged Robots
subtitle: 2024 IEEE ICRA
thumbnail-img: /assets/img/quad_comparison.jpg
share-img: /assets/img/quad_comparison.jpg
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

Legged robots often perform dynamic maneuvers in underactuated domains, where they have limited control over acceleration and are highly sensitive to disturbances during transitions (e.g., foot touchdown). This makes it challenging for traditional feedback controllers to recover from perturbations. To address this, the paper uses worst-case perturbation analysis based on a fundamental solution matrix to optimize hybrid trajectories. Incorporating this analysis into an iLQR framework, the optimized trajectories exhibit better recovery from disturbances, are more robust to large perturbations, and require less feedback control effort compared to conventional optimization methods.

## Read the Paper  
[Read the full paper on IEEE Xplore](https://ieeexplore.ieee.org/document/10611641){: .button}

## Watch the ICRA Presentation  
[Watch the conference presentation on YouTube](https://www.youtube.com/watch?v=EaUzGOmvvlM){: .button}
