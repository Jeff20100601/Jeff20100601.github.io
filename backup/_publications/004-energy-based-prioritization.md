---
title: "Energy-Based Hindsight Experience Prioritization"
collection: publications
permalink: /publication/004-energy-based-prioritization
excerpt: '
<p align="left">
  <img width="500" height="" src="/images/004-energy-based-prioritization.png">
</p>'
date: 2018-12-24
venue: 'Published in Conference on Robot Learning (CoRL) as <span style="color:red">oral presentation</span> (7%), 2018<br/>
        Proceedings of  Machine Learning Research Volume 87'
paperurl: 'https://arxiv.org/abs/1810.01363'
---
In Hindsight Experience Replay (HER), a reinforcement learning agent is trained by treating whatever it has achieved as virtual goals. However, in previous work, the experience was replayed at random, without considering which episode might be the most valuable for learning. In this paper, we develop an energy-based framework for prioritizing hindsight experience in robotic manipulation tasks. Our approach is inspired by the work-energy principle in physics. We define a trajectory energy function as the sum of the transition energy of the target object over the trajectory. We hypothesize that replaying episodes that have high trajectory energy is more effective for reinforcement learning in robotics. To verify our hypothesis, we designed a framework for hindsight experience prioritization based on the trajectory energy of goal states. The trajectory energy function takes the potential, kinetic, and rotational energy into consideration. We evaluate our Energy-Based Prioritization (EBP) approach on four challenging robotic manipulation tasks in simulation. Our empirical results show that our proposed method surpasses state-of-the-art approaches in terms of both performance and sample-efficiency on all four tasks, without increasing computational time. A video showing experimental results is available at https://youtu.be/jtsF2tTeUGQ

[Download paper here](https://arxiv.org/abs/1810.01363)
