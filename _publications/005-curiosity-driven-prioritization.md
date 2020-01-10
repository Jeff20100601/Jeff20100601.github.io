---
title: "Curiosity-Driven Experience Prioritization via Density Estimation"
collection: publications
permalink: /publication/005-curiosity-driven-prioritization
excerpt: '
<p align="left">
  <img width="500" height="" src="/images/005-curiosity-driven-prioritization.png">
</p>'
date: 2018-12-25
venue: 'Accepted by NeurIPS Deep Reinforcement Learning Workshop'
paperurl: 'https://arxiv.org/abs/1902.08039'
---
In Reinforcement Learning (RL), an agent explores the environment and collects trajectories into the memory buffer for later learning. However, the collected trajectories can easily be imbalanced with respect to the achieved goal states. The problem of learning from imbalanced data is a well-known problem in supervised learning, but has not yet been thoroughly researched in RL. To address this problem, we propose a novel Curiosity-Driven Prioritization (CDP) framework to encourage the agent to over-sample those trajectories that have rare achieved goal states. The CDP framework mimics the human learning process and focuses more on relatively uncommon events. We evaluate our methods using the robotic environment provided by OpenAI Gym. The environment contains six robot manipulation tasks. In our experiments, we combined CDP with Deep Deterministic Policy Gradient (DDPG) with or without Hindsight Experience Replay (HER). The experimental results show that CDP improves both performance and sample-efficiency of reinforcement learning agents, compared to state-of-the-art methods.

[Download paper here](https://arxiv.org/abs/1902.08039)
