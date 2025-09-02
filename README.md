# AI-Kung-Fu-Master
An artificial intelligence agent trained to achieve superhuman performance in a custom "Kung Fu Master" reinforcement learning environment. This project implements and compares state-of-the-art Deep Reinforcement Learning (DRL) algorithms to master a complex fighting game scenario.

***
🎯 ENVIRONMENT OVERVIEW <br/>
The environment is a simplified yet dynamic 2D fighting game, inspired by classic arcade titles. The agent controls a martial artist who must defeat waves of incoming enemies.

1. State Space: Pixel-based (CNN) or feature-based (Dense) observations including character positions, health, and enemy states.

2. Action Space: Discrete set of high-level martial arts moves (e.g., punch, kick, jump, crouch, block, move left/right, and combinations).

3. Reward Signal: Positive rewards for defeating enemies and avoiding attacks. Negative rewards for taking damage. A significant bonus for clearing a wave.

***

🤖 IMPLEMENTED ALGORITHM <br/>
This repository provides implementations of several leading DRL algorithms:

1. PPO (Proximal Policy Optimization): A stable and efficient policy-gradient method, chosen for its balance of simplicity and performance.

2. DQN (Deep Q-Network) & its variants (e.g., Double DQN, Dueling DQN): Value-based methods that learn the optimal action-value function.

3. A2C (Advantage Actor-Critic): A synchronous, deterministic variant of A3C for efficient policy learning.
