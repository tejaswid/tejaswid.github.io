---
title: "Towards real-time forest inventory using handheld LiDAR"
collection: publications
permalink: /publication/2022-08-22-Realtime-Forest-Inventory-RAS
excerpt: ''
date: 2022-08-22
venue: 'Robotics and Autonomous Systems'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S0921889022001397'
citation: 'Proudman, A., Ramezani, M., Digumarti, S.T., Chebrolu, N. and Fallon, M., 2022. &quot;Towards real-time forest inventory using handheld LiDAR.&quot; <i>Robotics and Autonomous Systems</i>, 157, p.104240'


---
## Abstract
While mobile LiDAR sensors are increasingly used to scan in ecology and forestry applications, reconstruction and characterization are typically carried out offline. Motivated by this, we present an online LiDAR system which is capable of running on a handheld device. Our system is capable of creating 3D point cloud reconstructions of large forest areas, segment and track individual trees, and create an inventory for the detected trees. Segments relating to each tree are accumulated over time, and tree models are completed as more scans are captured from different perspectives. The LiDAR scans are processed in an online fashion, and feedback can be provided to the operator via a screen mounted on the device. This allows the operator to ensure the desired area is mapped satisfactorily without any gaps or missing sections. We employ a pose-graph based SLAM system with loop closures to correct for drift errors allowing us to map large areas accurately. Our mapping system also provides multi-session capability where data captured during different runs can be automatically merged in a post-processing step. In this work, we estimate the Diameter at Breast Height (DBH) of individual trees as an example parameter for the forest inventory. The DBH is estimated online by fitting a cylinder to each tree trunk through a least-squares optimization within a RANSAC loop. We demonstrate our mapping approach operating in two different forests (both ecological and commercial) with the total travel distance spanning several kilometres. Further, we also provide experimental results comparing our DBH estimation to ground-truth measurements recorded manually in an ecological forest (Wytham Woods, Oxford). We demonstrate that our DBH estimates are within 7 cm accuracy for 90% of individual trees detected in the dataset.