Notoriously, three-stage paradigm for training a GLM(Generative Language Model)
1. **Pretraining:** unsupervised pretraining from raw text, to learn general-purpose representations
2. **Instruction tuning:** aligning Language Models with instruction format data
4. **RLHF:** use human feedback and reinforcement learning technique to better align to end tasks and user preferences.
Not matter pretraining stage, instruction tuning or RLHF stage of LLM, how to mix and utilize data is the key point of model performance. 



## 📃Relevant papers
#### Scaling Relationship on Learning Mathematical Reasoning with Large Language Models

 The correct approach should be to scale up the Reward model to reduce the size of the Policy model, as seen in [Scaling Laws for Reward Model Overoptimization](https://arxiv.org/abs/2210.10760) — that is, reversing the sizes of the two models, using a 175B Reward to PPO a 7B policy.

#### Multitask Prompted Training Enables Zero-Shot Task Generalization






## ☑️Todo List
