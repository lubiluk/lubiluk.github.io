---
layout: post
title:  "Bootstrapping the Semantics of Tools: Affordance Analysis of Real World Objects on a Per-part Basis"
date:   2022-01-05 17:00:00 +0200
categories: middle-circle
---
 
M. Schoeler and F. Worgotter, “Bootstrapping the Semantics of Tools: Affordance Analysis of Real World Objects on a Per-part Basis,” IEEE Trans. Cogn. Dev. Syst., vol. 8, no. 2, pp. 84–98, Jun. 2016, doi: 10.1109/TAMD.2015.2488284.

***

Humans can use an enormous number of different shapes, and in different ways, as tools. Authors speculate that what makes this extreme adaptation possible is because humans understand tools through their affordances to human hands. Possible configurations of hands reduces the number of possible tool types and tool uses to a manageable size, hence allowing for tool understanding transfer. To test that theory authors introduce a computer vision based system that makes predictions about the possible functions of simple tools.

Objects are segmented using Constrained Planar Cuts into separate functional parts. Then signa-ture of histograms of orientations (SHOT) and ensemble of shape functions (ESF) are used to create part signatures. Additionally a pose signature is estimated. It tells how different parts of the object are connected together. An SVM classifier, trained on synthetic data recognizes possible uses of given tool.

![Bootstrapping the Semantics of Tools: Affordance Analysis of Real World Objects on a Per-part Basis](/assets/bootstrapping-the-semantics-of-tools-affordance-analysis-of-real-world-objects-on-a-per-part-basis.png)