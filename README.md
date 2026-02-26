# **CSCN8020 – Assignment 2  **
## **Q-Learning on Taxi-v3**

### **Author**
Sabrina Ronnie George Karippatt

---

## **Overview**

This notebook implements tabular Q-Learning on the Taxi-v3 environment using Gymnasium.

The assignment includes:
- Baseline training (α=0.1, ε=0.1, γ=0.9)
- Hyperparameter sweeps for α and ε
- Performance comparison using average and last-100 episode metrics
- Moving average convergence plots (window=100)
- Best configuration selection
- Robustness verification using different random seeds
- Greedy policy evaluation and simulation validation
- Reproducibility via fixed seeds

---

## **Reproducibility**

All experiments use:

SEED = 42

Environment and action space are seeded to ensure deterministic behavior.

---

## **How to Run**

1. Install dependencies:
`pip install -r requirements.txt`
2. Open:
CSCN8020_Assignment2.ipynb

3. Restart Kernel → Run All

---

## **Dependencies**

- Python 3.10+
- gymnasium (Taxi-v3 environment)
- numpy
- matplotlib
- pygame (required for GUI simulation rendering)

>> This implementation follows the standard off-policy Temporal Difference update rule (Bellman optimality equation).