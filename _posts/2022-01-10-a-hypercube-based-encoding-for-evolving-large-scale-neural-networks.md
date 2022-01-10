---
layout: post
title:  "A Hypercube-Based Encoding for Evolving Large-Scale Neural Networks"
date:   2022-01-10 23:00:00 +0200
categories: outer-circle
---

K. O. Stanley, D. B. D’Ambrosio, and J. Gauci, “A Hypercube-Based Encoding for Evolving Large-Scale Neural Networks,” Artificial Life, vol. 15, no. 2, pp. 185–212, Apr. 2009, doi: 10.1162/artl.2009.15.2.15202. [online](https://direct.mit.edu/artl/article/15/2/185-212/2634)

***

The idea behind Hypercube-based NeuroEvolution of Augmenting Topologies (HyperNEAT) is that neural networks found in nature exhibit some patterns or motifs in their structure. It is hypothesized that such regularities may help with dealing with regularities in network inputs. HyperNEAT employs CPPNs to describe large scale ANNs through connectivity patterns as functions in Cartesian space.
 
 This article focuses on connective CPPNs, i.e. CPPNs that describe connections between nodes in space, rather than spatial CPPNs like the original CPPNs paper did. Connective CPPN is a function of four dimensions that generate spatial patterns embedded in a four-dimensional hypercube. Each point in the pattern on the hypercube is interpreted as a connection in a two-dimensional connected graph. The system is evaluated on two tasks.
 
 The goal of the first task, Visual Discrimination is to find the center of a bigger rectangle from two rectangles shown on a black and white two-dimensional visual field.
 
 In the second task, Food Gathering there is a robot placed in the middle of two-dimensional, square room. It is employed with range sensors and can move in any direction, but always faces the same side (no rotation). A piece of food is placed somewhere in the room. The goal is for the robot to find the food.


![A Hypercube-Based Encoding for Evolving Large-Scale Neural Networks](/assets/a-hypercube-based-encoding-for-evolving-large-scale-neural-networks.png)