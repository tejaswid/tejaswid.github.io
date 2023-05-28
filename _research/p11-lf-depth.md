---
title: "Learning to See with Sparse Light Field Video Cameras"
excerpt: "Generalized unsupervised odometry and depth estimation on sparse 4D light fields.<br/> <img src='/images/lf-depth.jpg'>"
collection: research
---

[Project Webpage](https://roboticimaging.org/Projects/LearnLFOdo/) | 
[Code](https://github.com/RoboticImaging/LearnLFOdo_IROS2021) | 
[Data Request](http://mediathinktank.com/datarequest/) | 
[Dataset Readme](https://roboticimaging.org/Projects/LearnLFOdo/Dataset/README.html)

Learning to use new kinds of cameras in robotics applications is challenging and time-consuming. This work represents a first step toward streamlining the integration of new kinds of imaging devices into robotics applications. We use unsupervised learning to simultaneously learn metric depth and odometry using an emerging sensing technology, the sparse light field (LF) camera.

- We generalize unsupervised odometry and depth estimation to operate on sparse 4D light fields
- We introduce an encoding scheme for sparse LFs appropriate for odometry and shape estimation
- We outperform the monocular approach, yielding more accurate trajectories and depth maps with known scale

We expect our method to work well with other cameras with regular overlapping views: regularly spaced 1D and 2D camera arrays, sparse cameras like the EPIModule, and lenslet-based plenoptic cameras like the Lytro and Raytrix devices.  

Refer to the following publication for further details.  
S. T. Digumarti, J. Daniel, A. Ravendran, R. Griffiths, and D. G. Dansereau, “Unsupervised learning of depth estimation and visual odometry for sparse light field cameras,” in Intelligent Robots and Systems (IROS), 2021.
([link](https://arxiv.org/abs/2103.11322))

**Acknowledgments**
We would like to thank EPIImaging LLC and the University of Sydney Aerospace, Mechanical and Mechatronic Engineering FabLab for their support, and the University of Sydney HPC service for providing HPC resources that contributed to the research results reported in this work.
