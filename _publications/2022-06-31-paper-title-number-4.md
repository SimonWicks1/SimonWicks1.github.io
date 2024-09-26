---
title: "Putn: A plane-fitting based uneven terrain navigation framework"
collection: publications
category: conferences
# permalink: /publication/2024-02-17-paper-title-number-4
excerpt: "This paper proposes a Plane-Fitting based Uneven Terrain Navigation (PUTN) framework for autonomous ground robots in unstructured 3D environments. PUTN combines an improved Plane Fitting RRT* for sparse trajectory generation, Gaussian Process Regression for trajectory interpolation, and Nonlinear Model Predictive Control (NMPC) for local planning. Experiments demonstrate PUTN's robust, safe motion planning in uneven terrain, validated through real-world testing."
date: 2022-07-10
venue: ' International Conference on Intelligent Robots and Systems (IROS) · IROS 2022. 23 October- 27 October 2022 | Kyoto, Japan'
image_path: '/images/IROS22.png'
# paperurl: 'https://ieeexplore.ieee.org/document/9456499'
# citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

<div>
    <a href="https://ieeexplore.ieee.org/abstract/document/9981038" target="_blank">Paper Link</a>
</div>

## Abstract
Autonomous navigation of ground robots has been widely used in indoor structured 2D environments, but there are still many challenges in outdoor 3D unstructured environments, especially in rough, uneven terrains. This paper proposed a plane-fitting based uneven terrain navigation framework (PUTN) to solve this problem. The implementation of PUTN is divided into three steps. First, based on Rapidly-exploring Random Trees (RRT), an improved sample-based algorithm called Plane Fitting RRT*(PF- RRT*) is proposed to obtain a sparse trajectory. Each sampling point corresponds to a custom traversability index and a fitted plane on the point cloud. These planes are connected in series to form a traversable “strip”. Second, Gaussian Process Regression is used to generate traversability of the dense trajectory interpolated from the sparse trajectory, and the sampling tree is used as the training set. Finally, local planning is performed using nonlinear model predictive control (NMPC). By adding the traversability index and uncertainty to the cost function, and adding obstacles generated by the real-time point cloud to the constraint function, a safe motion planning algorithm with smooth speed and strong robustness is available. Experiments in real scenarios are conducted to verify the effectiveness of the method. 

## Overview
![IROS22](/images/IROS22.png)

## Citation

```text
@INPROCEEDINGS{9981038,
  author={Jian, Zhuozhu and Lu, Zihong and Zhou, Xiao and Lan, Bin and Xiao, Anxing and Wang, Xueqian and Liang, Bin},
  booktitle={2022 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)}, 
  title={PUTN: A Plane-fitting based Uneven Terrain Navigation Framework}, 
  year={2022},
  volume={},
  number={},
  pages={7160-7166},
  keywords={Point cloud compression;Training;Strips;Uncertainty;Three-dimensional displays;Navigation;Trajectory},
  doi={10.1109/IROS47612.2022.9981038}}
```