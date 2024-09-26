---
title: "Integrated Intention Prediction and Decision-Making with Spectrum Attention Net and Proximal Policy Optimization"
collection: publications
category: conferences
# permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'This paper presents an integrated intention prediction and decision-making framework for autonomous driving. A spectrum attention net predicts surrounding vehicle intentions efficiently by analyzing frequency components, while the proximal policy optimization (PPO) algorithm addresses non-stationary issues with policy updates. Joint learning integrates both modules, and experiments demonstrate superior performance in safety, efficiency, and success rates compared to deep reinforcement learning baselines.'
date: 2024-07-10
venue: ' The 27th IEEE International Conference on Intelligent Transportation Systems. 24 Sep- 27 Sep 2024 | Edmonton, Canada'
image_path: '/images/Intention_frequency.png'
# paperurl: 'https://ieeexplore.ieee.org/document/9456499'
# citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

<div>
    <a href="https://arxiv.org/pdf/2408.03191" target="_blank">Paper Link</a>
</div>


## Abstract
For autonomous driving in highly dynamic environments, it is anticipated to predict the future behaviors of surrounding vehicles (SVs) and make safe and effective decisions. However, modeling the inherent coupling effect between the prediction and decision-making modules has been a long-standing challenge, especially when there is a need to maintain appropriate computational efficiency. To tackle these problems, we propose a novel integrated intention prediction and decision-making approach, which explicitly models the coupling relationship and achieves efficient computation. Specifically, a spectrum attention net is designed to predict the intentions of SVs by capturing the trends of each frequency component over time and their interrelations. Fast computation of the intention prediction module is attained as the predicted intentions are not decoded to trajectories in the executing process. Furthermore, the proximal policy optimization (PPO) algorithm is employed to address the non-stationary problem in the framework through a modest policy update enabled by a clipping mechanism within its objective function. On the basis of these developments, the intention prediction and decision-making modules are integrated through joint learning. Experiments are conducted in representative traffic scenarios, and the results reveal that the proposed integrated framework demonstrates superior performance over several deep reinforcement learning (DRL) baselines in terms of success rate, efficiency, and safety in driving tasks.


## Overview
![Intention_frequency](/images/Intention_frequency.png)


## Citation
``` text
@inproceedings{zhou2024integrated,
  title={Integrated Intention Prediction and Decision-Making with Spectrum Attention Net and Proximal Policy Optimization},
  author={Zhou, Xiao and Meng, Chengzhen and Liu, Wenru and Peng, Zengqi and Liu, Ming and Ma, Jun},
  booktitle={Proc. 27th Int. IEEE Conf. Intell. Transp. Syst. (ITSC)},
  year={Sep. 2024}
}
```
