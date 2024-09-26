---
title: "Game-Theoretic Driver Modeling and Decision-Making for Autonomous Driving with Temporal-Spatial Attention-Based Deep Q-Learning"
collection: publications
category: manuscripts
# permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'A game-theoretic driver modeling and decision-making framework with level-k reasoning for autonomous vehicles is proposed. A temporal-spatial attention-based deep Q-learning (TSA-DQN) algorithm is developed to estimate the decision level of surrounding vehicles and optimize ego vehicle’s decision. Simulations demonstrate improved safety, efficiency, and success rates over baselines in various driving scenarios. Real-world testing further confirms the algorithm's practical feasibility.'
date: 2024-09-25
venue: 'IEEE TRANSACTIONS ON INTELLIGENT VEHICLES'
# slidesurl: 'https://ieeexplore.ieee.org/document/9770363'
image_path: '/images/Level_k.png'
# paperurl: 'https://ieeexplore.ieee.org/document/9456499'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

<!-- <div>
    <a href="https://ieeexplore.ieee.org/document/9770363" target="_blank">Paper Link</a>
</div> -->

## Abstract
The safe and efficient navigation of autonomous vehicles in complex traffic scenarios remains a significant challenge. One of the key impediments is the limited effectiveness of current methods in constructing driver models for surrounding vehicles (SVs) that capture diverse decision-making abilities. As
a result, implementing decision-making algorithms for the ego vehicle (EV) based on such models could result in unfortunate accidents due to misinterpretation of the decision-making of SVs. To deal with this problem, this paper first introduces a novel decision-making framework that incorporates a game-theoretic driver model based on level-k reasoning. For the SVs, driver models at different decision levels are established with an iterative level-k reasoning algorithm. As supported by rigorous proof, the strategies of SVs corresponding to these driver models converge to the Nash equilibrium. Following this, utilizing these driver models characterized by mixed decision levels, we propose a temporal-spatial attention-based deep Q-learning (TSA-DQN) algorithm to approximate the optimal policy for the EV and generate respective decisions in various scenarios. It is noteworthy that the proposed algorithm leverages a temporal attention network to estimate the decision level of SVs and spatial attention mechanisms to generate decisions while capturing the interactions
between vehicles. Simulations are conducted in representative traffic scenarios, and the results reveal that the proposed driver
model based on level-k game theory effectively captures the behaviors of diverse drivers. On this basis, the proposed TSA-DQN algorithm demonstrates superior performance over several deep reinforcement learning (DRL) baselines in terms of success rate, efficiency, and safety in driving tasks. Furthermore, the
TSA-DQN algorithm is deployed to the real-world hardware platform to illustrate its effectiveness and practical feasibility.

## Overview
![Level_k](/images/Level_k.png)

<!-- ## Citation
```text

@ARTICLE{9770363,
  author={Xie, Yusen and Deng, Lei and Sun, Ting and Fu, Yeyu and Li, Jian and Cui, Xinglong and Yin, Hanxi and Deng, Shuixin and Xiao, Junwei and Chen, Baohua},
  journal={IEEE Robotics and Automation Letters}, 
  title={A4LidarTag: Depth-Based Fiducial Marker for Extrinsic Calibration of Solid-State Lidar and Camera}, 
  year={2022},
  volume={7},
  number={3},
  pages={6487-6494}}

``` -->