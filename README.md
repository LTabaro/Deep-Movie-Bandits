# Reinforcement Learning for Movie Recommendations

This project implements a reinforcement learning (multi-armed bandit) framework for personalised movie recommendation using self-supervised movie embeddings. Inspired by the approach in *"Reinforcement Learning Approaches to Movies Recommendation"* (Carpentier et al., 2015), the system learns user preferences over time by interacting with them through simulated recommendation episodes.

The model uses a content-based strategy with learned embeddings from a lightweight autoencoder trained on movie metadata (genre and year).

---

## Setup

### 1. Clone the repo
```bash
git clone https://github.com/your-username/rl-movie-recommender.git
cd rl-movie-recommender
