# Customer Funnel Q-Learning & Ray DQN (Reinforcement Learning)

*A complete RL framework for modeling and optimizing customer journeys through marketing funnels.*

---

## Repository Overview

This repository implements **two complementary reinforcement learning approaches** to model and optimize customer progression through a marketing funnel:

### 1. Tabular Q-Learning (Manual)

* Uses Q-tables
* Simple, interpretable learning process
* Demonstrates baseline RL behavior
* Good for understanding stage transitions and reward shaping

### 2. Deep Q-Network (DQN) using Ray RLlib

* Scalable, neural-network-based Q-function
* Handles more complex environments than tabular RL
* Includes:
  * Gymnasium-compatible custom funnel environment
  * Replay buffers
  * ε-greedy exploration
  * Target networks
  * Q-value extraction
  * Policy path analysis (best, second-best, direct conversion paths)

Together, these components provide a __full RL experimentation suite__ for __customer funnel optimization__.

Refer to my __Medium-published thought__, which explores core pillars of my work— __Optimization, Experimentation, Personalization, AI Governance, and Semantic Intelligence__ —providing practical insights grounded in real-world implementation.
https://medium.com/@shukla.shankar.ravi
