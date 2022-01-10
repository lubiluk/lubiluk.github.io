---
layout: post
title:  "Programming Robotic Agents with Action Descriptions"
date:   2022-01-10 23:00:00 +0200
categories: middle-circle
---

G. Kazhoyan and M. Beetz, “Programming robotic agents with action descriptions,” in 2017 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), Vancouver, BC, Sep. 2017, pp. 103–108. doi: 10.1109/IROS.2017.8202144. [online](https://ieeexplore.ieee.org/document/8202144)

***

Generalization of robot control programs is an important problem for robots that
should work in unstuctured environments. Task descriptions often take one of
two forms: either low level motion descriptions which have very limited adaptation
capabilities, or high level symbolic descriptions that are too vague to execute 
without carrying out additional computations. The way to solve the problem of 
general control programs is to combine both approaches and connect them 
using presented Action Descriptions.

Action Descriptions are prolog-based, parametrized motion plans that encode
information about what must be done and in what order to achieve given goals.
They also specifiy which of their symbols must be resolved and how. They are 
implemented in the Cognitive Robot Abstract Machine (CRAM) and use vision, 
perception and reasoning subroutines from that sytem to perform object detection,
symbol grounding, pose or context queries, motion execution etc.

The system is validated on PR2 robot in a table setting environment. It is programmed
to pick up various objects and to pour a substance into container. Analysis
of examples are provided as the evaluation. No quantitative results are presented.

![Programming Robotic Agents with Action Descriptions](/assets/programming-robotic-agents-with-action-descriptions.png)