# Snake Game AI 🐍🎮

## Overview
This project is a Snake Game AI that uses reinforcement learning, specifically Deep Q-Learning, to train a snake to play the game autonomously. The AI agent learns to navigate the game environment, avoid collisions, and consume food to grow in size.

## Methodology
The AI agent is implemented using a neural network that predicts the optimal move based on the current state of the game. The state is represented by an array of values indicating the immediate danger, direction of movement, and food location relative to the snake's head. The agent uses an epsilon-greedy strategy to balance exploration and exploitation during training.

## Libraries Used
- `torch`: An open-source machine learning library used for the neural network model.
- `numpy`: A library for numerical computations in Python.
- `collections`: A module that implements specialized container datatypes.

## Files
- `agent.py`: Contains the `Agent` class that defines the behavior of the AI agent, including state representation, memory, and training methods.
- `model.py`: Defines the neural network architecture (`LINEAR_QNET`) and the training process (`QTrainer`).

## How to Run
To train the AI agent, simply run the `agent.py` script:

```python
python agent.py
```

---
