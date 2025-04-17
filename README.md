# Reinforcement-learning-breakout
Training an AI Agent with Deep Q-Networks (DQN)

## Overview
 
This project leverages Deep Q-Learning (DQN) to train an AI agent to play Atari Breakout using raw pixel inputs. The agent learns optimal gameplay strategies through trial and error, stabilized by techniques such as experience replay and a target network.

Training was performed in Google Colab with a T4 GPU, and model checkpoints were saved every 1,000 episodes. Final performance is demonstrated via training metrics and a gameplay video of the trained agent.

---
## Goals

- Train a fully autonomous agent for Atari Breakout

- Implement DQN with visual state inputs

- Visualize learning progress and evaluate performance



---
## Features

 - Custom DQN implementation using TensorFlow/Keras

 - CNN-based architecture for image frame processing

 - Experience Replay & Target Network for stability

 - Periodic model checkpointing

 - Detailed reward tracking and visual analytics


---
## Tech Stack
- Python 3.10+, TensorFlow/Keras

- OpenAI Gym (Breakout-v0)

- NumPy, Matplotlib

- Google Colab (T4 GPU)

---
## Results
- Trained over 32,000 episodes

- Achieved consistent performance gains

- Learned advanced behaviors (e.g., ball control, targeting)

- Training was resumed from checkpoints after Colab session interruption

---

## Gameplay video of the trained agent
![breakout-vedio](https://github.com/user-attachments/assets/43c3efd8-5b30-4367-8b83-a46019fe7a8d)

---

