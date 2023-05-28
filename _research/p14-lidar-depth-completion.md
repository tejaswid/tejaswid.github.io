---
title: "3D Lidar Reconstruction with Probabilistic Depth Completion"
excerpt: "Learning-based uncertainty-aware depth completion.<br/> <img src='/images/lidar-depth-completion.png'>"
collection: research
---

<img src='/images/lidar-depth-completion.png'>

This work is chiefly part of Yifu Tao's doctoral thesis.

Learning-based uncertainty-aware depth completion is used to densify sparse lidar measurements with vision. 
A 16-beam lidar input and camera images are processed to reconstruct (with explicit free space) a reconstruction of quality that is similar to what can be achieved by using a 64-beam lidar. We deployed this on a legged robot platform (Boston Dynamics Spot) with a multi-camera setup and the depth completion network could run on a mobile GPU at 10 Hz.

For further details, please refer to the following publication.  
Y. Tao, M. Popović, Y. Wang, S. Digumarti, N. Chebrolu, and M. Fallon, “3D Lidar Reconstruction with Probabilistic Depth Completion for Robotic Navigation”, in IEEE/RSJ Intl. Conf. on Intelligent Robots and Systems (IROS), 2022  
([paper](https://arxiv.org/pdf/2207.12520.pdf)|[website](https://ori.ox.ac.uk/labs/drs/depth-completion/))


<img src='/images/lidar-depth-completion-overview.png'>
An overview of the proposed framework.

<img src='/images/lidar-depth-completion-mesh-reconstruction.png'>
Mesh reconstructions from the proposed approach compared against ground truth - (top) monocular camera, (bottom) multi-camera setup.

<iframe width="560" height="315" src="https://www.youtube.com/embed/db3HetMq5h4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>