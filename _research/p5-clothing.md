---
title: "Human Acquisition and Re-acquisition by Clothing Characterization"
excerpt: "A system for identifying previously observed people using their clothing.<br/> <img src='/images/ms_framework.png'>"
collection: research
---

This was my master's thesis at the Autonomous Systems Lab (ASL), ETH Zurich. This work was a joint collaboration with Disney Research, Zurich and was carried out under the supervision of Dr. Paul Beardsley, [Prof. Dr. Stelian Coros](http://crl.ethz.ch/coros.html), [Prof. Dr. Roland Siegwart](http://www.asl.ethz.ch/the-lab/people/person-detail.Mjk5ODE=.TGlzdC8yMDI4LDEyMDExMzk5Mjg=.html) and [Raghav Khanna](https://raghavkhanna.github.io/).  

In this project we developed a system for identifying people who were previously observed by recongnizing their clothing. Images of people were captured using a Kinect One (v2) sensor in an initial step. Using a skeleton extracetd on these images, the torso region was cropped out and transformed into a fronto-parallel view. Features were extracted on these crops and a classifier was trained on these features. In a later step when the same people were once again imaged by the system, they were identified based on their clothing. Various features such as Colour Histograms, SURF, Histogram of Gradients (HOG) and a combination of these were evaluated and a robust re-identification framework was developed. Evaluation was carried out under several lighting conditions as well.

Bonus: I got the opportunity to be one of the first few to work with the developer model of the then newly released Kinect v2 sensor.

<img src='/images/ms_framework.png'>  
An overview of the framework.  

<img src='/images/ms_dataset.png'>  
A sample of the dataset.