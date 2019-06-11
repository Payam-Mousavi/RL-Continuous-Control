[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/43851024-320ba930-9aff-11e8-8493-ee547c6af349.gif "Trained Agent"
[image2]: https://user-images.githubusercontent.com/10624937/43851646-d899bf20-9b00-11e8-858c-29b5c2c94ccc.png "Crawler"


# Project 2: Continuous Control
## Payam Mousavi

### Introduction

For this project, I worked with [Reacher](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#reacher) environment.

![Trained Agent][image1]

In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that
the agent's hand is in the goal location. Thus, the goal of the agent is to maintain its position at the target location
for as long as possible. I chose to use the [DDPG algorithm](https://spinningup.openai.com/en/latest/algorithms/ddpg.html) 
to solve this challenge.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of
the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the
action vector should be a number between -1 and 1.

### Environment version:
I chose to work with the first version of the Unity environment provided: 

A single agent was trained. The task is episodic, and in order to solve the environment,  the agent was required
to get an average score of +30 over 100 consecutive episodes.



### Downloading the environment:

Download the environment from one of the links below.  You need only select the environment that matches your operating system:

   - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip)
   - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip)
   - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86.zip)
   - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip)


 
### Instructions

The required Python packages are listed in `requirements.txt`
Follow the instructions in `Project_2_Contiuous_Control.ipynb` to train and evaluate the agent. 

