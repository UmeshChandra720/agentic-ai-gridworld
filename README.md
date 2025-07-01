# agentic-ai-gridworld
This project demonstrates a simple agent-based AI system that learns to navigate a 5x5 grid environment using Reinforcement Learning (Q-Learning).

# Agentic AI: Q-Learning Based Grid World Navigator

## Problem Statement

Design and develop a simple **agentic AI system** that can **navigate a grid** to reach a goal while **learning from the environment**.  
The agent should make decisions based on rewards and penalties, simulating autonomy by learning from experience using **Reinforcement Learning** (Q-Learning).

---

## Approach

1. **Environment Design**:
   - A custom **5x5 grid world** was created using NumPy and visualized with Seaborn.
   - The grid includes:
     - Empty spaces (`0`)  
     - Obstacles (`-1`)  
     - A goal (`10`)

2. **Learning Algorithm**:
   - Implemented **Q-Learning**, a model-free reinforcement learning algorithm.
   - The agent learns **action-value pairs** to decide the best path.

3. **Reward System**:
   - Goal: `+10`
   - Obstacle: `-1`
   - Out-of-bound or wall hit: `-5`
   - Empty cell: `0`

4. **Agent Behavior**:
   - The agent starts from a random position and uses exploration/exploitation to learn.
   - Over multiple episodes, it learns to find the **shortest and safest path** to the goal.

---

## Technology Stack

- **Language**: Python 3
- **Libraries**:  
  - `numpy`  
  - `pandas`  
  - `matplotlib`  
  - `seaborn`

- **Platform**: Google Colab (recommended for running)

---

## How to Run the Code

1. Open the notebook in Google Colab or Jupyter.
2. Run each cell step-by-step:
   - Environment Setup
   - Grid Visualization
   - Q-Learning Logic
   - Simulation of Agent Movement
3. Final heatmap will show the **agent’s path** to the goal.
4. Modify the grid or episodes to test different strategies.

---

## Demo Output

- **Grid Heatmap**: Shows where goal and obstacles are placed.
- **Agent Path Heatmap**: Shows how the trained agent navigates through the grid.

---

## Deliverables

- Clean, well-commented code
- Trained Q-learning model
- Heatmap-based visual demo
- This README file

---

## Learning Outcomes

- Learned how to build a **grid world simulation**.
- Understood and implemented **Q-learning**.
- Developed an **AI agent** capable of autonomous decision-making.

