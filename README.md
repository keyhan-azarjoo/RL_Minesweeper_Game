# Reinforcement Learning For Minesweeper Game

Title: Q-Learning Implementation for Minesweeper: Exploring Training Strategies and Adaptability to Varying Game Boards

Description:
This project focuses on the implementation of Q-learning, a reinforcement learning technique, for the game of Minesweeper. The objective was to assess the performance of Q-learning in two distinct scenarios.

In the first scenario (stage), the game board was fixed with predetermined mine placements, and the model was trained for 10,000 iterations. During the training, the number of wins and losses were tracked, revealing an impressive outcome. The agent successfully won the game in approximately 95% of the training instances. However, a significant limitation was discovered when changing the game board configuration, as the agent was unable to achieve victory. This highlighted a critical challenge to overcome.

To address the adaptability issue, the second model (stage), introduced a dynamic approach by randomly placing the mines on the game board for each iteration. Two different parameter settings were employed. The first approach involved the agent acting based on the Q-table, while the second approach involved the agent acting randomly. The primary focus was to prioritize Q-table exploration.

The results of the second model demonstrated that by increasing exploration, a significant improvement was observed, with the agent achieving approximately 50% wins in most situations. This emphasized the importance of exploring and filling the Q-table to enhance the agent's performance and adaptability to varying game board configurations.
