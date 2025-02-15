# Learning to Drive with Reinforcement Learning in Unreal Engine 5

## Overview
This project demonstrates how to train an AI agent to drive using **Reinforcement Learning (RL)** in **Unreal Engine 5**. The agent learns to navigate a track by receiving rewards based on its driving performance. The project utilizes the **Learning Agents** framework in Unreal for training and execution.

## Features
- **Reinforcement Learning-driven autonomous driving**
- **Custom training environment** built in Unreal Engine 5
- **Agent observes and reacts to the environment** using Unreal Learning Agents
- **Neural network-based policy** for decision-making
- **Trained using PPO (Proximal Policy Optimization)**

## Requirements
### Software
- Unreal Engine 5 with **Learning Agents** plugin enabled
- (Optional) GPU for faster training

### Dependencies
- Unreal Engine Learning Agents Framework

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/pankajkaushik12/LearnToDriveWithRL.git
   ```
2. Open the project in **Unreal Engine 5**.
3. Ensure the **Learning Agents** plugin is enabled.
4. Set up the training environment in **Blueprints/C++**.
5. Run the simulation and observe the agent's learning process.

## How It Works
1. **Agent Observations**: The agent collects data about its speed, direction, and track position.
2. **Actions**: The agent controls steering, acceleration, and braking.
3. **Rewards**: The agent receives positive rewards for staying on track and negative rewards for going off-road.
4. **Training Loop**: The agent learns by trial and error, optimizing its policy using **PPO (Proximal Policy Optimization)**.

## Training Process
- Training occurs within Unreal Engine using the **LearningAgentsManager** component.
- The agent interacts with the environment, improving its driving skills over multiple episodes.
- Reward shaping ensures the agent prioritizes stable and efficient driving.

## Usage
- **To Train the Agent**: Run the project, set the RunInference variable in **BP_SportsCarManager** to false and let the RL algorithm optimize the policy.
- **To Test the Agent**: Set the RunInference variable in **BP_SportsCarManager** to true and observe the driving behavior.

## Output
[![Watch the video](https://img.youtube.com/vi/3FySgZmYdn8/0.jpg)](https://www.youtube.com/watch?v=3FySgZmYdn8)

## References
- Unreal Engine Learning Agents: [Official Docs](https://dev.epicgames.com/community/learning/courses/GAR/unreal-engine-learning-agents-5-5/7dmy/unreal-engine-learning-to-drive-5-5)

---
Developed using **Unreal Engine 5** and **Reinforcement Learning**.

