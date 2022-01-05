---
layout: post
title:  "Multi-View Fusion for Multi-Level Robotic Scene Understanding"
date:   2022-01-05 12:00:00 +0200
categories: inner-circle
---
 
Y. Lin, J. Tremblay, S. Tyree, P. A. Vela, and S. Birchfield, “Multi-View Fusion for Multi-Level Robotic Scene Understanding,” *IROS*, 2021. [online](http://arxiv.org/abs/2103.13539)

***

The proposed system performs a multi-level scene understanding with use of three main modules: 3D point-cloud reconstruction, primitive shape recognition, and known object pose estimation.

The first layer of the system, multi-view stereo for 3D dense reconstruction, leverages COLMAP and CasMVSNet algorithms to produce refined point clouds from raw RGB camera frames. The camera is mobile and mounted on robot's wrist.

The second layer, multi-view primitive shape segmentation and fitting, finds all graspable objects in the output from the previous layer. I uses an improved PS-CNN algorithm (author's prior work) to decompose objects into one or more primitive shapes suitable for grasping. 

The third layer, multi-view object pose fusion, estimates 6-DoF poses of known CAD models. It is the DOPE extended method extended to work on multiple views.

![Multi-View Fusion for Multi-Level Robotic Scene Understanding](/assets/multi-view-fusion-for-multi-level-robotic-scene-understanding.png)