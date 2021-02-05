# deep_learning_2

It contains code,report,optimal weights

# Project Details

Environment:
Single agent version environment

Continuous space
33 variables for arm position coordinates, rotation, velocity, and each velocity

Action space
4 numerical vectors(action_value vectore) for the joints of each arm(-1<=action_value<=1)

Reward
Agent gets reward +0.1 when its arm's position coincide the target position.

Conditions for the achievement of the global target
Agents perform more than 100 tasks using DDPG, a policy-based reinforcement learning method. A task is terminated if the reward exceeds 30.

# introduction
All my work was done on a GPU environment given by Udacity. 
1. Clone the [DRLND GitHub repository](https://github.com/udacity/deep-reinforcement-learning) . 

2. Download the Unity environment below.

1 Agent
for Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip)
for Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip)
for Windows x32: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86.zip)
for Windows x64: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip)

20 Agents
for Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Linux.zip)
for Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher.app.zip)
for Windows x32: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86.zip)
for Windows x64: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86_64.zip)


# instruction

<*> means optional step　　

1.Open Continuous_Control.ipynb　　

2.Load the library　　

3.Start the gym environment　　

4*.Observe the environment as needed　　

5.Initialize the environment　　

6.Define states and actions　　

7.Train using DDPG.　　

8.Save the weights of the neural network when the reward exceeds 30.　　

9*.Observe the training results.　　

10.Terminate the environment.



