## Lunar Landing using DQN 🌕
- Episode 100   Average Score: -145.50
- Episode 200   Average Score: -73.69
- Episode 300   Average Score: 49.65
- Episode 400   Average Score: 81.76
- Episode 500   Average Score: 156.57
- Episode 600   Average Score: 167.65
- Episode 700   Average Score: 147.83
- Episode 800   Average Score: 129.80
- Episode 900   Average Score: 179.25
- Episode 1000  Average Score: 181.83
- Episode 1043  Average Score: 202.27
Environment solved in 943 episodes!  Average Score: 202.27

[Link to Lunar Landing](https://github.com/CNS-PRADHYUMNA/AI_ML/assets/152390152/c937f304-ba58-4de5-9ed7-e12b5c0a98fb)

## Pac-man using DCQN 🍒
- Episode 100   Average Score: 284.70
- Episode 200   Average Score: 435.30
- Episode 280   Average Score: 502.30
Environment solved in 180 episodes!  Average Score: 502.30

[Link to Pac-man](https://github.com/CNS-PRADHYUMNA/AI_ML/assets/152390152/42549f2a-c1e5-4cb9-ac48-bb9736c5d827)

**DQN (Deep Q-Network)** 🧠
- **Definition**: DQN is a reinforcement learning algorithm that uses a neural network to approximate the Q-function, which represents the expected future rewards for each action in a given state.
- **Formula**: 
  - The Q-function is updated using the Bellman equation:
  
  - The neural network is trained to minimize the difference between the predicted Q-values and the target Q-values.

**DCQN (Dueling Convolutional Q-Network)** 🎮
- **Definition**: DCQN is an extension of DQN that separates the estimation of the state value and action advantages, allowing the network to learn the value of being in a particular state without having to learn the effect of each action in that state separately.
- **Formula**: 
  - The DCQN architecture consists of two streams: one for estimating the state value (\( V(s) \)) and another for estimating the advantage of each action (\( A(s,a) \)). 
  - These streams are combined to produce the final Q-values:
    

**A3C (Asynchronous Advantage Actor-Critic)** 🏆
- **Definition**: A3C is a distributed reinforcement learning algorithm that uses multiple actor-learner agents to asynchronously explore different parts of the environment and learn from their experiences. It combines the advantages of both actor-critic methods and asynchronous training to achieve faster convergence and better performance.
- **Formula**: 
  - A3C uses an actor-critic architecture, where the actor learns to select actions based on policy gradients 
  - 
