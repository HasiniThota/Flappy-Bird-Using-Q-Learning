# Flappy Bird Using Q-Learning

A reinforcement learning project that applies the Q-learning algorithm to train an agent to play *Flappy Bird*. The agent learns optimal strategies through trial and error, improving its performance by maximizing cumulative rewards as it navigates through obstacles.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [Future Enhancements](#future-enhancements)

## Introduction
This project showcases reinforcement learning's application in game optimization. Through Q-learning, the agent learns to autonomously play *Flappy Bird*, refining its actions to maximize its score in a dynamic environment.

## Features
- **Autonomous Agent**: Utilizes Q-learning to train an agent for gameplay without human intervention.
- **Dynamic Environment Simulation**: Replicates *Flappy Bird* with moving obstacles and real-time feedback.
- **Visualized Learning Progress**: Displays the agent’s learning curve to demonstrate performance improvements over time.

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
2. **Observe the agent**:
   - The agent autonomously decides when to flap, navigating through obstacles to achieve a higher score.
   - The learning curve is visualized, showing how the agent’s performance improves over generations.

## Project Structure
- `RL_project.py`: Contains the Q-learning algorithm, game setup, and environment simulation.

## Results
The trained agent shows improved performance over multiple generations, with highlights including:
- **Score Improvement**: Higher scores are achieved as the agent refines its gameplay strategy.
- **Learning Curve**: A consistent upward trend in scores, visualized using *matplotlib*.

## Future Enhancements
Potential enhancements include:
- **Hyperparameter Optimization**: Fine-tuning learning rates and exploration-exploitation balance.
- **Advanced RL Techniques**: Experimenting with deeper reinforcement learning models, like Deep Q-Learning, for improved performance.
