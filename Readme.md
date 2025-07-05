# Frozen Lake Solver Agent ❄️🧠

This project involves coding an agent to solve the **Frozen Lake** problem using the **OpenAI Gymnasium** environment.

## Overview

We use **Q-learning** with a **Q-table** and an **epsilon-greedy policy** to train the agent to navigate a frozen lake without falling into holes. The agent learns through trial and error to reach the goal safely.

## Key Features

- ✅ Q-Learning algorithm implementation
- 🧠 Q-table for storing and updating state-action values
- 🎲 Epsilon-greedy policy for balancing exploration and exploitation
- 🧪 Supports different map sizes and environment configurations

## Requirements

- Python 3.7+
- `gymnasium`
- `numpy`

Install dependencies with:

```bash
pip install gymnasium numpy matplotlib
````

## Running the Code

You can run all the cells in notebooks one by one. 

## Environment Info

* Environment: `FrozenLake-v1` from Gymnasium
* States: Grid positions
* Actions: \[Left, Down, Right, Up]
* Goal: Reach the goal tile without falling into holes

## License

This project is licensed under the MIT License.
