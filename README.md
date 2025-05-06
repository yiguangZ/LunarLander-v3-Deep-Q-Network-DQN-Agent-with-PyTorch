# 🚀 LunarLander-v3: Deep Q-Network (DQN) Agent with PyTorch

This project implements a Deep Q-Network (DQN) agent to solve the LunarLander-v3 environment from OpenAI Gym using PyTorch. The agent learns to land a spacecraft safely between landing pads by approximating the optimal Q-value function from experience.

## 🎯 Objective
Train a reinforcement learning agent to land the lunar module smoothly by learning optimal actions from trial-and-error interactions with the environment.

## 🧠 Key Features

- **Deep Q-Network (DQN):** Uses a fully connected neural network to approximate Q-values.
- **Experience Replay:** Stores past transitions and samples them randomly to break correlation in updates.
- **Target Network:** Stabilizes training by updating a separate target network periodically.
- **Epsilon-Greedy Strategy:** Balances exploration and exploitation during training.
- **Reward Clipping and Normalization:** Ensures stable training dynamics.

## 🛠️ Technologies Used

- **Python 3**
- **PyTorch**
- **OpenAI Gym**
- **NumPy**

## 🧪 Training Results

- Achieves consistent landings with high episodic rewards.
- Training stabilizes with average scores well above the environment's solved threshold.

## 📁 Files

- `dqn_agent.py` – Implementation of the DQN agent class.
- `train.py` – Main training loop and environment interaction.
- `LunarLander-v3_dqn.pt` – Trained model checkpoint.
- `utils.py` – Helper functions for replay buffer and neural network.
- `requirements.txt` – Python dependencies.

## 🚀 How to Run

1. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
