---
title: "Semantic Segmentation of Tree Structure Using Deep Convolutional Neural Networks"
excerpt: "A deel learning based framework for semantic segmentation of trees into their components.<br/> <img src='/images/tree_seg_real.png'>"
collection: projects
---
  
In this project we developed a pipeline for semantic segmentation of trees into their components. Given a single RGB-D image of a tree, we employ a deep network to predict labels to clasify each pixel into trunk, branch, twig or leaf. We further evaluated and compared the performance of multiple network architectures that combine the complementary modlities of colour and depth. 

A paper on this will be presented at the IEEE International Conference on Robotics and Automation, 2019.

<img src='/images/tree_seg_network.png'>  
Figure shows the proposed late fusion architecture and the other architectures evaluated in this project.

<img src='/images/tree_seg_real.png'>  
Figure shows qualitative results of different architectures on real world data.