---
layout: default
title: Erwan Lecarpentier
---

# Welcome to my home page

Hi, I am a third year PhD student at [ISAE-SUPAERO](https://www.isae-supaero.fr/en/) in the awesome city of Toulouse. I am honored to work under supervision of Dr. [Emmanuel Rachelson](https://people.isae-supaero.fr/emmanuel-rachelson?lang=en), Dr. [Guillaume Infantes](https://www.onera.fr/en/node/3138), and Dr. [Charles Lesire](https://www.onera.fr/en/node/3104).

I am interested in Artificial Intelligence and was introduced to the field via the Reinforcement Learning (RL) paradigm. Currently, I am working on Non-Stationary Markov Decision Processes (MDPs). I view the evolution in two different ways: 1) when it changes continuously, this is a robot trying to surf on a wave; 2) when it changes abruptly, this is a robot in a lifelong RL world.

# Coding

Some RL environments I created:

**Dyna Gym**
This is a pip package implementing Reinforcement Learning algorithms in non-stationary environments supported by the OpenAI Gym toolkit. [**Github**](https://github.com/SuReLI/dyna-gym)

**Flatland environment**
A C++ library for navigation task in a 2D environment. The settings enable the use of different policies, environments and action spaces. Choice of state space is also made available so that the agent can either evolve within a discrete gridworld or a continuous-state world. [**Github**](https://github.com/erwanlecarpentier/flatland)

**Learning2Fly**
A C++ library simulating the flight of a glider UAV within a non-stationary atmosphere featuring thermal currents. The used dynamics model is borrowed from [Beeler et al. 2003](https://ntrs.nasa.gov/search.jsp?R=20040031358). [**Github**](https://github.com/erwanlecarpentier/l2f)

**Traveler**
Traveler is a graph-based non-stationary MDP simulating travels between waypoints. Each node of the graph represents a location and each edge a route between locations. The travel duration corresponding to an edge is time-dependent, making the environment non-stationary. The goal of an agent is to reach a unique termination node as quickly as possible. [**Github**](https://github.com/erwanlecarpentier/traveler)

# Publications

2019 Erwan Lecarpentier and Emmanuel Rachelson. Non-Stationary Markov Decision Processes, a Worst-Case Approach using Model-Based Reinforcement Learning. arXiv preprint arXiv:1904.10090 [**Preprint**](https://arxiv.org/abs/1904.10090)

2018 Erwan Lecarpentier, Guillaume Infantes, Charles Lesire, and Emmanuel Rachelson. Open loop execution of tree-search algorithms. In Proceedings of the Twenty-Seventh International Joint Conference on Artificial Intelligence, IJCAI-18 [**IJCAI**](https://www.ijcai.org/proceedings/2018/0327.pdf)

2017 Erwan Lecarpentier, Sebastian Rapp, Marc Melo and Emmanuel Rachelson. Empirical evaluation of a Q-Learning Algorithm for Model-free Autonomous Soaring. In JFPDA, 2017. [**JFPDA**](https://pfia2017.greyc.fr/share/actes/JFPDA/Lecarpentier_JFPDA_2017.pdf)

