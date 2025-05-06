# 🧠 Deep Q-Learning on CartPole using PyTorch

This project is a tutorial-style notebook demonstrating how to train a Deep Q-Network (DQN) agent using PyTorch to solve the CartPole-v1 environment from [Gymnasium](https://gymnasium.farama.org).

The notebook is based on work by Adam Paszke and Mark Towers, with major edits by Matthew Dupree and Heekyung Lee for UCSB's ECE 157B/272B course (Winter 2025).

## 🎯 Objective

Train an agent to balance a pole on a moving cart by learning an optimal policy via reinforcement learning. The agent observes a 4-dimensional state and selects from two possible actions (move left or right). The environment terminates when the pole falls or the cart moves out of bounds.

## 🚀 Features

- Custom implementation of DQN using PyTorch
- CartPole-v1 task from Gymnasium classic control suite
- Replay buffer for experience replay
- Target network for stable Q-learning
- Performance evaluation and visualization
- Video generation of agent performance using `moviepy` and `ffmpeg`

## 📦 Dependencies

Install the required packages using:

```bash
pip install swig
pip install torch gymnasium[classic_control,box2d] pandas numpy nbformat plotly tqdm moviepy ffmpeg ipywidgets
```

For Colab users: If video rendering fails, install ffmpeg manually:

```bash
!apt-get install ffmpeg
```

## 📈 Output

- Real-time training statistics
- Interactive reward plots (via Plotly)
- Saved videos demonstrating the trained agent's performance

## 📁 File Structure

- `ECE_157B_272B_W24_Homework4__1_.ipynb`: Main notebook with all code and commentary
- `videos/`: Folder (optional) for storing recorded videos
- `README.md`: Project overview and setup instructions

## 🖥️ Author Credits

- Original notebook: Adam Paszke, Mark Towers
- UCSB Edits: Matthew Dupree, Heekyung Lee
- Student Work: Yiguang Zhu (based on ECE 157B/272B Winter 2025)

---

This project is a great starting point for anyone interested in deep reinforcement learning with PyTorch and Gym environments.
