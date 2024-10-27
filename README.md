# CS-370-Treasure-Hunt-Game

## Overview
This project is part of the CS 370 course, where I applied reinforcement learning and neural networks to develop a pathfinding solution for a treasure hunt game. The primary objective was to create an intelligent agent (pirate) that could navigate a maze-like environment to locate a treasure. Using deep Q-learning, the agent learns to make decisions to reach the target while avoiding obstacles.

## Project Details

### Code Provided
The project included some pre-written code that I used as a foundation:
1. **Environment Setup** (`TreasureMaze.py`): This file defines the 8x8 grid representing the maze environment. It includes methods for resetting the environment, retrieving the current state, executing actions, and calculating rewards.
2. **Experience Replay** (`GameExperience.py`): This code provided a mechanism for storing episodes (sequences of states, actions, and rewards). Experience replay allows the agent to learn from past actions and improve stability during training.
3. **Model Structure**: A neural network architecture template was included in the notebook, using Keras to define and compile the model structure for the Q-learning agent.

### Code Created
I developed the deep Q-learning algorithm within the Jupyter Notebook (`TreasureHuntGame.ipynb`). Specifically, my contributions include:
- **Q-Training Algorithm**: I implemented the main training loop where the agent learns through experience, using Q-learning principles to optimize decision-making. This involved:
  - **Balancing Exploration and Exploitation**: Ensuring the agent explores new paths while also exploiting known ones to reinforce successful actions.
  - **Experience Replay**: Using stored episodes to train the neural network and enhance learning by iteratively adjusting the weights based on past experiences.
  - **Training Loop**: Fine-tuning the number of epochs and other hyperparameters to improve the agent's performance and achieve high win rates.

## Reflection on Learning and Relevance to Computer Science

### What Do Computer Scientists Do and Why Does It Matter?
Computer scientists are problem-solvers who apply computational techniques to solve complex issues across a variety of domains. In this project, I gained hands-on experience with AI-driven decision-making, which has applications in robotics, autonomous vehicles, and other fields requiring intelligent navigation. This project illustrated how reinforcement learning can be used to tackle real-world challenges in a controlled environment, showcasing the impact of computer science on society.

### Approaching Problems as a Computer Scientist
My approach to solving this problem involved breaking it down into smaller, manageable components. I started by understanding the environment, then focused on implementing and tuning the Q-learning algorithm. This iterative process—testing, analyzing, and refining—helped me develop a strategic mindset, which is essential for computer scientists when tackling complex issues. Each phase was a stepping stone towards developing an effective solution, highlighting the importance of structured problem-solving.

### Ethical Responsibilities to the End User and Organization
This project highlighted ethical considerations related to AI. In a real-world application, it is crucial to ensure that AI-driven systems make fair and unbiased decisions, particularly in high-stakes environments like healthcare or finance. Transparency in AI decision-making and data privacy are essential, as is the responsibility to create models that do not perpetuate harmful biases. As a computer scientist, my role includes ensuring that technology serves the broader good while respecting users' rights and organizational goals.

## Repository Contents
- **`TreasureHuntGame.ipynb`**: Jupyter Notebook containing the complete Q-learning implementation for the pirate intelligent agent.
- **`Project 2 Design Defense - Joseph Dengler.docx`**: A design defense document that outlines the technical aspects and reasoning behind the agent's design.
- **`README.md`**: This file, documenting the project overview, reflection on learning, and ethical considerations.

## Conclusion
This project provided me with valuable insights into reinforcement learning and neural networks, reinforcing key concepts from the CS 370 course. By developing an intelligent agent capable of navigating a complex environment, I gained practical experience with machine learning and its potential applications. The experience also emphasized the importance of ethical responsibility in AI, preparing me for future challenges in the field of computer science.
