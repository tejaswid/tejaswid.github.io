---
title: "Underwater 3D Capture Using Commercial Depth Cameras"
excerpt: "An underwater 3D capture system and a method for calibrating depth cameras for underwater use.<br/> <img src='/images/underwater_system.gif'>"
collection: projects
---
  
In this project we developed a complete underwater 3D capture system using commercial depth cameras, including protective housing, suitable for hand-held use by a diver. Most commercial depth cameras such as the Intel RealSense (F200 and SR300) work by projecting a structured infrared pattern into the environment and estimate depth by measuring distortions in this pattern, observed through an infrared camera. When using such cameras underwater, the depth computed by the cameras is incorrect due to refractions occuring at the air-housing interface and the housing-water interface. We developed an easy-to-use calibration method, to account for these refractions, which we evaluate on exemplar data as well as 3D reconstructions in a lab aquarium.

A [paper](../../publication/2016-03-07-Underwater-3D) on this was published at the IEEE Winter conference on Applications of Computer Vision, 2016.

<img src='/images/underwater_system.gif'>  
Figure shows (a) CAD model of the system, (b) the device being tested underwater.

<img src='/images/underwater_refractions.gif'>  
Figure shows the refraction model.