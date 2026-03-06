# RL_129
AI-Based Smart Decision System

AI-Based Intelligent Decision System using UCB and Machine Learning

📌 Project Overview
This project demonstrates how Artificial Intelligence algorithms can learn optimal decisions automatically through experience and data.
It combines Reinforcement Learning (Multi-Armed Bandit using UCB) and Supervised Learning (Decision Tree / PAC Learning) to simulate intelligent decision-making systems.

The project contains three simulations:

IoT-Based Smart Home Optimization

Multi-Armed Bandit Decision System

Chess Move Prediction using Machine Learning

These implementations illustrate how AI systems can adaptively select the best action among multiple choices to maximize efficiency or reward.

🧠 Key Concepts Used

Artificial Intelligence

Reinforcement Learning

Multi-Armed Bandit Problem

Upper Confidence Bound (UCB) Algorithm

PAC Learning

Decision Trees

IoT Smart Systems

Machine Learning

🏠 1. IoT-Based Smart Home System

This module simulates a smart home environment where AI learns which device provides the best efficiency.

Example devices:

Smart Light

Smart AC

Smart Heater

The system uses the Upper Confidence Bound (UCB) algorithm to decide which device to activate in order to maximize energy efficiency over time.

Example Output
Total efficiency after 100 steps: 76
Estimated efficiencies: [0.69, 0.61, 0.82]

The algorithm gradually learns which device performs best.

. Multi-Armed Bandit Simulation

This module demonstrates the classic Multi-Armed Bandit problem.

The system must choose between multiple actions (slot machines), each having a different probability of reward.

Example probabilities:

Machine 1 → 10%
Machine 2 → 50%
Machine 3 → 80%

Using the UCB algorithm, the system balances:

Exploration – trying different options

Exploitation – selecting the best option discovered so far

Example Output
Total reward after 100 rounds: 81
Estimated values: [0.11, 0.52, 0.79]

♟️ 3. Chess Move Prediction (PAC Learning)

This module trains a Decision Tree Machine Learning model to predict the optimal chess move based on board states.

Steps involved:

Generate synthetic chess board data

Split the dataset into training and testing sets

Train a Decision Tree classifier

Evaluate model accuracy

Example Output
PAC Model Accuracy: 19.40%

This demonstrates the concept of PAC (Probably Approximately Correct) Learning.
