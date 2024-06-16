Explanation:
Environment Class: WarehouseEnv simulates the warehouse with reset and step functions to interact with the agent.
Q-Table Initialization: The Q-table is initialized to zeros.
Training Loop: The agent learns by interacting with the environment, updating the Q-values using the Q-learning algorithm.
Evaluation: The agent's performance is evaluated over 100 episodes to check the average reward.
This implementation demonstrates a basic Q-Learning model for optimizing warehouse flows. For a real-world application, additional complexities like dynamic obstacles, varied task priorities, and more sophisticated reward structures can be incorporated.
