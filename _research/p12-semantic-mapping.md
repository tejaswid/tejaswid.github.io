---
title: "Semantic Mapping"
excerpt: "Strategies for large scale elastic and semantic LiDAR reconstruction.<br/> <img src='/images/semantic-mapping.png'>"
collection: research
---

<img src='/images/semantic-mapping.png'>

This work is chiefly part of Yiduo Wang's doctoral thesis.

In this work we investigated novel strategies for spawning and fusing submaps within an elastic dense 3D reconstruction system. Spatial understanding of the scanned environment was used to control memory usage growth by fusing overlapping submaps in different ways. This allowed the number of submaps and memory consumption to scale with the size of the environment rather than the duration of exploration. By analysing spatial overlap and semantic information, our system segments distinct spaces on-the-fly during exploration, such as rooms, stairwells, and indoor–outdoor transitions. The proposed system associates semantically labelled submaps with poses of SLAM pose graph to enable global elasticity. A probabilistic model to merge the voxel labels of the different submaps is incorporated to ensure correct semantic submap fusion when SLAM loop closures occur. 

For further details please refer to the following publication.
Wang, Y., Ramezani, M., Mattamala, M., Digumarti, S.T. and Fallon, M., "Strategies for large scale elastic and semantic LiDAR reconstruction" in Robotics and Autonomous Systems, 2022, 155, p.104185' ([link](https://www.sciencedirect.com/science/article/pii/S0921889022001075))

<img src='/images/semantic-mapping-overview.png'>
An overview of the framework.

<img src='/images/semantic-mapping-segmentation.png'>
Semantic egmentation results on a representative image.

<img src='/images/semantic-mapping-result.png'>
Reconstruction with voxels coloured based on their semantic category.


<iframe width="560" height="315" src="https://www.youtube.com/embed/GwS2KqP3lLo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>