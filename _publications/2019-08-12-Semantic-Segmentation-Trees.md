---
title: "An Approach for Semantic Segmentation of Tree-like Vegetation"
collection: publications
permalink: /publication/2019-08-12-Automatic-Segmentation-Trees
excerpt: ''
date: 2019-08-12
venue: ' International Conference on Robotics and Automation (ICRA)'
paperurl: 'https://ieeexplore.ieee.org/document/8793576'
citation: 'Digumarti, S. T., Schmid, L. M., Rizzi, G. M., Nieto, J., Siegwart, R., Beardsley, P., & Cadena, C. (2019, May). &quot;An approach for semantic segmentation of tree-like vegetation.&quot; <i>IEEE International Conference on Robotics and Automation (ICRA)</i>, 3(4), pp. 1801-1807'

---
## Abstract
This paper presents a pipeline for semantic segmentation of trees into their components. Given a single RGB-D image of a tree, we employ a deep network to predict labels to classify each pixel of the tree into trunk, branches, twigs and leaves. Multiple convolutional neural network architectures to combine the complementary modalities of depth and colour data are investigated. An asynchronous training approach where two networks trained separately on RGB and depth encoded as a 3-channel HHA image are combined using a late fusion architecture with different learning rates performs the best. Training and evaluation are performed on a synthetic dataset of 6 species of broadleaf trees. We further demonstrate the network's generalization capabilities, across various tree species on the synthetic dataset, achieving an accuracy of upto 92.5%. Furthermore, we present a qualitative evaluation of our approach on real-world data.