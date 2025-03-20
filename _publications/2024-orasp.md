---
title: "Optimal Robotic Assembly Sequence Planning (ORASP): A Sequential Decision-Making Approach"
collection: publications
permalink: /publication/2024-orasp
excerpt: 'Proposed a new formulation of the robotic assembly sequencing problem as a Markov Decision Process. Then showed how a class of methods called Graph Exploration Assembly Planners (GEAPs) can be used to gather optimal assembly sequences from a graph. We then showcased a deep reinforcement learning extension for handling very complex structures, all while handling diverse constraints.'
date: 2024-06-01
venue: '2024 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)'
citation: 'https://doi.org/10.1109/IROS58592.2024.10802475'
---
The optimal robotic assembly planning problem entails determining the sequence of actions for a robot to feasibly assemble a product from its components which minimizes a given objective. This problem is made especially challenging as the number of potential sequences increase exponentially with respect to the number of parts in the assembly. Additionally, the optimal sequence must also consider and satisfy a selection of constraints such as attachment precedence or a maximum robot carry weight. Traditionally, robotic assembly planning problems have been solved using heuristics, but these methods are specific to a given robot or cost structure. In this paper, we propose to model robotic assembly planning as a decision-making problem which enables us to use tools from shortest path algorithms and reinforcement learning. We formulate assembly sequencing as a Markov Decision Process and use Dynamic Programming (DP) to find optimal assembly policies that far outperform the state-of-the-art in terms of speed. We further exploit the deterministic nature of assembly planning to introduce a class of optimal Graph Exploration Assembly Planners (GEAPs) and even propose our own ORASP Search Method. We further showcase how we can produce high-reward assembly plans for larger structures using our deep Reinforcement Learning (RL) method. We evaluate this method on large robotic assembly problems such as the assembly of the Hubble Space Telescope, the International Space Station, and the James Webb Space Telescope. We further discuss how our DP, GEAP, and RL methods are capable of finding optimal solutions under a variety of different objective functions and how we translate any form of precedence constraints to branch pruning and further improve performance. We have published our code [here](https://github.com/labicon/ORASP-Code).

### Citation Bibtex:
@INPROCEEDINGS{10802475,
  author={Nagpal, Kartik and Mehr, Negar},
  booktitle={2024 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)}, 
  title={Optimal Robotic Assembly Sequence Planning (ORASP): A Sequential Decision-Making Approach}, 
  year={2024},
  volume={},
  number={},
  pages={9847-9854},
  keywords={Robotic assembly;Sequential analysis;Uncertainty;Tracking;Search methods;Decision making;Telescopes;Deep reinforcement learning;Planning;Assembly},
  doi={10.1109/IROS58592.2024.10802475}}