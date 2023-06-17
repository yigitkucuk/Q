---
tags:
- FrozenLake-v1-4x4
- q-learning
- reinforcement-learning
- custom-implementation
model-index:
- name: FLS
  results:
  - task:
      type: reinforcement-learning
      name: reinforcement-learning
    dataset:
      name: FrozenLake-v1-4x4
      type: FrozenLake-v1-4x4
    metrics:
    - type: mean_reward
      value: 0.56 +/- 0.50
      name: mean_reward
      verified: false
---

  # **Q-Learning** Agent playing **FrozenLake**
  This is a trained model of a **Q-Learning** agent playing **FrozenLake** .

  ## Usage

  ```python
  model = load_from_hub(repo_id="yigitkucuk/FLS", filename="q-learning.pkl")

  env = gym.make(model["env_id"])
  ```
  