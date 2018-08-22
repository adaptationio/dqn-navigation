# Deep Reinforcement Learning - Navigation - DQN in Pytorch
## Introduction
The environment is a square world filled with yellow and blue bananas. The goal of the agent is to collect yellow bananas while avoiding blue bananas.

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

    0 - move forward.
    1 - move backward.
    2 - turn left.
    3 - turn right.

## Getting Started

### Dependencies
- Python 3.6 or higher (https://www.anaconda.com/download) or (https://www.python.org/downloads/) 
- Optional but recommended Create (and activate) a new environment with Python 3.6.
    Create (and activate) a new environment with Python 3.6.
    - __Linux__ or __Mac__: 
	```bash
	conda create --name drlnd python=3.6
	source activate drlnd
	```
	- __Windows__: 
	```bash
	conda create --name drlnd python=3.6 
	activate drlnd
	```
- Install requirements:
    ```bash
    clone git https://github.com/adaptationio/dqn-navigation.git
    cd dqn-navigation
	pip install .
	```

- Download the correct Unity Environment for OS and copy into same directory as results.ipynb
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) NO Visuel version


## Instructions

- Run:
    ```bash
	jupyter notebook
	```
    Open results.ipynb and run code cells in order




