---
title: "Online Forest Mapping and Inventory Generation using Handheld LiDAR"
excerpt: "Realtime mapping of forests and online extraction of metrics from handheld LiDAR.<br/> <img src='/images/online-forestry.png'>"
collection: research
---

<img src='/images/online-forestry.png'>

In this work we develped an online mapping system for forest environments using a handheld LiDAR capable of real-time feedback for the operator to aid in the survey mission. Segmentation, tracking and estimation of DBH parameter was computed for individual trees in the forest. An accurate map of individual trees using a deformable pose-graph based SLAM system with loop closure detection to correct for odometry drift was maintained. We used a standard pose-graph based SLAM system with our main contribution being its application for large-scale forestry mapping. Multi-session mapping capability where data captured
during multiple runs can be merged in a post-processing step was developed. This system was demonstrated on challenging large scale datasets from ecological as well as commercial forests spanning several kilometres.

<img src='/images/trees-extracted.png'>
Input point cloud and individual trees extracted.

<img src='/images/finland-traj.png'>
Trajectories of three seperate scans in a commerical forest in Finland.

<img src='/images/online-forestry.png'>
Combined map from the above trajectories.

This work resulted in the following publications.  
- A. Proudman, M. Ramezani, S. T. Digumarti, N. Chebrolu and M. Fallon, "Towards Real-Time Forest Inventory using Handheld LiDAR." in Robotics and Autonomous Systems, 2022 ([link](https://www.sciencedirect.com/science/article/pii/S0921889022001397))

- N. Chebrolu, S. T. Digumarti and M. Fallon, "A Portable LiDAR System for Online Forestry Mapping" in ForestSAT, 2022

- A. Proudman, M. Ramezani, S. T. Digumarti, N. Chebrolu and M. Fallon, "Online Forest Mapping and Inventory Generation using Handheld LiDAR" in Workshop on Innovation in Forestry Robotics: Research and Industry Adoption, IEEE International
Conference on Robotics and Automation (ICRA), 2022