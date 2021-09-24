---
title: "Fast-Learning Grasping and Pre-Grasping Via Clutter Quantization and Q-Map Masking"
collection: publications
permalink: /publication/2021-09-28-Fast-Learning-Grasping
excerpt: ''
date: 2019-09-28
venue: 'IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)'
paperurl: 'https://http://export.arxiv.org/pdf/2107.02452'
citation: 'Ren, X., Wang, X., Digumarti, S. T., Shi, G. (2021, September). &quot;Fast-Learning Grasping and Pre-Grasping Via Clutter Quantization and Q-Map Masking.&quot; <i>IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)</i> (to appear)'

---
## Abstract
Grasping objects in cluttered scenarios is a challenging task in robotics. Performing pre-grasp actions such as pushing and shifting to scatter objects is a way to reduce clutter. Based on deep reinforcement learning, we propose a Fast-Learning Grasping (FLG) framework, that can integrate pre-grasping actions along with grasping to pick up objects from cluttered scenarios with reduced real-world training time. We associate rewards for performing moving actions with the change of environmental clutter and utilize a hybrid triggering method, leading to data-efficient learning and synergy. Then we use the output of an extended fully convolutional network as the value function of each pixel point of the workspace and establish an accurate estimation of the grasp probability for each action. We also introduce a mask function as prior knowledge to enable the agents to focus on the accurate pose adjustment to improve the effectiveness of collecting training data and, hence, to learn efficiently. We carry out pre-training of the FLG over simulated environment, and then the learnt model is transferred to the real world with minimal fine-tuning for further learning during actions. Experimental results demonstrate a 94% grasp success rate and the ability to generalize to novel objects. Compared to state-of-the-art approaches in the literature, the proposed FLG framework can achieve similar or higher grasp success rate with lesser amount of training in the real world. Supplementary video is available [here](https://youtu.be/KTGj1fGU6ho). 