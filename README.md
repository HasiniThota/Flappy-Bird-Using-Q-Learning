# Flappy Bird Using Q-Learning

A Python-based project that applies Q-learning, a reinforcement learning algorithm, to train an autonomous agent to play the game *Flappy Bird*. The agent learns to navigate through obstacles by maximizing cumulative rewards.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [Future Enhancements](#future-enhancements)

## Introduction
This project demonstrates how Q-learning can be applied to a dynamic environment like *Flappy Bird*. The agent, through iterative learning, optimizes its gameplay strategy, improving its score by making strategic decisions to navigate through pipes.

## Features
- **Autonomous Gameplay**: The agent learns to play Flappy Bird without human intervention.
- **Reinforcement Learning**: Uses Q-learning to update the agent’s strategy based on rewards and penalties.
- **Learning Visualization**: Shows the agent’s score progression across generations, providing insights into its learning process.

## Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/FlappyBird-Qlearning.git
   ```
2. **Install dependencies**:
   ```bash
   pip install pygame numpy matplotlib
   ```

## Usage
1. **Run the project**:
   ```bash
   python RL_project.py
   ```
2. **Gameplay Observation**:
   - The agent autonomously decides when to flap, aiming to pass through pipes to increase its score.
   - A plot of the learning curve will appear, showing how the agent’s performance improves over time.

## Project Structure
- `RL_project.py`: Main code containing the Q-learning implementation, game logic, and environment simulation.
- `img/`: Folder with images for game assets, such as the bird, pipes, and background.

## Results
The agent shows steady improvement after multiple training generations, with notable outcomes:
- **Score Increase**: Scores rise as the agent refines its decision-making.
- **Learning Curve**: Matplotlib-generated visualization of score improvement across generations.

## Future Enhancements
Consider further optimizing the agent's learning:
- **Parameter Tuning**: Experiment with learning rates and exploration settings.
- **Deep Q-Learning**: Use a neural network to approximate Q-values, enhancing decision-making in complex scenarios.
