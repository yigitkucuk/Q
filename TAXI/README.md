---
tags:
- q-learning
- reinforcement-learning
- custom-implementation
model-index:
- name: TAXI
  results:
  - task:
      type: reinforcement-learning
      name: reinforcement-learning
    dataset:
      name: Taxi-v3
      type: Taxi-v3
    metrics:
    - type: mean_reward
      value: 7.56 +/- 2.71
      name: mean_reward
      verified: false
---

  # **Q-Learning** Agent playing **Taxi-v3**
  This is a trained model of a **Q-Learning** agent playing **Taxi-v3** .

  ## Usage

  ```python
  model = load_from_hub(repo_id="yigitkucuk/TAXI", filename="q-learning.pkl")

  env = gym.make(model["env_id"])
  ```
  