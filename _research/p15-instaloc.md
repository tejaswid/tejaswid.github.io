---
title: "Indoor LiDAR Localization through Instance Learning"
excerpt: "One-shot Global Lidar Localisation in Indoor Environments through Instance Learning.<br/> <img src='/images/instaloc.png'>"
collection: research
---

<img src='/images/instaloc.png'>

This work is chiefly part of Lintong Zhang's doctoral thesis.

A localization framework for indoor environments called InstaLoc, which operates on an individual lidar scan to localize it within a prior map is developed. We draw on inspiration from how humans navigate and position themselves by recognizing the layout of distinctive objects and structures. Mimicking the human approach, InstaLoc identifies and matches object instances in the scene with those from a prior map. As far as we know, this is the first method to use panoptic segmentation directly inferring on 3D lidar scans for indoor localization. InstaLoc operates through two networks based on spatially sparse tensors to directly infer dense 3D lidar point clouds. The first network is a panoptic segmentation network that produces object instances and their semantic classes. The second smaller network produces a descriptor for each object instance. A consensus based matching algorithm then matches the instances to the prior map and estimates a six degrees of freedom (DoF) pose for the input cloud in the prior map. The significance of InstaLoc is that it has two efficient networks. It requires only one to two hours of training on a mobile GPU and runs in real-time at 1 Hz. Our method achieves between two and four times more detections when localizing, as compared to baseline methods, and achieves higher precision on these detections.

For further details, please refer to the following publication.  
Zhang L., Digumarti, S.T., Tinchev, G. and Fallon, M., 2023. "InstaLoc: One-shot Global Lidar Localisation in Indoor Environments through Instance Learning." Robotics: Science and Systems (RSS) (to appear) ([link](https://arxiv.org/abs/2305.09552))

<img src='/images/instaloc.png'>
An overview of the proposed framework.

<img src='/images/instaloc-segmentation.png'>
Results of segmentation (left) simulated scan, (right) real scan.

<img src='/images/instaloc-results.png'>
Results of the proposed framework in comparison to state-of-the-art benchmarks.