---
layout: post
title: Hybrid Event Shaping to Stabilize Periodic Hybrid Orbits
subtitle: Presented at ICRA 2022
cover-img: /assets/img/paddle_juggler.jpg
thumbnail-img: /assets/img/paddle_juggler.jpg
share-img: /assets/img/paddle_juggler.jpg
tags: [hybrid systems]
---

Many controllers for legged robotic systems leverage open- or closed-loop control at discrete hybrid events to enhance stability. These controllers appear in several well studied phenomena such as the Raibert stepping controller, paddle juggling, and swing leg retraction. This work introduces
hybrid event shaping (HES): a generalized method for analyzing and designing stable hybrid event controllers. HES utilizes the
saltation matrix, which gives a closed-form equation for the effect that hybrid events have on stability. We also introduce shape parameters, which are higher order terms that can be tuned completely independently of the system dynamics to promote stability. Optimization methods are used to produce values of these parameters that optimize a stability measure. Hybrid event shaping captures previously developed control methods while also producing new optimally stable trajectories without the need for continuous-domain feedback.

Read the paper [here](https://arxiv.org/abs/2110.01123) on Arxiv:

Here is the poster presented at ICRA 2022:

<img src="/assets/img/hybrid_event_shaping_icra_2022.pdf" alt="HES Poster" width="800" class="center"/>

Watch the video attachment here:

[![HES_video_attachment](http://img.youtube.com/vi/EqIjG2cCX5w/0.jpg)](https://www.youtube.com/watch?v=EqIjG2cCX5w "Hybrid Event Shaping Video Attachment")

Watch my presentation at ICRA here:

[![HES_ICRA_presentation](https://img.youtube.com/vi/oLRKRzsb5uo/0.jpg)](https://www.youtube.com/watch?v=oLRKRzsb5uo "Hybrid Event Shaping ICRA Presentation")