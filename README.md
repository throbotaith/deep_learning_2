# deep_learning_2


Intro
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

# introduction
All my work was done on a GPU environment given by Udacity. Therefore, no new files or dependencies were installed in the development environment.


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



