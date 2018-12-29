Author: Wes Brewer <wes@computational.io>

## Introduction

This code solves the Unity ML-Agents Banana Collector environment using a deep Q-network reinforcement algorithm implemented using PyTorch. In the Bananas environment, there are four possible actions:

* 0 - walk forward
* 1 - walk backward
* 2 - turn left
* 3 - turn right

The state space has `37` dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  A reward of `+1` is provided for collecting a yellow banana, and a reward of `-1` is provided for collecting a blue banana. 

## How to Install

The Unity environment needs to be installed from one of the following links:

* Linux: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip
* Mac OSX: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip
* Windows (32-bit): https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip
* Windows (64-bit): https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip

This project uses Python 3 with the following required packages:

* numpy==1.14.3
* unityagents==0.4.0
* torch==1.0.0
* matplotlib==2.2.2

To install all the required packages, run:

`python -r requirements.txt`

## Notes

The trained weights are saved as `checkpoint.pth`

