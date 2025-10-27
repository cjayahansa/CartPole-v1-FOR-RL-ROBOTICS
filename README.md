# CartPole-v1-with-RLAgent-ROBOTICS
# 🧠 CartPole Reinforcement Learning Project

This project demonstrates how an intelligent agent can learn to balance a pole on a moving cart using **Reinforcement Learning (RL)** techniques.  
The simulation is based on the classic **CartPole-v1** environment from **Gymnasium (OpenAI Gym)**.

---

## 🚀 Project Overview

The **CartPole** problem is a benchmark task in control theory and reinforcement learning.  
A pole is attached by an un-actuated joint to a cart, which moves along a frictionless track.  
The agent must learn to apply forces (left or right) to keep the pole upright.

The episode ends when:
- The pole angle exceeds ±12 degrees from vertical.
- The cart moves more than ±2.4 units from the center.
- Or the maximum number of steps (500) is reached.

The goal is to **maximize the total reward**, achieved by keeping the pole balanced for as long as possible.



[![Watch the video_with Agent]](https://drive.google.com/file/d/18xDInJd_nALq3RsG6aQhGNbqegrsw3qY/view?usp=drive_link).
---
[![Watch the video with Out Agent]](https://drive.google.com/file/d/160tspPztNfcQbB76HVJQom0j1Qu4QqYX/view?usp=drive_link).
---



---

## 🧩 Features

- ✅ Classic **CartPole-v1** control environment
- 🧠 **Deep Q-Learning (DQN)** implementation
- 📊 **TensorBoard** support for visualization
- 📈 Training progress graphs for reward tracking
- 💾 Model saving and loading support
- 🧰 Easy to customize and extend with new algorithms

---

## ⚙️ Technologies Used

| Tool / Library | Purpose |
|----------------|----------|
| **Python 3.x** | Main programming language |
| **Gymnasium / OpenAI Gym** | RL environment |
| **NumPy** | Numerical computations |
| **TensorFlow / Keras** | Neural network for DQN |
| **Matplotlib** | Reward visualization |
| **TensorBoard** | Performance monitoring |

---

## 🧠 How It Works

1. **Environment Initialization**
   - Load the CartPole-v1 environment.
   - Define observation and action spaces.

2. **Neural Network Policy**
   - Use a small feed-forward neural network to approximate Q-values.

3. **Agent Training**
   - The agent interacts with the environment, stores experience in memory, and learns via Q-value updates.

4. **Reward System**
   - +1 reward for every step the pole remains upright.

5. **Model Evaluation**
   - After training, the model is tested to check how long it can balance the pole.

---

## 📁 Project Structure

