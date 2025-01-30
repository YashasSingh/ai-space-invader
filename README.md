# ai-space-invader
# Reinforcement Learning with OpenAI Gym and TensorFlow

## Overview
This project demonstrates reinforcement learning using OpenAI Gym and TensorFlow. The environment used is `SpaceInvaders-v0`, where an agent interacts with the game by taking random actions. The project also includes a deep learning model built with Keras to improve the agent's decision-making process.

## Installation
Ensure you have the necessary dependencies installed before running the project. You can install them using:
```sh
pip install tensorflow==2.3.1 gym keras-rl2 gym[atari]
```

### Verified Dependencies
- TensorFlow 2.3.1
- Gym 0.18.0
- Keras-RL2 1.0.4
- NumPy
- TensorFlow Estimator
- Keras Preprocessing

## Running the Project
### Step 1: Initialize OpenAI Gym Environment
- The environment `SpaceInvaders-v0` is created.
- The available actions in the game are displayed.
- The game runs for multiple episodes, taking random actions and displaying the resulting scores.

### Step 2: Build a Deep Learning Model with Keras
- A neural network model is created using Keras.
- The model will be used for reinforcement learning to improve the agent's performance over time.

## Example Output
```sh
Available Actions: ['NOOP', 'FIRE', 'RIGHT', 'LEFT', 'RIGHTFIRE', 'LEFTFIRE']
Episode 1: Score = 410.0
Episode 2: Score = 235.0
Episode 3: Score = 155.0
Episode 4: Score = 240.0
Episode 5: Score = 120.0
```

## Notes
- The `env.render()` function is used to visualize the game during execution.
- The random agent is a starting point; a deep reinforcement learning model will be implemented next.

## Closing the Environment
To avoid resource leaks, the environment is closed using `env.close()` after execution.

## Future Improvements
- Implement Deep Q-Learning (DQN) for better decision-making.
- Train the agent using Keras-RL2 to achieve higher scores.
- Optimize hyperparameters to improve training efficiency.

## License
This project is open-source and available for further modifications and enhancements.

