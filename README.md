

# 🎮 Grid World Value and Policy Iteration

## 📝 Description

This repository implements Value Iteration and Policy Iteration algorithms for solving a Grid World problem, demonstrating fundamental reinforcement learning concepts in a grid environment.

### 🌟 Features

- Implementation of both Value Iteration and Policy Iteration
- Visualizations of optimal policies and value functions
- Configurable grid world environment

## 🎯 Environment

The environment consists of a 4x5 grid with:

| Cell Type | Description | Value |
|-----------|-------------|--------|
| ⬜ White | Neutral cells | 0 |
| 🟩 Green | Small cost | 1 |
| 🟥 Red | High cost | 10 |
| 🟪 Violet | Goal/Terminal | -1 |
| ⬛ Obstacle | Blocked | ∞ |

### Available Actions
- Stay in place
- Move Right
- Move Down
- Move Left
- Move Up

## 🛠️ Installation

1. Clone the repository
```bash
git clone https://github.com/Abhimanyu-0/grid-world-value-policy-iteration.git
cd grid-world-value-policy-iteration
```

2. Create and activate a virtual environment (optional but recommended)


## 📦 Requirements

```txt
numpy>=1.24.0
matplotlib>=3.7.1
jupyter
```

## 🚀 Usage

1. Open the Jupyter notebook:
```bash
jupyter notebook Policy_and_Value_iteration.ipynb
```

2. Run all cells to see:
- Grid world environment setup
- Value iteration implementation and visualization
- Policy iteration implementation and visualization
- Performance comparisons

## 📊 Results

### Value Iteration
- Converges to optimal policy through iterative value function updates
- Provides both cost matrix and policy visualization
- Higher iteration count but straightforward implementation

### Policy Iteration
- Faster convergence through policy evaluation and improvement steps
- Matrix-based solution for policy evaluation
- Efficient for smaller grid worlds



## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

## ✍️ Author

Abhimanyu Suthar - [@Abhimanyu-0](https://github.com/Abhimanyu-0)


