# Reinforcement learning: Train An Agent Play Pacman Game Using Neural Network

## Introduction

Reinforcement learning is an area of machine learning and also a branch of artificial intelligence. 
Although many algorithm has been successful applied on reinforcement learning, it is still an open research question about how  to implement reinforcement learning on large dynamic environments. Neural network is one of the most popular method to handling  large dynamic environments. In this project, we will implement reinforcement learning  algorithm using neural network on a famous arcade game Ms.PacMan. The game Ms. PacMan has a large dynamic environment. In order to the let the agent quickly learn how to play Ms. PacMan, we combine neural network and SASAR(λ) to train the agent. Furthermore, we apply A* searching algorithm to achieve good performance.

### Prerequisities

Required softwares:

Pac-man requires **Python 2.x** (tested on versions 2.6 and 2.7), and the
corresponding version of the Pygame library, freely available online. Make sure
you install the matching (32- or 64-bit) version of Pygame as your Python
installation, and the one compatible with your Python version number. 

pybrain library is also needed.

### Agent play

The main program is /pacman-python-master/pacman/pacman.pyw
run pacman.pyw file then you can see the agent running Ms. Pac-man to eat Pac-dots.

### Result

Training take 500 episodes. 

![alt tag](https://github.com/tianxiangchen2015/Reinforcement-learning-train-agent-play-pacman/blob/master/pics/Screenshot%20from%202016-11-04%2019-46-04.png)

![alt tag](https://github.com/tianxiangchen2015/Reinforcement-learning-train-agent-play-pacman/blob/master/pics/Screenshot%20from%202016-11-04%2019-46-26.png)

![alt tag](https://github.com/tianxiangchen2015/Reinforcement-learning-train-agent-play-pacman/blob/master/pics/afdsf.png)

### Authors

* **Tianxiang Chen (ORNL Research Assistant)** - [Linkedin HomePage](https://www.linkedin.com/in/tianxiang-chen-946543114?trk=nav_responsive_tab_profile)
* Yan Li

### Acknowledge

* Thanks to David Reilly for provding pacman code.
* Thanks to pyBrain team for the easy using library for neural network.
