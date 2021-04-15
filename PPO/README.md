# CartPole via PPO - PyTorch 

## Description

A reward of +1 is provided for every step taken, and a reward of 0 is provided at the termination step. The state space has 4 dimensions and contains the cart position, velocity, pole angle and pole velocity at tip. Given this information, the agent has to learn how to select best actions. Two discrete actions are available, corresponding to:

- 0 - 'Push cart to the left'
- 1 - 'Push cart to the right'
