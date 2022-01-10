---
layout: post
title:  "Know Rob 2.0 — A 2nd Generation Knowledge Processing Framework for Cognition-Enabled Robotic Agents"
date:   2022-01-10 23:00:00 +0200
categories: middle-circle
---

M. Beetz, D. Bessler, A. Haidu, M. Pomarlan, A. K. Bozcuoglu, and G. Bartels, “Know Rob 2.0 — A 2nd Generation Knowledge Processing Framework for Cognition-Enabled Robotic Agents,” in 2018 IEEE International Conference on Robotics and Automation (ICRA), Brisbane, QLD, May 2018, pp. 512–519. doi: 10.1109/ICRA.2018.8460964. [online](https://ai.uni-bremen.de/papers/beetz18knowrob.pdf)

***

Robotic manipulation tasks, in order to be successfuly performed, requrie huge amount of information about task, environment and physics in general. KnowRob2 is a framework that offers knowledge representation and reasoning mechanisms for making informed decisions concerning robot motions. The second version of the framework is a continuation of the former version with partial redesign and new additions.

KnowRob2 works as an information source about the world, current task and robot's state. It stores information on different levels of abstraction and offers a way to meaningfully search through it. The system can answer detailed questions about tasks and the world such as "how to pick up the cup to pour out its remains".

At it's core, on it's lowes level the system has a symbolic representation of the ontology which allows programmer to semantically annotate control data structures and compute the semantic meaning of them. The core ontology consists of robots and their body parts, part connections, sensing, action capabilities, objects, their parts and functionality, object constellations and configurations, robot tasks, actions, activities, behaviors, situational context and environment.

KnowRob2 includes a hybrid reasoning kernel with knowledge bases of: the inner world knowledge (cad models, meshes), virtual knowledge (computed on demand from control system data), logid knowledge (sensor data with logical axioms and inference mechanisms) and episodic memories knowledge (past experiences of the robot). It generates multiple possible answers to a query and validates their plausibility and consistency. The system constatly records robot's experiences toghether with it's intents and saves them as Narrative-enabled Episodic Memories which can be retrieved, replayed and analysed on demand. The reasoning system also includes a realistic world simulator based on an advanced game engine which allows the agent to predict outcomes of it's actions and test hypotheses or try certain motions before performing them in real world. All of the above elements of the system which are heterogenious in nature are tied together by inference mechanisms which are accessible through a uniform programming interface. The interface lets programmers to retrieve and infer needed information by constructing queries using Prolog language. Part of the KnowRob2 system is available to try online as a web-based knowledge system called [openEASE](http://open-ease.org).

![Know Rob 2.0 — A 2nd Generation Knowledge Processing Framework for Cognition-Enabled Robotic Agents](/assets/know-rob-20-a-2nd-generation-knowledge-processing-framework-for-cognition-enabled-robotic-agents.png)