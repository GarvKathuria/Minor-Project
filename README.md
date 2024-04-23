# Snake Game with Q-Learning

## Overview

This project implements the classic Snake Game using two different approaches: one without Q-Learning and the other with Q-Learning. The Snake Game is a popular arcade game where the player controls a snake that moves around a board, eating food to grow longer while avoiding collisions with the snake's own body and the boundaries of the board.

### Components

- **Snake Game**: This module contains the main logic for the Snake Game, including the game board, the snake object, methods for moving the snake, spawning food, checking game states, and calculating rewards.
  
- **Snake Game without Q-Learning**: This part of the project implements the Snake Game without using Q-Learning for decision making. The snake moves based on predefined rules, and the game continues until the snake collides with itself or the board boundaries.

- **Snake Game using Q-Learning**: Here, Q-Learning is applied to train an AI agent to play the Snake Game. The agent learns to make decisions based on the current game state and potential future rewards. The Q-Learning algorithm updates the Q-values based on the agent's actions and rewards.

- **Animation**: An animation feature is included to visualize the gameplay at different stages of training. This helps in understanding how the AI agent learns to play the game over multiple episodes.

## Instructions

### Setup

To run the Snake Game with Q-Learning, follow these steps:

1. Install the required dependencies (NumPy, Matplotlib).
2. Ensure Python 3.x is installed on your system.
3. Download or clone the repository containing the source code.
4. Navigate to the directory containing the Python scripts.

### Running the Game

- Execute the script `snake_game_with_q_learning.py` to start training the AI agent using Q-Learning. Adjust the parameters such as the number of episodes, board dimensions, and exploration rate as needed.

- Once the training is complete, the script will output a convergence graph showing the learning progress of the Q-Learning algorithm.

- You can also run the Snake Game without Q-Learning by executing the script `snake_game_without_q_learning.py`. This allows you to play the game manually using keyboard inputs.

### Animation

- The animations of the Snake Game's progress at different training episodes are generated automatically. You can visualize how the AI agent improves its gameplay over time.

- The animations will display the game board, the snake's movements, and the food items, providing insights into the learning process of the AI agent.


