---
title: "Research Assistantship"
collection: teaching
type: "Graduate Research"
permalink: /teaching/2017-spring-teaching-4
venue: "GRASP Laboratory, University of Pennsylvania"
date: 2021-08-01
location: "Philadelphia, Pennsylvania"
---

Research Assistant to Dr. [Kostas Daniilidis](https://www.cis.upenn.edu/~kostas/), Ruth Yalom Stone Professor at Department of Computer and Information Science, and Dr. [Eleni Miltsakaki](https://www.miltsakaki.com/), Senior Researcher, Department of Computer and Information Science at [GRASP Laboratory](https://www.grasp.upenn.edu/) at University of Pennsylvania.

Research Overview
======

### Cross-modal Map Learning for Vision and Language Navigation (VLN)

As technology makes our lives easier everyday we expect robots to be able to smartly execute tasks that are defined not in the form of lengthy scripts but rather in the form of human instructions (text or speech).
A very basic but challenging task for the robot is to locomote from point A to point B in a completely unfamiliar environment.
While robots have been quite successful in executing this task using metric representations, it has been more challenging for robots to execute semantic tasks such as “go down the hallway and turn right into the kitchen”.
In VLN, the robot is given instructions and is expected to reach a goal by making use of images of the environment that it can acquire along the way.

### The two-fold objective to this problems: 
1.  semantic grounding of language to predict semantic maps
2.  spatial grounding of instructions to predict path to reach the goal

We leveraged VLN-CE and Google Room-Across-Room datasets to test our Cross-model map learning algorithm. 

My Contribution
======
1.  Created a multi-stream design that leverages cross-modal attention mechanism of transformers on egocentric maps
2.  Semantic and spatial grounding of instructions to predict semantic maps and waypoints within Vision-and-Language Navigation in Continuous Environments (VLN-CE) setup
3.  Identifying and masking parts of instruction that correspond to concepts such as motion, change in direction or localization to quantify the impact of navigation concepts on waypoint prediction

Read more about the project [here](https://ggeorgak11.github.io/CM2-project/)
