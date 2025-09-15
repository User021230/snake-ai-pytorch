# Snake AI PyTorch

This repository contains code for training a reinforcement learning agent to play the classic Snake game using PyTorch.

## Files

- `model.py` — Defines the neural network model and training logic.
- `agent.py` — Implements the agent, memory, and training loop.
- `game.py` — Contains the Snake game logic and rendering.
- `helper.py` — Utility functions for plotting training progress.

## Prerequisites

- Anaconda (Python 3.9 recommended)

## Setup

Before running the agent, execute the following commands:

```sh
conda create --name py_env python=3.9
conda activate py_env
pip install torch torchvision
```

## Running the Agent

To start training the agent to play Snake, run:

```sh
python agent.py
```

## Description

- The agent uses a neural network to predict actions and improve its gameplay over time.
- Training is handled by the agent, which interacts with the game environment.
- Training progress can be visualized using helper utilities.

## License

MIT License.
