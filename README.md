# Social Media Recommendation Agent Using Deep Reinforcement Learning

This project implements a **social media recommendation system** inspired by Instagram-style feeds. The system uses **Deep Reinforcement Learning (DRL)** to model user interactions and recommend content that maximizes engagement. The agent is trained using **DQN (Deep Q-Networks)**, but the framework can be extended to **PPO** and **A2C**. The environment simulates users, posts, social graphs, and optional cold-start scenarios.

---

## Features

- Synthetic Instagram-style post catalog with:
  - Topics, languages, creators, popularity scores
  - Placeholder images for visualization
- User simulation:
  - Embeddings reflecting topic preferences
  - Language preferences
  - Social network of friends for cold-start handling
- Reinforcement learning agent:
  - DQN-based recommendation
  - Epsilon-greedy exploration
  - Replay buffer and target network updates
- Reward function based on:
  - Engagement, watch proportion, diversity, repetition penalty, retention
- Explainability for each recommendation:
  - Similarity score, language match, friend match fraction, popularity
- Interactive user demo:
  - Optional user-provided preferences
  - Instagram-style feed with technical explanations

---

## Requirements

- Python 3.8+
- Libraries:
pip install numpy pandas matplotlib seaborn torch torchvision gym tqdm scikit-learn


## Clone the repository:
```bash
git clone https://github.com/VarsHini-2520/Reinforcement-Learning-Based-Social-Media-Recommendation-Agent.git
cd RL-Social-Media-Recommendation-Agent


