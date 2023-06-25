# DQN Agent for Breakout Game

This repository contains an implementation of a DQN (Deep Q-Network) agent for training and playing the Breakout game. The agent uses a neural network model and the Double DQN algorithm to improve its performance.

## Prerequisites

Make sure you have the following dependencies installed:

- Python (version 3.x)
- PyTorch (version 1.x)
- OpenAI Gym

  ## File Structure

- `agent.py`: Contains the implementation of the DQN agent.
- `agent_double.py`: Contains the implementation of the double DQN agent.
- `model.py`: Defines the neural network model used by the agent.
- `memory.py`: Implements the replay memory for experience replay.
- `config.py`: Contains the configuration parameters for training.
- `utils.py`: Provides utility functions for preprocessing game frames.
- `save_model/`: Directory to save the trained models.
- `save_graph/`: Directory to save the training visualization graphs.

![dqn](https://user-images.githubusercontent.com/98642342/235613327-9d05296e-a462-43d6-9a90-ff32046a138f.gif)
