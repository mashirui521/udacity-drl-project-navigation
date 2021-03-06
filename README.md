[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif "Trained Agent"

# Deep Reinforment Learning Project 1: Navigation

### Introduction

This project is for Udacity Nanodegree program "Deep Reinforcement Learning". In this project,  an agent was trained to navigate (and collect bananas!) in a large, square world, using value-based reinforment learning (RL) with Deep Q-Network (DQN) algorithm.
This project is built based on the Unity ML-Agent, see [here](https://github.com/Unity-Technologies/ml-agents)

![Trained Agent][image1]

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana.  Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.  

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  Given this information, the agent has to learn how to best select actions.  Four discrete actions are available, corresponding to:
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

The task is episodic, where each episode terminates after 1000 steps. The environment is considered solved when the trained agent obtains an average score of 13 over 100 consecutive episodes.

### Prerequisites
- Python 3.6
- Pytorch 0.4.0
- matplotlib 3.3.4
- Jupyter Notebook
- OpenAI Gym 0.19.0

### Installation
1. Clone the repository `git clone https://github.com/mashirui521/udacity-drl-project-navigation.git`

2. `pip install -r requirements.txt`

### Getting Started
1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    
    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

2. Place the file in the cloned repository and unzip (or decompress) the file. 

### Instructions

Open the notebook `Navigation.ipynb` and follow the instructions. This project is trained by using CPU. GPU is not tested. The training and testing results of the agent are illustrated in the `Report.html`, where the average score over 100 consecutive episodes and the score in the testing are reached 16
