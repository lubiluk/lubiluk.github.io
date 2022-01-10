---
layout: post
title:  "Compositional pattern producing networks: A novel abstraction of development"
date:   2022-01-10 23:00:00 +0200
categories: outer-circle
---

K. O. Stanley, “Compositional pattern producing networks: A novel abstraction of development,” Genet Program Evolvable Mach, vol. 8, no. 2, pp. 131–162, Jun. 2007, doi: 10.1007/s10710-007-9028-8. [online](http://link.springer.com/10.1007/s10710-007-9028-8)

***

DNA in biological systems is an example of great information compression. A relatively short genome can produce multicelluar organisms with a structure far more complex than the genome itself. Nature achieves that through the means of emryogenesis, a temporal unfolding process. It starts with just one cell then continues to develop from there by creating increasingly complex structures. However, it was shown that such a process in theory doesn't need the temporal progression, as it can be replaced by a functional description. Drawing inspiration from nature and taking into account above considerations this paper proposes a novel abstraction for evolutionary computation called Compositional Pattern Producing Networks (CPPNs).

CPPNs are networks of function compositions that produce phenotype. They take coordinates as inputs and return phenotype element description. Effectively they simulate embryogenesis but instead of temporal unfolding they employ function composition. Structurally they are equivalent to Artificial Neural Networks, but serve a different purpose, hence the name diversification.

Since CPPNs and ANNs are so similar it is trivial to modify NEAT algorithm such that it evolves CPPNs instead of ANNs. CPPN–NEAT is an extension to NEAT that does just that. Essentially, in order to evolve CPPNs that would offer regularities like symmetry or repetition support for different activation functions was added to NEAT.

The system is demonstrated in a setup where CPPN generates an image and human is responsible for choosing parents at each mating iteraction. The result is an image with some visible regularities, repetitions or symmetries. Ultimately CPPNs could be used to describe large artificial neural networks though this paper does not go into detail on how that could be achieved.


![Compositional pattern producing networks: A novel abstraction of development](/assets/compositional-pattern-producing-networks-a-novel-abstraction-of-development.png)