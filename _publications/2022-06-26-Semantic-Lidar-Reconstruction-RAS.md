---
title: "Strategies for large scale elastic and semantic LiDAR reconstruction"
collection: publications
permalink: /publication/2022-06-26-Semantic-Lidar-Reconstruction-RAS
excerpt: ''
date: 2022-06-26
venue: 'Robotics and Autonomous Systems'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S0921889022001075'
citation: 'Wang, Y., Ramezani, M., Mattamala, M., Digumarti, S.T. and Fallon, M., 2022. &quot;Strategies for large scale elastic and semantic LiDAR reconstruction.&quot; <i>Robotics and Autonomous Systems</i>, 155, p.104185'

---
## Abstract
This paper presents novel strategies for spawning and fusing submaps within an elastic dense 3D reconstruction system. The proposed system uses spatial understanding of the scanned environment to control memory usage growth by fusing overlapping submaps in different ways. This allows the number of submaps and memory consumption to scale with the size of the environment rather than the duration of exploration. By analysing spatial overlap and semantic information, our system segments distinct spaces on-the-fly during exploration, such as rooms, stairwells, and indoor–outdoor transitions. The proposed system associates semantically labelled submaps with poses of SLAM pose graph to enable global elasticity. A probabilistic model to merge the voxel labels of the different submaps is incorporated to ensure correct semantic submap fusion when SLAM loop closures occur. Additionally, we present a new mathematical formulation of relative uncertainty between poses to improve the global consistency of the reconstruction. Performance is demonstrated using experiments exploring multi-floor multi-room indoor environments, indoor–outdoor transitions and large-scale outdoor experiments. Relative to our baseline, the presented approach demonstrates improved scalability and accuracy.