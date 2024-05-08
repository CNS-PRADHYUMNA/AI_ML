# Lunar Landing using DQN 🌕

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

# Pac-man using DCQN 🍒

- Episode 100   Average Score: 284.70
- Episode 200   Average Score: 435.30
- Episode 280   Average Score: 502.30

Environment solved in 180 episodes!  Average Score: 502.30

[Link to Pac-man](https://github.com/CNS-PRADHYUMNA/AI_ML/assets/152390152/42549f2a-c1e5-4cb9-ac48-bb9736c5d827)

# Kung-Fu using A3C + LSTM ☯️:

- Average agent reward:
  - 6/3001 [00:35<3:36:11,  4.33s/it] : 500.0
  - 1008/3001 [01:29<44:25,  1.34s/it] : 920.0
  - 2007/3001 [02:22<22:35,  1.36s/it]: 1000.0
  - 3001/3001 [03:11<00:00, 15.66it/s]: 700.0

[Link to Kung-Fu](https://github.com/CNS-PRADHYUMNA/AI_ML/assets/152390152/f901158e-e2b8-4dee-9479-167d2872d6da)

## DQN (Deep Q-Network) 🧠

- **Definition**: DQN is a reinforcement learning algorithm that uses a neural network to approximate the Q-function, which represents the expected future rewards for each action in a given state.

- **Formula**: 
  - The Q-function is updated using the Bellman equation:
  
    ![1_nm0lt3oobxdBHTMACUZ-cg](https://github.com/CNS-PRADHYUMNA/AI_ML/assets/152390152/6a94f0b1-ba04-42f1-ac6c-00f55683980c)

    ![1_99Su482PJlvtkji_4n0A_Q](https://github.com/CNS-PRADHYUMNA/AI_ML/assets/152390152/89a51ddf-1c4a-4ba6-8d0c-77a4a1c24587)

## DCQN (Deep Convolutional Q-Network) 🎮

- **Definition**: Deep Convolutional Q-Network (DQN) is an extension of the original DQN algorithm that specifically leverages convolutional neural networks (CNNs) as function approximators. It's commonly used in reinforcement learning settings, particularly in scenarios where the input data is visual, such as playing Atari games from raw pixel inputs.

- **Components**: 
  - **Convolutional Layers**: Extract hierarchical features from raw pixel inputs.
  - **Fully Connected Layers**: Process extracted features to produce Q-values.
  - **Experience Replay, Target Network, and ε-Greedy Policy**: Stabilize and accelerate training.
  
  ![Tnkq3Tf](https://github.com/CNS-PRADHYUMNA/AI_ML/assets/152390152/0a80a0b4-ab02-4525-887d-a9163c567fac)

## A3C (Asynchronous Advantage Actor-Critic) 🏆

- **Definition**: A3C is a distributed reinforcement learning algorithm that uses multiple actor-learner agents to asynchronously explore different parts of the environment and learn from their experiences. It combines the advantages of both actor-critic methods and asynchronous training to achieve faster convergence and better performance.

- **Formula**: 
  - A3C uses an actor-critic architecture, where the actor learns to select actions based on policy gradients.

    ![1_P6Zk8WQxfiBQVsgWKVH9hQ](https://github.com/CNS-PRADHYUMNA/AI_ML/assets/152390152/c3029414-d2c8-46ef-bf78-5d5ec1c72e90)

    ![download](https://github.com/CNS-PRADHYUMNA/AI_ML/assets/152390152/d1a68e6a-403d-4958-a90d-ffe510199aee)
