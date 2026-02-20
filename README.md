# AI Savanna Simulator (DQN)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Keras-orange)
![Pygame](https://img.shields.io/badge/Library-Pygame-green)

## 📋 About The Project

This project demonstrates the practical application of **Reinforcement Learning (RL)**. Unlike traditional hard-coded AI, the agents in this simulation are not programmed with explicit rules on how to move. Instead, they utilize a **Deep Q-Network (DQN)** to learn optimal strategies through trial and error, responding to rewards and penalties defined in the environment.

The simulation visualizes the inference phase where the AI utilizes pre-trained models (`.h5` files) to navigate the savanna map efficiently.

## 🚀 Key Features

*   **Deep Q-Learning Implementation:** Custom implementation of DQN logic using Keras/TensorFlow.
*   **Neural Network Brain:** Agents make decisions based on inputs from their immediate environment (vision).
*   **Pygame Visualization:** Real-time rendering of the ecosystem.
*   **Pre-trained Models:** Includes trained models (`model2.h5`, `model3.h5`) demonstrating different stages of learning.

## 🛠️ Tech Stack

*   **Language:** Python 3
*   **ML Framework:** TensorFlow / Keras
*   **Visualization:** Pygame
*   **Math:** NumPy

## 📂 Project Structure

*   `test.py` - **Main entry point.** Runs the simulation using a pre-trained model to show the AI in action.
*   `train.py` - Script used to train the neural network from scratch (exploration & exploitation phase).
*   `dqn.py` - Contains the Deep Q-Network architecture and replay memory logic.
*   `brain.py` - The agent's "brain" class that interfaces with the DQN.
*   `environment.py` - Defines the simulation rules, physics, states, and rewards.
*   `modelX.h5` - Saved weights of the trained neural networks.

## ⚙️ Getting Started

### Prerequisites & Installation

Make sure you have Python installed. You need to install the necessary libraries manually using pip:

```bash
pip install tensorflow keras pygame numpy
