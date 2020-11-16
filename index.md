---
layout: default
title: Erwan Lecarpentier
---

# Welcome to my home page

Hi, I just completed my PhD in Computer Sciences on the topic of "Reinforcement Learning in Non-Stationary Markov Decision Processes". The thesis was carried out at [ISAE-SUPAERO](https://www.isae-supaero.fr/en/) in the awesome city of Toulouse. I was honored to work under supervision of Prof. [Emmanuel Rachelson](https://people.isae-supaero.fr/emmanuel-rachelson?lang=en), Dr. [Guillaume Infantes](https://scholar.google.fr/citations?user=CyD_G68AAAAJ&hl=en), and Dr. [Charles Lesire](https://www.onera.fr/en/node/3104).

I am interested in Artificial Intelligence and was introduced to the field via the Reinforcement Learning (RL) paradigm. Currently, I am focusing on several different questions, including the following:
- How to build efficient state and/or action abstractions to prune the complexity of an RL task? Precisely, I am interested in ways to formalize a good optimization criterion that would produce those abstractions. I am thinking about criteria that would be similar to the one human could use (e.g. bio-inspired), instead of criteria that would optimize directly an objective such as the discounted sum of rewards in an MDP.
- How to build RL algorithms that realize a trade-off between performance guarantees and level of approximation? Mostly, existing algorithms are ON/OFF, i.e. they are either exact/tabular and feature a high sample complexity, or they use function approximators that make them efficient but implies losing the performance guarantees. Could an in-between exist?
- How to build good metrics to measure MDP similarities? Such a tool could be used to build efficient transfer learning methods (see [our work on Lifelong RL](https://erwanlecarpentier.github.io/pdf/lecarpentier20lipschitz.pdf)). A key point would be to learn to detect good features of MDPs that indicate the possibility of knowledge transfer.

# Publications

2020 Erwan Lecarpentier, David Abel, Kavosh Asadi, Yuu Jinnai, Emmanuel Rachelson, Michael L. Littman. Lipschitz Lifelong Reinforcement Learning. Submitted.<br/>
[**PDF**](https://erwanlecarpentier.github.io/pdf/lecarpentier20lipschitz.pdf) - [**arXiv**](https://arxiv.org/abs/2001.05411)

2019 Erwan Lecarpentier and Emmanuel Rachelson. Non-Stationary Markov Decision Processes, a Worst-Case Approach using Model-Based Reinforcement Learning. In Proceedings of the Thirty-third Conference on Neural Information Processing Systems, NeurIPS 2019<br/>
[**NeurIPS**](https://papers.nips.cc/paper/8942-non-stationary-markov-decision-processes-a-worst-case-approach-using-model-based-reinforcement-learning) - [**PDF**](https://erwanlecarpentier.github.io/pdf/lecarpentier19non.pdf) - [**arXiv**](https://arxiv.org/abs/1904.10090)

2018 Erwan Lecarpentier, Guillaume Infantes, Charles Lesire, and Emmanuel Rachelson. Open loop execution of tree-search algorithms. In Proceedings of the Twenty-Seventh International Joint Conference on Artificial Intelligence, IJCAI 2018<br/>
[**IJCAI**](https://www.ijcai.org/proceedings/2018/0327.pdf) - [**PDF**](https://erwanlecarpentier.github.io/pdf/lecarpentier18openloop.pdf) - [**arXiv**](https://arxiv.org/abs/1805.01367)

2017 Erwan Lecarpentier, Sebastian Rapp, Marc Melo and Emmanuel Rachelson. Empirical evaluation of a Q-Learning Algorithm for Model-free Autonomous Soaring. In JFPDA 2017.<br/>
[**JFPDA**](https://pfia2017.greyc.fr/share/actes/JFPDA/Lecarpentier_JFPDA_2017.pdf) - [**PDF**](https://erwanlecarpentier.github.io/pdf/lecarpentier17empirical.pdf) - [**arXiv**](https://arxiv.org/abs/1707.05668)

PhD Thesis: Reinforcement Learning in Non-Stationary Environments, ISAE-SUPAERO - Université de Toulouse.<br/>
[**PDF**](https://erwanlecarpentier.github.io/pdf/phdthesis.pdf)

# Coding

Some RL environments I created:

[**Dyna Gym**](https://github.com/SuReLI/dyna-gym)
This is a pip package implementing Reinforcement Learning algorithms in non-stationary environments supported by the OpenAI Gym toolkit.<br/>
<a href="https://github.com/SuReLI/dyna-gym"><img class="small_link_icon_button" src="img/github_logo.png"></a>

[**Flatland environment**](https://github.com/erwanlecarpentier/flatland)
A C++ library for navigation task in a 2D environment. The settings enable the use of different policies, environments and action spaces. Choice of state space is also made available so that the agent can either evolve within a discrete gridworld or a continuous-state world.<br/>
<a href="https://github.com/erwanlecarpentier/flatland"><img class="small_link_icon_button" src="img/github_logo.png"></a>

[**Learning2Fly**](https://github.com/erwanlecarpentier/l2f)
A C++ library simulating the flight of a glider UAV within a non-stationary atmosphere featuring thermal currents. The used dynamics model is borrowed from [Beeler et al. 2003](https://ntrs.nasa.gov/search.jsp?R=20040031358).<br/>
<a href="https://github.com/erwanlecarpentier/l2f"><img class="small_link_icon_button" src="img/github_logo.png"></a>

[**Traveler**](https://github.com/erwanlecarpentier/traveler)
Traveler is a graph-based non-stationary MDP simulating travels between waypoints. Each node of the graph represents a location and each edge a route between locations. The travel duration corresponding to an edge is time-dependent, making the environment non-stationary. The goal of an agent is to reach a unique termination node as quickly as possible.<br/>
<a href="https://github.com/erwanlecarpentier/traveler"><img class="small_link_icon_button" src="img/github_logo.png"></a>

