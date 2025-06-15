# RouteMind-AI
This repository hosts the code and documentation for our RouteMind-AI project. The system leverages reinforcement learning algorithms to train intelligent agents capable of solving taxi dispatch problems through optimized route planning and decision-making.

## Introduction

RouteMind-AI aims to address the classic taxi routing problem using reinforcement learning. By training agents in the OpenAI Gym's Taxi-v3 environment, the system learns efficient policies to transport passengers with minimal steps and maximum rewards. The project explores and compares two key algorithms: Q-learning and SARSA, demonstrating their convergence and adaptability in dynamic environments.

## Project Summary

- **Algorithms Used**: Q-learning, SARSA

- **Key Techniques**: ε-greedy strategy, Q-table updates, reward tracking, step efficiency analysis

## Models and Performance

We implemented and trained Q-learning and SARSA agents with dynamic exploration strategies:

- **Q-learning**: Achieved an average reward of 7.925 and average steps of 13.075 after convergence.

- **SARSA**: Achieved an average reward of 7.865 and average steps of 13.135.

Both algorithms showed effective learning of optimal policies, with Q-learning slightly outperforming in reward optimization.

## Environment

We used the classic Taxi-v3 environment from OpenAI Gym, which simulates a grid world where a taxi agent must pick up and drop off passengers at the correct locations.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Citation

If you use this system or its findings in your research, please cite related literature in the field of reinforcement learning and route optimization.
