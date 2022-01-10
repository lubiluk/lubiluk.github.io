---
layout: post
title:  "Ontology-Assisted Generalisation of Robot Action Execution Knowledge"
date:   2022-01-04 23:30:00 +0200
categories: middle-circle
---

A. Mitrevski, P. G. Plöger, and G. Lakemeyer, “Ontology-Assisted Generalisation of Robot Action Execution Knowledge,” *IROS*, 2021. [online](http://arxiv.org/abs/2107.09353)


***

The paper addresses an issue of generalization of robot behaviors to scenarios unseen during learning. Environment and object ontologies describe realtionships between objects classes. Those can be helpful in deciding if an action is useful in the newly encountered context. But ontologies are static in nature and do not consider robot's experience which is a limiting factor. The proposed method combines object ontology with a probabilistic graph that indicates the likelihood of successful action generalization.

The ontology, based on the OWL language, encodes object class definitions, relations between those classes and object property definitions. By using such an ontology when decinding on a generalization strategy the search of possible execution models is reduced to manageable level and prevents generalization between unrelated object classes. The additional probabilistic graph model provides experience-based weights to the ontology which further helps with selecting the right generalization. The experience is learned using 25 executions of an action on each object.

The idea is validated using two common domestic scenarios: grasping objects and stowing them in a drawer. The experiments are performed using Toyota HSR. Objects used come from the YCB dataset.

![Ontology-Assisted Generalisation of Robot Action Execution Knowledge](/assets/ontology_assisted_generalization.png)