---
layout: post
title: Hybrid Event Shaping to Stabilize Periodic Hybrid Orbits
subtitle: 2022 IEEE ICRA
thumbnail-img: /assets/img/paddle_juggler.jpg
share-img: /assets/img/paddle_juggler.jpg
tags: [legged robots, robust control]
---

  body { 
    font-family: 'Figtree', sans-serif; 
    line-height: 1.6; 
    max-width: 800px; 
    margin: auto; 
    padding: 20px; 
    color: #00001a;
  }
  h1 { color: #745EED; text-align: center; font-weight: 600; }
  h2 { color: #8BD1DA; font-weight: 600; }
  p { font-size: 16px; }
  .video-thumbnail { text-align: center; margin-top: 20px; }
  .button {
    display: inline-block;
    padding: 10px 15px;
    margin: 10px 0;
    font-size: 16px;
    color: white;
    background: #745EED;
    text-decoration: none;
    border-radius: 5px;
    font-weight: 600;
  }
  .button:hover { background: #8BD1DA; color: #00001a; }
</style>

Hybrid Event Shaping (HES) is a novel control method for stabilizing legged robots by optimizing discrete events like footfalls and impacts. Using the saltation matrix, HES provides a closed-form approach to analyze stability and introduces shape parameters—higher-order terms that enhance stability independently of system dynamics. 

By leveraging optimization techniques, HES unifies existing control strategies (e.g., Raibert stepping) while generating new, optimally stable motions without requiring continuous feedback.

## Read the Paper  
[Read the full paper on IEEE Xplore](https://ieeexplore.ieee.org/document/9811782){: .button}

## Watch the ICRA Presentation  
<div class="video-thumbnail">
  <a href="https://www.youtube.com/watch?v=oLRKRzsb5uo" title="Hybrid Event Shaping ICRA Presentation">
    <img src="https://img.youtube.com/vi/oLRKRzsb5uo/0.jpg" alt="HES ICRA Presentation Thumbnail" width="100%">
  </a>
</div>
