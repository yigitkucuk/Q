---
tags:
- q-learning
- reinforcement-learning
- custom-implementation
model-index:
- name: FLNS
  results:
  - task:
      type: reinforcement-learning
      name: reinforcement-learning
    dataset:
      name: FrozenLake-v1-4x4-no_slippery
      type: FrozenLake-v1-4x4-no_slippery
    metrics:
    - type: mean_reward
      value: 1.00 +/- 0.00
      name: mean_reward
      verified: false
---

  # **Q-Learning** Agent playing **FrozenLake**
  This is a trained model of a **Q-Learning** agent playing **FrozenLake** .

  ## Usage

  ```python
  model = load_from_hub(repo_id="yigitkucuk/FLNS", filename="q-learning.pkl")

  env = gym.make(model["env_id"])
  ```
  