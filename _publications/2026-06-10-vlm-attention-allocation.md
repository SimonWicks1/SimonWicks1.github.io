---
title: "Behavioral Uncertainty-Aware Attention Allocation via VLMs for Interactive Autonomous Driving"
collection: publications
category: manuscripts
excerpt: "This paper addresses how an autonomous vehicle with limited onboard computation should allocate attention among surrounding vehicles. The behavioral uncertainty of surrounding drivers is modeled in terms of micro-level cooperativeness and macro-level intentions, and is combined with multimodal scene information and attention memory in a structured prompt, enabling a vision-language model (VLM) to allocate attention to the vehicles that pose genuine threats. Experiments show higher success rates than baselines and improved robustness as traffic density increases."
date: 2026-06-10
venue: 'IEEE TRANSACTIONS ON VEHICULAR TECHNOLOGY'
---

<div>
    <a href="https://doi.org/10.1109/TVT.2026.3713420" target="_blank">Paper Link</a>
</div>

## Abstract
To navigate interactive traffic with limited onboard computational resources, an autonomous vehicle (AV) must selectively allocate its attention to the surrounding vehicles (SVs) that pose the greatest impact on their future motion. Existing attention allocation approaches fail to fully account for the SVs' behavioral uncertainty, leading to their poor performance in complex interactive scenarios. To address these issues, this paper proposes a behavioral uncertainty-aware attention allocation method via vision-language models (VLMs) for autonomous driving. Behavioral uncertainty is first categorized into micro-dimensional cooperativeness as well as macro-dimensional intentions, and the interactive behaviors of the SVs are predicted with comprehensive consideration of such uncertainties. Subsequently, the behavioral uncertainty data, combined with multimodal information of the current situation and attention allocation memories of the historical situation, is elaborately arranged in the designed template as the prompt for VLMs. Leveraging the multimodal information in the prompt, VLMs are required to conduct situation understanding, explicitly analyze the impact of the SVs on the AV's motion, and allocate attention to the SVs that pose real threats to the AV's motion. Comprehensive results demonstrate that the proposed approach outperforms baselines in success rates across a wide range of complex interactive scenarios. Furthermore, our method maintains remarkable resilience and exhibits excellent robustness as traffic density increases.

## Citation
```text
@ARTICLE{ma2026behavioral,
  author={Ma, Benshan and Liu, Haichao and Zhong, Ruiguo and Liu, Pei and Zhou, Xiao and Ma, Jun},
  journal={IEEE Transactions on Vehicular Technology}, 
  title={Behavioral Uncertainty-Aware Attention Allocation via VLMs for Interactive Autonomous Driving}, 
  year={2026},
  doi={10.1109/TVT.2026.3713420}}
```
