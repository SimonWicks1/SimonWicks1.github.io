---
title: "SocialTraj: Two-Stage Socially-Aware Trajectory Prediction for Autonomous Driving via Conditional Diffusion Model"
collection: publications
category: manuscripts
excerpt: "SocialTraj integrates social value orientation (SVO) into trajectory prediction for autonomous driving. The SVOs of surrounding vehicles are estimated with Bayesian inverse reinforcement learning and embedded into a conditional denoising diffusion model, together with the planned trajectory of the ego vehicle. Experiments on NGSIM and HighD show socially compliant, behaviorally consistent predictions that outperform existing baselines."
date: 2026-06-20
venue: 'IEEE TRANSACTIONS ON VEHICULAR TECHNOLOGY'
---

<div>
    <a href="https://doi.org/10.1109/TVT.2026.3716670" target="_blank">Paper Link</a> | <a href="https://arxiv.org/abs/2509.17850" target="_blank">arXiv</a>
</div>

## Abstract
Accurate trajectory prediction of surrounding vehicles (SVs) is crucial for autonomous driving systems to avoid misguided decisions and potential accidents. However, achieving reliable predictions in highly dynamic and complex traffic scenarios remains a significant challenge. One of the key impediments lies in the limited effectiveness of current approaches to capture the multi-modal behaviors of drivers, which leads to predicted trajectories that deviate from actual future motions. To address this issue, we propose SocialTraj, a novel trajectory prediction framework integrating social psychology principles through social value orientation (SVO). By utilizing Bayesian inverse reinforcement learning (IRL) to estimate the SVO of SVs, we obtain the critical social context to infer the future interaction trend. To ensure modal consistency in predicted behaviors, the estimated SVOs of SVs are embedded into a conditional denoising diffusion model that aligns generated trajectories with historical driving styles. Additionally, the planned future trajectory of the ego vehicle (EV) is explicitly incorporated to enhance interaction modeling. Extensive experiments on NGSIM and HighD datasets demonstrate that SocialTraj is capable of adapting to highly dynamic and interactive scenarios while generating socially compliant and behaviorally consistent trajectory predictions, outperforming existing baselines. Ablation studies demonstrate that dynamic SVO estimation and explicit ego-planning components notably improve prediction accuracy and substantially reduce inference time.

## Citation
```text
@ARTICLE{zhou2026socialtraj,
  author={Zhou, Xiao and Peng, Zengqi and Song, Yang and Lin, Junan and Ma, Jun},
  journal={IEEE Transactions on Vehicular Technology}, 
  title={SocialTraj: Two-Stage Socially-Aware Trajectory Prediction for Autonomous Driving via Conditional Diffusion Model}, 
  year={2026},
  doi={10.1109/TVT.2026.3716670}}
```
