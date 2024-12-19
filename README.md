# Space Invaders DQN Agent

This project implements a Deep Q-Network (DQN) agent to play the **Space Invaders** game using the **gymnasium** environment. The agent uses a convolutional neural network (CNN) to predict Q-values for different actions and is trained with an epsilon-greedy policy for exploration.

## Overview

- The agent is trained using the **Deep Q-Learning** algorithm with experience replay and target networks.
- The **Space Invaders** environment from **gymnasium** is used, with preprocessing applied to the game frames.
- The agent explores the environment using an epsilon-greedy strategy, gradually shifting from exploration to exploitation.
- The model is saved periodically during training, but only after every `10000` frames.

## Requirements

This project requires Python 3.12.5 and the following libraries:

- **Python**
- **tensorflow**
- **keras**
- **gymnasium** (requires downgrading to v0.29.1)
- **ale_py**
- **numpy**
  
### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Kevi22/Deep-Learning-Kevin-Fu
2. **Setup virtual enviorment**:
   ```bash
   python3 -m venv venv

   source venv/bin/activate  # On windows use venv\Scripts\activate

3. **Python packages**:
   ```bash
   pip install -r requirements.txt
