# RL from scratch

Reinforcement learning from scratch: maths, intuition and code for every algorithm.

📢 I post daily logs on what I'm learning on X, follow along: [@shreya_sajal](https://x.com/shreya_sajal)

Each notebook builds up one idea: the theory and derivations first, then a from-scratch implementation in NumPy on Gymnasium environments, then experiments and what I learned from them.

## Notebooks

### Part 1: Model-based learning (dynamic programming)

| # | Notebook | What's inside |
|---|---|---|
| 01 | [Intro to RL + Policy Iteration](model_based_learning/01_intro_rl_and_policy_iteration.ipynb) | MDPs, values, Bellman equation derivation, optimality equations, contraction + Banach fixed-point theorem, policy iteration |
| 02 | Value Iteration *(coming soon)* | Bellman optimality backup, why it converges, PI vs VI |

### Part 2: Model-free learning

| # | Notebook | What's inside |
|---|---|---|
| 03 | Monte Carlo *(coming soon)* | Learning from episodes, ε-greedy, online averaging |
| 04 | SARSA *(coming soon)* | TD learning, bootstrapping, on-policy control |
| 05 | Q-learning *(coming soon)* | Off-policy control, SARSA vs Q-learning on CliffWalking |
| 06 | n-step TD *(coming soon)* | Bias-variance trade-off between TD and Monte Carlo |
| 07 | TD(λ) *(coming soon)* | λ-returns, eligibility traces |

## Handwritten notes

- [Bellman equation derivation](notes/bellman_equation_derivation.pdf)

## Running the notebooks

```bash
pip install -r requirements.txt
jupyter notebook
```

Or open any notebook in Colab: `https://colab.research.google.com/github/shreyasajal/reinforcement_learning/blob/main/<path-to-notebook>`

