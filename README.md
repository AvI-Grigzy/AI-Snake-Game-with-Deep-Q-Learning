# AI Snake Game with Deep Q-Learning

## Overview
This project implements a classic Snake game where an AI agent learns to play the game using Reinforcement Learning, specifically the Deep Q-Learning algorithm. The goal of the agent is to maximize the score by eating food and growing longer without colliding with the walls or itself.

## Features
- **Deep Q-Learning (DQN):** The agent is trained using a neural network to approximate the Q-values for each possible action.
- **Epsilon-Greedy Strategy:** Balances exploration and exploitation during training.
- **Experience Replay:** Uses a memory buffer to store and sample past experiences for training, improving the learning stability.
- **Game Visualization:** The game is rendered in real-time using Pygame, allowing you to visually observe the agent's performance.
- **Model Saving and Loading:** The trained model can be saved and loaded for testing or further training.

## Requirements
- Python 3.6+
- Pygame
- Numpy
- PyTorch

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/AvI-Grigzy/AI-Snake-Game-with-Deep-Q-Learning.git
    cd ai-snake-game-dqn
    ```

2. **Install the required dependencies:**
    ```bash
    pip install pygame numpy torch
    ```

## Usage
### 1. Play the Game Manually
You can play the Snake game manually to explore and test the game environment. This allows you to experience the gameplay firsthand and verify the mechanics before or after AI training.
### 2. Train the Agent
To train the AI agent from scratch, run the training function from the program.
### 3. Test the Agent 
Once the AI agent has been trained, you can evaluate its performance by running the game in testing mode. This allows the trained model to control the snake, demonstrating the skills it has learned. 

## Acknowledgments
* pygame library for offering an intuitive framework to build the game.
* PyTorch for facilitating the development of the neural network.


