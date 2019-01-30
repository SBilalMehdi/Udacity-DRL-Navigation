# Udacity-DRL-Navigation

## Overview

This repository serves as a submission for "Navigation" Project for the Deep Reinforcement Learning Nanodegree offered by Udacity. The code contained in this repository is a modified version of sample codes provided in different exercises in the Nanodegree.

## Environment
The repository is used with a modified version of Unity Banana Collector Environment as provided in the Udacity Nanodegree.

The state space has 37 dimensions describing the agent's velocity and ray-based perception of objects around the agent within a limited field of view. The action space is discrete with four possible values (forward, backward, left, or right).

A reward of +1 is provided if the agent collects a yellow banana, whereas, a reward of -1 is provided if the agent collects a blue banana.

The environment is considered to be solved if the agent scores with an average of 13.0 or more for 100 consecutive episodes or more.

## Python Packages Required

- numpy
- collections
- torch
- pickle
- matplotlib
- random

## Getting Started

1. Download the environment based on your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    
    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

    (_For AWS_) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the environment.

2. Place all the files from this repository in the `p1_navigation/` folder.

3. Run 'Navigation.ipynb'.


## Description of Each File

| File Name             | Description                                                                    |
|-----------------------|--------------------------------------------------------------------------------|
| Navigation.ipynb    | Main file that trains a DQN agent |
| Readme.md    | This readme |
| Report.pdf    | A short report on the project |
| dqn_agent.py    | Python code that contains the algorithmic implementation of DQN |
| model.py    | A python file that defines the neural network objects used by the DQN agent |
