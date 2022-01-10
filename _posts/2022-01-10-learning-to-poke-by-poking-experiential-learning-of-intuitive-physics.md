---
layout: post
title:  "Learning to Poke by Poking: Experiential Learning of Intuitive Physics"
date:   2022-01-10 23:00:00 +0200
categories: outer-circle
---

P. Agrawal, A. V. Nair, P. Abbeel, J. Malik, and S. Levine, “Learning to Poke by Poking: Experiential Learning of Intuitive Physics,” p. 9. [online](https://arxiv.org/pdf/1606.07419.pdf)

***

It is hypothesized that humans have an internal model of intuitive physics that allows us to plan and predict outcomes of our actions. Children spend years worth of time playing with various objects with no apparent goal in mind which could be a way of acquiring that internal physics models. It could be beneficial to employ robots with similar, learnt physics models. Presented experiment sets out to do that by training a robot to plan pokes to achieve desired object positions by letting it poke objects and collect experiences.

The robot collects data by moving it's end effector above a table on a fixed height. Pokes are described by a start point, angle and length. Deep neural network is employed to learn the dynamics of the experiment. In order to avoid complexity of predicting pixels the learning alorigthm operates on scene latent features obtained by passing the input image from RGB camera through 5 convolution layers. Moreover, to avoid problems with degenerate solutions the model is trained to learn both forward and inverse dynamics simultaniously.

The learnt model is tested by requiring the robot to poke objects into desired locations. Novel objects or object setups were used to test generalization abilities. Results indicate that the robot did indeed learn some physics model. Evidence was tested agains a blob model and analysed empirically. The robot was able to poke previously unseen shapes and drive objects to longer distances than those used in traning. Further studies in a simulated environment were performed to gain more insight into the learning process and suggested that forward model regularizes inverse model and therefore helps to generalize better. With large amounts of training data an inverse-only model performs as good as the inverse-forward model. That can be explained by the fact that large training sets usually lead to better generalizations.

### Future work
* Compare learnt physics vs simulated physics
* Quantify robustness of models
* Use continuous time control with smaller pokes
* Test scalability of the approach


![Learning to Poke by Poking: Experiential Learning of Intuitive Physics](/assets/learning-to-poke-by-poking-experiential-learning-of-intuitive-physics.png)