---
layout: post
title:  "Automatic Hanging Point Learning from Random Shape Generation and Physical Function Validation"
date:   2022-01-05 23:00:00 +0200
categories: inner-circle
---
 
K. Takeuchi, I. Yanokura, Y. Kakiuchi, K. Okada, and M. Inaba, “Automatic Hanging Point Learning from Random Shape Generation and Physical Function Validation,” in 2021 IEEE International Conference on Robotics and Automation (ICRA), Xi’an, China, May 2021, pp. 4237–4243. doi: 10.1109/ICRA48506.2021.9561484.

***

The proposed system tackles the problem of finding points on arbitrary shapes that enable the object to be hung. The hanging points are estimated using a Deep Neural Network trained on a random shapes genrated by Generative Adversarial Network. Each shape is tested in simulation in various poses to check for possible hanging configuration, hence generating ground truth hangin points. Shapes are then rendered with domain randomization.

The system is tested on synthetic data as well as on real object from the YCB dataset. Also an experiment with real world scenario using PR2 robot is performed.

![Automatic Hanging Point Learning from Random Shape Generation and Physical Function Validation](/assets/automatic-hanging-point-learning-from-random-shape-generation-and-physical-function-validation.png)