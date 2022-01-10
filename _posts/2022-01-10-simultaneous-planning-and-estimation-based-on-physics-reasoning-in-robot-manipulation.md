---
layout: post
title:  "Simultaneous Planning and Estimation Based on Physics Reasoning in Robot Manipulation"
date:   2022-01-10 23:00:00 +0200
categories: middle-circle
---
M. Murooka, S. Nozawa, M. Bando, I. Yanokura, K. Okada, and M. Inaba, “Simultaneous Planning and Estimation Based on Physics Reasoning in Robot Manipulation,” in 2018 IEEE International Conference on Robotics and Automation (ICRA), Brisbane, QLD, May 2018, pp. 3137–3144. doi: 10.1109/ICRA.2018.8463156. [online](https://ieeexplore.ieee.org/abstract/document/8463156)

***

Advanced object manipulation skills often consist of complex object motions, re-grasping, tool use or cooperation with other agents. Those in turn require adaptive planning and understanding of object properties and effects of actions performed on them. Proposed framework takes into account those considerations by performing operation trials and updating object's property estimates while doing that.

The objective for the robot is specified as a desired repositioning of given object. Robot's program considers object statics constraints to be satifsied during manipulation based on probability distribution of objects' properties. Manipulation planner works on graph representations of object states with possible transitions like adding or removing contacts (i.e. grasping and releasing), sliding, pivoting, lifting, etc. During each manipulation attempt the program executes the most feasable operation and collects sensor data to improve next step guesses.

The system is evaluated in a multitude setups. In the simplest form it is tested on a simple simulation of a cube. In more realistic scenarios the system is tried on real robots (HRP-2 and PR2) that are supposed carry heavy furniture. Based on an initial trials robots can decide whether it is better to push objects, pivot them around corners or lift them. It is also possible to achieve reasoning for model multi link objects like ladders and plan appropriate operations on them by extending statics constraints and adding new operations to robot's repertoire. Additionally learning from demonstration scenario is shown where robots instead of learning trajectories use demonstrations performed by humans to estimate objects' physical properties wich will in turn make their own manipulation planning more accurate.

![Simultaneous Planning and Estimation Based on Physics Reasoning in Robot Manipulation](/assets/simultaneous-planning-and-estimation-based-on-physics-reasoning-in-robot-manipulation.png)