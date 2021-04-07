---
title: "Semantic Segmentation of Tree Structure Using Deep Convolutional Neural Networks"
excerpt: "A deep learning based framework for semantic segmentation of trees into their components.<br/> <img src='/images/tree_seg_real.png'>"
collection: research
---
  
In this project we developed a pipeline for semantic segmentation of trees into their components. Given a single RGB-D image of a tree, we employ a deep network to predict labels to clasify each pixel into trunk, branch, twig or leaf. We further evaluated and compared the performance of multiple network architectures that combine the complementary modlities of colour and depth. 

Refer to the following publication for further details.  
Digumarti, S. T., Schmid, L. M., Rizzi, G. M., Nieto, J., Siegwart, R., Beardsley, P., & Cadena, C. (2019, May). "An approach for semantic segmentation of tree-like vegetation." IEEE International Conference on Robotics and Automation (ICRA), 3(4), pp. 1801-1807. ([link](https://ieeexplore.ieee.org/document/8793576))

<img src='/images/tree_seg_network.png'>  
Figure shows the proposed late fusion architecture and the other architectures evaluated in this project.

<img src='/images/tree_seg_real.png'>  
Figure shows qualitative results of different architectures on real world data.
