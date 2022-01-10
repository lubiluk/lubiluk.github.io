---
layout: post
title:  "Evolving Neural Networks through Augmenting Topologies"
date:   2022-01-10 23:00:00 +0200
categories: outer-circle
---

K. O. Stanley and R. Miikkulainen, “Evolving Neural Networks through Augmenting Topologies,” Evolutionary Computation, vol. 10, no. 2, pp. 99–127, Jun. 2002, doi: 10.1162/106365602320169811. [online](https://direct.mit.edu/evco/article/10/2/99-127/1123)

***

NeuroEvolution of Augmenting Topologies (NEAT) is a method of solving complex control problems by gradually evolving artificial neural networks (ANN) by the means of genetic programming. In NEAT a genotype that is being evolved consists of genes that encode nodes, node connections, and connection weights of a neural network. Genotype contains all the information required to build a phenotype - a neural network with a structure that reflects description in genotype. Performance of each ANN is evaluated in the test environment and a fitness score is assigned to its genotype. Genotypes with the best fitness scores are selected for further evolution in each optimization cycle.

Genotypes can be of variable length. When a new gene is introduced to the gene pool it gets an unique number. That number is used during mating to align corresponding genes.

There are two major features that separate NEAT from other neuroevolution algorithms. Firstly, NEAT starts the process with minimal genotype and gradually adds more elements to it, hence it promotes simpler solutions. Secondly, NEAT has a mechanism of that can distinguish different species of genotypes and let's them evolve in separation. Coevolution of species prevents falling into local optima and gives genotypes time to optimize before being discarded as non-performant.

The performance of the system is evaluated on XOR, Pole Balancing and Double Pole Balancing problems where it outperformed previous attempts like ESP in terms of convergence time. Also, autors point out that neuro-evolution (NE) techniques have already surpassed traditional gradient based methods on some benchmarks in the past, therefore they only need to compare NEAT to other NE algorithms.

![Evolving Neural Networks through Augmenting Topologies](/assets/evolving-neural-networks-through-augmenting-topologies.png)