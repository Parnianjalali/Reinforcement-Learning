# Reinforcement Learning Projects

This repository contains various projects and implementations related to Reinforcement Learning (RL). The focus is on developing, training, and evaluating different RL algorithms in diverse environments.

## Projects

### 1. Grid World
- **Description**: Implementation of RL algorithms in a simple grid world environment.
- **Algorithms**: Q-learning, SARSA, Value Iteration.
- **Environment**: Custom grid world defined in `grid_world.py`.

### 2. CartPole
- **Description**: Balancing a pole on a cart using RL.
- **Algorithms**: Deep Q-Network (DQN), Policy Gradient.
- **Environment**: OpenAI Gym's CartPole-v1.

### 3. MountainCar
- **Description**: Solving the MountainCar-v0 environment using RL.
- **Algorithms**: SARSA(λ), Q-learning.
- **Environment**: OpenAI Gym's MountainCar-v0.

### 4. FrozenLake
- **Description**: Navigation on a frozen lake with the aim of reaching a goal without falling into holes.
- **Algorithms**: Q-learning, SARSA.
- **Environment**: OpenAI Gym's FrozenLake-v0.

## Getting Started

### Prerequisites
- Python 3.x
- OpenAI Gym
- NumPy
- TensorFlow or PyTorch (for deep learning models)

### Installation
Clone the repository:
```bash
git clone https://github.com/Parnianjalali/Reinforcement-Learning.git
cd Reinforcement-Learning


Reinforcement Learning
Implementing K-Armed Bandit Algorithm Using Python (2021)

Description: Developed a K-Armed Bandit algorithm in Python, simulating the selection of actions from a normal distribution for each arm. Evaluated the performance by running the experiment 1000 times and visualizing the estimated action values.
Greedy Action Selection in K-Armed Bandit Problem (2021)

Description: Implemented greedy action selection in a K-Armed Bandit problem and compared the performance of greedy and epsilon-greedy strategies with different epsilon values (0, 0.1, 0.01). Analyzed the results through multiple experiments and graphical representations.

Implementing FrozenLake Environment with OpenAI Gym (2021)

Description: Implemented the FrozenLake environment from OpenAI Gym using Python. Developed a simulation to perform random actions in the environment and analyzed the resulting state transitions and rewards.
Policy Evaluation Using Dynamic Programming in FrozenLake Environment (2021)

Description: Developed a policy evaluation algorithm using dynamic programming with a discount factor of 0.9. Evaluated the value function and optimal policy for the FrozenLake environment and plotted the changes in state values over iterations.
Monte Carlo Policy Evaluation in FrozenLake Environment (2021)

Description: Applied Monte Carlo methods for policy evaluation in the FrozenLake environment. Compared the results with dynamic programming by plotting the changes in state values over iterations and analyzed the performance differences.
Off-Policy Monte Carlo Evaluation Using Importance Sampling (2021)

Description: Implemented off-policy Monte Carlo evaluation with importance sampling in the FrozenLake environment. Calculated optimal actions and compared the results with previous methods to assess the efficiency and accuracy of the off-policy approach.
Upper Confidence Bound (UCB) in K-Armed Bandit Problem (2021)

Description: Applied the Upper Confidence Bound (UCB) method with a confidence level parameter (c=2) to the K-Armed Bandit problem. Compared the average rewards of the UCB method with epsilon-greedy methods by conducting the experiment over 2000 iterations.
