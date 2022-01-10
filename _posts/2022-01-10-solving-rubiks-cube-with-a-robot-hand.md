---
layout: post
title:  "Solving Rubik’s Cube with a Robot Hand"
date:   2022-01-10 23:00:00 +0200
categories: outer-circle
---

OpenAI et al., “Solving Rubik’s Cube with a Robot Hand,” arXiv:1910.07113 [cs, stat], Oct. 2019, Accessed: Jan. 11, 2022. [online](http://arxiv.org/abs/1910.07113)

***

Different humanoid robots exist today but using them in real world for complex task still remains a challenge. 

A shadow hand solves Rubic’s cube. It is achieved by training a reinforcement learning model in simulation. The model learns hot to reposition the cube and how to rotate its faces. The plan for solving the cube is generated procedurally by a widely known algorithm. In order to achieve transferability or the RL model from simulation to the real world it is trained multiple times in varying simulation worlds. Physics parameters and visual appearance changes are generated automatically by Adaptive Domain Randomization algorithm which makes sure that the RL model trains well in a variety and f setups. 


![Solving Rubik’s Cube with a Robot Hand](/assets/solving-rubiks-cube-with-a-robot-hand.png)