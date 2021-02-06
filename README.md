# Acrobot-v1

This repo trains a policy in the Acrobot-v1 environment using a minimal implementation of the REINFORCE algorithm.

# Environment Description

State Space: 6 continuous values. Shape = (6,)
Action Space: 1 of 3 possible values: (-1, 0, 1). Shape = (1,)

Objective: Swing the two-link, two-joint object up to the horizontal line. 

# Policy Model Description
The policy model maps states to actions. I used a feed-forward neural network (FFNN) with one hidden layer of 32 units and ReLU activations followed by a softmax output layer of 3 units.

Thanks to: https://github.com/david-wb/acrobot-v1 . Improved this version.

