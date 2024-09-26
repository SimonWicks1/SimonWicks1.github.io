---
title: "Reward-Driven Automated Curriculum Learning for Interaction-Aware Self-Driving at Unsignalized Intersections"
collection: publications
category: conferences
# permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'This paper introduces a reward-driven automated curriculum learning framework for self-driving at unsignalized intersections, addressing uncertainties in surrounding vehicles' intentions and quantities. A progressive curriculum and well-designed reward function improve policy exploration and sample efficiency. Experiments in Highway-Env and CARLA show superior success rates, robustness, and adaptability, validating the method's effectiveness in handling complex driving interactions.'
date: 2024-06-31
venue: 'International Conference on Intelligent Robots and Systems (IROS) · IROS 2024. 14 October- 18 October 2024 | Abu Dhabi, UAE'
image_path: '/images/Curriculum Learning-IROS23.png'
# paperurl: 'https://ieeexplore.ieee.org/document/9456499'
# citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

<div>
    <a href="https://arxiv.org/abs/2405.16599" target="_blank">Paper Link</a>
</div>

## Abstract
In this work, we present a reward-driven automated curriculum reinforcement learning approach for interaction-aware self-driving at unsignalized intersections, taking into account the uncertainties associated with surrounding vehicles (SVs). These uncertainties encompass the uncertainty of SVs' driving intention and also the quantity of SVs. To deal with this problem, the curriculum set is specifically designed to accommodate a progressively increasing number of SVs. By implementing an automated curriculum selection mechanism, the importance weights are rationally allocated across various curricula, thereby facilitating improved sample efficiency and training outcomes. Furthermore, the reward function is meticulously designed to guide the agent towards effective policy exploration. Thus the proposed framework could proactively address the above uncertainties at unsignalized intersections by employing the automated curriculum learning technique that progressively increases task difficulty, and this ensures safe self-driving through effective interaction with SVs. Comparative experiments are conducted in Highway-Env, and the results indicate that our approach achieves the highest task success rate, attains strong robustness to initialization parameters of the curriculum selection module, and exhibits superior adaptability to diverse situational configurations at unsignalized intersections. Furthermore, the effectiveness of the proposed method is validated using the high-fidelity CARLA simulator.

## Overview
![IROS23](/images/Curriculum Learning-IROS23.png)

## Citation

```text
@article{RN17,
  title={{Reward-Driven Automated Curriculum Learning for Interaction-Aware Self-Driving at Unsignalized Intersections}},
  author={Peng, Zengqi and Zhou, Xiao and Zheng, Lei and Wang, Yubin and Ma, Jun},
  journal={arXiv preprint arXiv:2403.13674},
  year={2024}
}
```
