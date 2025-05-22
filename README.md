# 🐦 PSO-Based Vehicle Routing Problem (VRP) - Python Implementation

This project implements a **basic version** of the **Vehicle Routing Problem (VRP)** using **Particle Swarm Optimization (PSO)** in Python. It’s designed for beginners who want to understand how metaheuristics like PSO can solve combinatorial optimization problems like routing.

## 📦 Problem Description

Given:
- A single **depot**
- 5 **customers**
- A single **vehicle**

The goal is to find the **shortest possible route** that:
- Starts and ends at the depot
- Visits all customers **exactly once**
- Minimizes the **total travel distance**

This version **does NOT** include vehicle capacity, multiple vehicles, or time windows (but can be extended later).

---

## 🚀 PSO Logic (Simplified)

- Each **particle** represents a possible route (a permutation of customer IDs).
- The swarm explores different routes, updating based on:
  - Its **personal best** route
  - The **global best** route found so far
- A basic **mutation** (swapping two cities) is used instead of full velocity/position logic for simplicity.

---

## 📂 Files

| File | Description |
|------|-------------|
| `pso_vrp_basic.py` | Main Python file with PSO + VRP code |
| `README.md` | Project explanation and setup instructions |

---

## 📸 Example Output

A sample output shows:

- Best distance in each iteration
- Best route found
- Visualization of the final route using `matplotlib`

