# Module 09: Reinforcement Learning – Q-Learning in the Nim Game

### Assignment Summary
This assignment introduced **reinforcement learning (RL)** through a practical implementation of the **Nim game**, focusing on Q-learning. Students were asked to understand the RL environment setup, evaluate agents, compute state/action spaces, and enhance the Q-learner's performance against strategic opponents.

### Tasks Covered
- Described the **environment** of the Nim game, including the board state and game rules.
- Identified the various **agents**, including the learning agent and opponents like the Guru and Random players.
- Explained the **reward and penalty** system in the Q-learning model.
- Computed the number of **possible game states** with 3 piles and a maximum of 10 items per pile.
- Calculated the number of **unique actions** available to Player 1 at the start of the game.
- Evaluated whether a standard Q-learner could outperform the Guru player, based on game dynamics and learning principles.
- Developed an **improved Q-learning agent** by:
  - Modifying the update rule (e.g., explicitly penalizing losses)
  - Adjusting the exploration/exploitation balance
- Trained the improved agent against Random and Guru players.
- Compared win rates to demonstrate learning performance improvements over time.

### Highlights
- The enhanced Q-learner showed **superior performance** after training, with improved win rates against both Random and Guru agents.
- Reinforced the value of **experience-based learning**, showing that Q-learning can match or even outperform a hard-coded expert under the right training conditions.
- Demonstrated the critical role of **reward shaping** in reinforcement learning model effectiveness.

### File
- `Shewale-Assign9.ipynb`: Includes environment setup, state/action computation, standard and improved Q-learning agents, training loops, and performance evaluation against multiple opponents.
