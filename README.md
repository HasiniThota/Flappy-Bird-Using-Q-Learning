# Flappy Bird Using Q-Learning

A Python-based project that applies the Q-learning algorithm, a form of reinforcement learning, to train an agent to play the game *Flappy Bird*. The agent learns optimal strategies through trial and error, aiming to maximize its score by navigating through pipes in the game environment.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Q-Learning Overview](#q-learning-overview)
- [Results](#results)
- [Future Work](#future-work)

## Introduction
This project explores reinforcement learning's effectiveness in game optimization by training an autonomous agent to play *Flappy Bird*. Using the Q-learning algorithm, the agent iteratively improves its strategy by maximizing cumulative rewards based on its interactions within the game environment.

### Objective
- Train an agent that can autonomously navigate *Flappy Bird*, avoiding obstacles and maximizing rewards.
- Evaluate the agent's performance using metrics such as score, generations, and visualized learning progress.

## Features
- **Reinforcement Learning**: Implements Q-learning to optimize the agent’s decisions in a dynamic environment.
- **Customizable Game Environment**: Simulates the *Flappy Bird* game with adjustable parameters.
- **Real-Time Score Display**: Displays score progression and performance metrics on-screen.
- **Performance Visualization**: Uses `matplotlib` to visualize the agent's learning progress across generations.

## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/FlappyBird-Qlearning.git
   ```
2. **Install dependencies:**
   - Python 3.8 or higher
   - [pygame](https://www.pygame.org/) for game rendering
   - [numpy](https://numpy.org/) for numerical operations
   - [matplotlib](https://matplotlib.org/) for visualizations

   ```bash
   pip install pygame numpy matplotlib
   ```

## Usage
1. **Run the project:**
   ```bash
   python RL_project.py
   ```
2. **Gameplay:**
   - The agent will begin attempting to navigate the game environment.
   - Pressing the spacebar will make the bird flap its wings (if needed for testing).
3. **Visualization of Learning:**
   - The program will display the agent’s learning curve after each generation.

## Q-Learning Overview
Q-learning is a reinforcement learning algorithm designed for training agents to make decisions. It uses a value iteration approach to maximize the cumulative reward in a discrete state-action space.

### Key Concepts
- **State**: Position, velocity, and spatial relationship of the bird and pipes.
- **Action**: Binary choice – flap (ascend) or do nothing.
- **Reward**: Positive for passing through pipes; negative for collisions.

### Algorithm Outline
1. **Initialize Q-values** to zero.
2. **Iterate** over episodes:
   - Choose an action based on an exploration-exploitation strategy.
   - Update Q-values based on observed rewards and future state estimates.
3. **Policy Derivation**: Select actions that maximize Q-values.

## Results
After multiple generations, the agent demonstrates improved performance in navigating the *Flappy Bird* environment. Key outcomes:
- **Score Improvement**: Scores increase over generations, showing the agent’s learning.
- **Learning Curve Visualization**: *matplotlib* graphs provide insights into the agent’s progress, highlighting score improvements across generations.
- **Challenges**: The agent encountered difficulty with precise timing in narrow gaps, a notable challenge in the Flappy Bird environment.

## Future Work
Further optimization can enhance the agent’s efficiency and adaptability:
- **Hyperparameter Tuning**: Adjust learning rates and discount factors.
- **Exploration of Deep Q-Learning**: Improve decision-making with neural network-based Q-value approximation.
- **Generalization**: Apply similar approaches to other complex game environments or real-world scenarios.
