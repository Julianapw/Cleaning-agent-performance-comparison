# Intelligent Vacuum Cleaner Agents Performance Comparison (5x5 Grid Environment)

## Technologies Used

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat-square&logo=python)
![Random](https://img.shields.io/badge/Python-Random%20Library-lightgrey?style=flat-square&logo=python)
![Time](https://img.shields.io/badge/Python-Time%20Library-lightgrey?style=flat-square&logo=python)
![Math](https://img.shields.io/badge/Python-Math%20Library-lightgrey?style=flat-square&logo=python)

## Overview
This repository presents an **Artificial Intelligence experiment** comparing the performance of two **vacuum cleaner agents** operating in a **5 × 5 grid environment** with randomly distributed dirty and clean rooms.

Both agents start from the **center position of the environment** and follow different navigation strategies. The goal is to evaluate their efficiency in cleaning the environment using a **performance metric based on movement cost and number of cleaned rooms**.

The project demonstrates concepts related to **reactive agents, environment perception, heuristic decision-making, and performance evaluation in autonomous systems**.

---

## Objectives & Requirements

- Expand the vacuum cleaner environment from **3 × 3 to 5 × 5 grid**
- Maintain **random distribution of dirty and clean rooms**
- Initialize both agents at the **central position (row 3, column 3)**
- Implement **two different agent strategies**
- Restrict movement to **four orthogonal directions**
- Measure performance using an **efficiency metric based on cleaning time**

---
## Key Features

### Expanded Environment Simulation
Implementation of a **5 × 5 dynamic grid environment** with randomized dirt distribution.

### Dual-Agent Strategy Comparison
Comparison between:

- Sequential navigation agent
- Distance-based reactive agent

### Euclidean Distance-Based Decision Making
Agent B dynamically selects the **closest dirty room** using spatial reasoning.

### Performance Metric Evaluation
Efficiency calculated using a **movement-based performance indicator**.

### Autonomous Cleaning Completion Detection
Simulation ends automatically when **all rooms are clean**.

---


