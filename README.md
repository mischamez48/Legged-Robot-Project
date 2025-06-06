# Legged Robot Project

This repository contains implementations of locomotion algorithms for legged robots, developed as part of a Master's Robotics course at EPFL.

## Overview

The project consists of two main components:

### Project 1: DCM Bipedal Locomotion
- Implementation of Divergent Component of Motion (DCM) based bipedal walking
- PyBullet simulation environment
- Quadratic programming for trajectory optimization
- Jupyter notebook with interactive demonstrations

### Project 2: Quadruped Locomotion
Two approaches for quadruped robot control:
- **CPG (Central Pattern Generator)**: Bio-inspired rhythmic pattern generation for locomotion
- **DRL (Deep Reinforcement Learning)**: Learning-based approach using Stable-Baselines3

## Features

- 🤖 Bipedal and quadruped robot simulations
- 🎯 Model Predictive Control with DCM planning
- 🧠 Reinforcement learning for locomotion policies
- 📊 Trajectory optimization and footstep planning
- 🔄 Central Pattern Generator implementations

## Getting Started

Each project has its own setup instructions and dependencies:
- See [`Project1/README.md`](Project1/README.md) for bipedal locomotion setup
- See [`Project2/Project2_DRL/README.md`](Project2/Project2_DRL/README.md) for quadruped DRL setup
- See [`Project2/Project2_CPG/README.md`](Project2/Project2_CPG/README.md) for quadruped CPG setup

## Requirements

- Python 3.6+
- PyBullet for physics simulation
- NumPy, Matplotlib for numerical computing and visualization
- Stable-Baselines3 for reinforcement learning (Project 2)
- QP solvers for optimization (Project 1)

## Structure

```
├── Project1/           # DCM bipedal locomotion
├── Project2/
│   ├── Project2_CPG/   # Central Pattern Generator approach
│   └── Project2_DRL/   # Deep Reinforcement Learning approach
└── README.md
```

---
*Legged Robotics - Master's in Robotics, EPFL* 