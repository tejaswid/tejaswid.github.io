---
title: "Semantics for Forestry"
excerpt: "A framework for extracting tree structures from forest scale 3D point clouds.<br/> <img src='/images/forest-sem.png'>"
collection: research
---

<img src='/images/forest-semantics.png'>

We developed data-driven approaches to segment individual trees from 3D LiDAR (Emesent Hovermap) scans of forest point clouds. Once individual trees are extracted, parameters of interest to forestry such as the diameter at breast height (DBH), lean of the trunk, twist factor, presence of kinks and knots, yield and leaf area index can be computed by analysing the tree's geometry in 3D.

A key focus was on developing deep learning aided techniques for large-scale 3D point cloud segmentation and classification.

This was a collaboration between the University of Sydney (Dr. Mitch Bryson), the University of Tasmania (Dr. Winyu Chinthammit), Interpine and Forest and Wood Products Australia.

An auxiliary research objective was the generation of large amounds of realistic tree data in simulation for training deep networks. The 3D modelling software Blender, particularly a custom fork of the [Modular Tree](https://github.com/MaximeHerpin/modular_tree/tree/master) plugin, was used to achieve this.

<img src='/images/blender-trees.png'>