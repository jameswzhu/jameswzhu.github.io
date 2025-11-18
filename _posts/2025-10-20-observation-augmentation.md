---
layout: post
title: "Robust RL Navigation Via Sensitivity-Aware Observation Augmentation"
subtitle: 2025 IROS Workshop on The Art of Robustness: Surviving Failures in Robotics
thumbnail-img: /assets/img/observation_augmentation.png
share-img: /assets/img/observation_augmentation.png
tags: [thesis]
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

Reinforcement learning (RL) policies can exhibit impressive adaptability in unstructured environments, yet deploying them safely in the real world often requires extensive domain randomization and careful tuning of simulation parameters. This work introduces observation augmentation (OA), a lightweight method that enhances the robustness of an existing RL policy without any retraining. Leveraging model-based sensitivity analysis, OA predicts future state uncertainties and incorporates chance-constrained back-off terms directly into the policy’s observation space. This provides the policy with principled information about expected deviations from nominal trajectories, enabling safer decision-making under uncertainty. We validate the approach on a quadrotor gate-passing task using a PPO policy and an unscented Kalman filter for state and parameter estimation. Compared to the baseline policy, which fails frequently when moderate gate spacing and estimation errors induce collisions, OA reduces failure rates nearly by half while maintaining task success. These results show that sensitivity-aware observation augmentation can significantly improve robustness of RL controllers with minimal computational overhead, offering a practical pathway toward safer real-world deployment.

## Read the Thesis  
[See the workshop poster here](/assets/pdf/2025_IROS_Workshop_Poster.pdf){: .button}
