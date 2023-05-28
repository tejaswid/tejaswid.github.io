---
title: "Gesture based control for a service robot"
excerpt: "A framework for controlling a service robot using human gestures.<br/> <img src='/images/tcs.png'>"
collection: research
---
This was an internship at, TCS Innovation Labs, Noida, India, under the supervision of [Dr. Swagat Kumar](https://sites.google.com/site/swagatkumar/). In this project I developed a human gesture recognition framework for controlling a service robot. A Kinect sensor was used to capture color and depth images of a human performing a gesture. Poses of certain limbs and joints were inferred from a skeleton that was extracted using these images. A gesture constituted a pre-specified motion of the hand performed between two specific static poses of the actor. The hand movement was modelled using a Hidden Markov Model (HMM). The static poses were used to determine the start and end of a gesture. Static poses were recognized using an RBFN (Radial basis functional network) ensemble trained over various joint angles. The direction of motion of the tip of the hand was the feature used for training the HMM. These gestures were then mapped to the control of a service robot to provide a natural way of interacting with the robot.  

<img src='/images/tcs.png'>  
Figure shows a gesture being detected.
