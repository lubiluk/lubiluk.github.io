---
layout: post
title:  "How robots are grasping the art of gripping"
date:   2021-09-08 21:29:15 +0200
categories: outer-circle
---

R. Hodson, “How robots are grasping the art of gripping,” *Nature*, vol. 557, no. 7704, pp. S23–S25, May 2018, doi: 10.1038/d41586-018-05093-1. [online](https://www.nature.com/articles/d41586-018-05093-1)

***

Grasping in unstructured and unpredictable environments is one of the biggest
challenge in robotics at the moment. A robot when trying to grasp has to deal
with a lot of uncertainty and should be able to predict results of it's actions.
Reasoning about physical interaction with everyday objects and simulating those
interactions accurately is an unsolved problem. Ultimately this prevents robots
from being used in open, human environments. Software is identified as
the bottleneck in the state of the art of robotic grasping.

The best working approaches to the problem so far, according to the results from
2017 Amazon Robotics Challenge are based on Machine Learning and use
a combination of different end effectors. Learnt robotic skills, opposed to
programmed ones, are more easily adapted to variations in the task at hand.
Recent works enabled robots to learn skills like grasping in simulation and
transfer those skills to real world, despite the fact that simulations do not
reflect reality accurately. Nevertheless, such virtual training environments
still have many limitations like inability to simulate anything that is not
a rigid body.

Soft materials are another hope for reliable grasping, as they enable so called
compliant contact, i.e. they mould against the surface of the grasped object.
Soft grippers also may enable robots to work with delicate objects without
risk of damaging them. But softness is still new to robotics and research is
in early stages.

One more aspect of grasping that's often ignored in current solutions is the
sense of touch. Some researchers are trying out solutions that involve
special resistance based touch sensors, some even try using microphones as
acoustic touch sensors with good results.

![A gripping problem](/assets/grasping.jpg)