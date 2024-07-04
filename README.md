# AI Mastery in Snake: A Reinforcement Learning Approach

This project details the development of an AI agent that learns to play the classic Snake game from scratch. Using PyGame for game development and PyTorch for AI training, we apply reinforcement learning techniques to evolve our AI from basic trial-and-error to strategic gameplay. The results demonstrate the AI's progression and the efficacy of deep learning in real-time problem-solving.

# Key Components
Reinforcement Learning (RL): RL is an area of machine learning concerned with how software agents ought to take actions in an environment to maximize cumulative reward. In this project, the AI agent receives rewards for eating food and penalties for game-over scenarios, learning to play better over time.

Deep Q-Learning: This approach extends RL by using a deep neural network to predict the actions. The network's predictions are used to guide the agent's decisions, improving its performance as it learns from experiences.

# Code Structure:

Game (PyGame): Implements the game environment and handles game logic, such as snake movements, food spawning, and collision detection.
Agent: Manages the AI agent's interaction with the game environment, including state representation, action selection, and memory management.
Model (PyTorch): Defines the neural network architecture (Linear_QNet) and the training process (QTrainer), which updates the network based on the agent's experiences.

## Features

- Classic Snake game implemented using PyGame.
- AI agent trained using Deep Q-Learning with a neural network.
- Visualization of training progress with scores and mean scores.

## File Descriptions

- `agent.py`: Manages the AI agent's state, actions, and learning. It uses a neural network model to predict the best actions to take.
- `game.py`: Implements the Snake game logic and environment using PyGame.
- `helper.py`: Contains utility functions for plotting training progress.
- `model.py`: Defines the neural network architecture and training process for the Q-learning agent.
