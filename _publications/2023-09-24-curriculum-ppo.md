---
title: "Curriculum Proximal Policy Optimization with Stage-Decaying Clipping for Self-Driving at Unsignalized Intersections"
collection: publications
category: conferences
excerpt: "This paper proposes a curriculum proximal policy optimization (CPPO) framework with stage-decaying clipping for self-driving at unsignalized intersections. A large clipping parameter enables rapid search for an approximately optimal policy, while a smaller one in later stages ensures convergence. Stage-based curriculum learning and curriculum-specific reward design further improve generalization and accelerate training in intersection-crossing scenarios."
date: 2023-09-24
venue: 'The 26th IEEE International Conference on Intelligent Transportation Systems (ITSC). 24 Sep- 28 Sep 2023 | Bilbao, Spain'
---

<div>
    <a href="https://ieeexplore.ieee.org/document/10422594" target="_blank">Paper Link</a> | <a href="https://arxiv.org/abs/2308.16445" target="_blank">arXiv</a>
</div>

## Abstract
Unsignalized intersections are typically considered as one of the most representative and challenging scenarios for self-driving vehicles. To tackle autonomous driving problems in such scenarios, this paper proposes a curriculum proximal policy optimization (CPPO) framework with stage-decaying clipping. By adjusting the clipping parameter during different stages of training through proximal policy optimization (PPO), the vehicle can first rapidly search for an approximate optimal policy or its neighborhood with a large parameter, and then converges to the optimal policy with a small one. Particularly, the stage-based curriculum learning technology is incorporated into the proposed framework to improve the generalization performance and further accelerate the training process. Moreover, the reward function is specially designed in view of different curriculum settings. A series of comparative experiments are conducted in intersection-crossing scenarios with bi-lane carriageways to verify the effectiveness of the proposed CPPO method. The results show that the proposed approach demonstrates better adaptiveness to different dynamic and complex environments, as well as faster training speed over baseline methods.

## Citation
```text
@INPROCEEDINGS{peng2023curriculum,
  author={Peng, Zengqi and Zhou, Xiao and Wang, Yubin and Zheng, Lei and Liu, Ming and Ma, Jun},
  booktitle={2023 IEEE 26th International Conference on Intelligent Transportation Systems (ITSC)}, 
  title={Curriculum Proximal Policy Optimization with Stage-Decaying Clipping for Self-Driving at Unsignalized Intersections}, 
  year={2023},
  pages={5027-5033},
  doi={10.1109/ITSC57777.2023.10422594}}
```
