---
title: "Automatic Segmentation of Tree Structure From Point Cloud Data"
collection: publications
permalink: /publication/2018-06-21-Automatic-Segmentation-Trees
excerpt: '**Overview**: This letter describes an automatic method for segmenting three-dimensional point cloud data of vegetation, acquired from commodity scanners, into its two main components: branches and leaves, by using geometric features computed directly on the point cloud.'
date: 2018-06-21
venue: ' IEEE Robotics and Automation Letters'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/8392392'
citation: 'Digumarti, S. T., Nieto, J., Cadena, C., Siegwart, R., & Beardsley, P. (2018). &quot;Automatic Segmentation of Tree Structure From Point Cloud Data.&quot; <i>IEEE Robotics and Automation Letters</i>, 3(4), pp. 3043-3050'

---
## Abstract
Methods for capturing and modeling vegetation, such as trees or plants, typically distinguish between two components-branch skeleton and foliage. Current methods do not provide quantitatively accurate tree structure and foliage density needed for applications such as visualization, inspection, or to estimate vegetation parameters. This letter describes an automatic method for segmenting three-dimensional point cloud data of vegetation, acquired from commodity scanners, into its two main components: branches and leaves, by using geometric features computed directly on the point cloud. In this letter, the specific type of vegetation considered is broadleaf trees. We present a data-driven approach, where a Random forest classifier is used for segmentation. In contrast to state-of-the-art methods, the point cloud is not reduced to a set of primitives such as cylinders. Instead, the algorithm works at the level of the input point cloud itself, preserving quantitative accuracy in the resulting model. Computation of typical vegetation metrics follows naturally from this model. We achieve an average classification accuracy of 91% on simulated data across three different species of broadleaf trees. Qualitative results on real data are also presented.