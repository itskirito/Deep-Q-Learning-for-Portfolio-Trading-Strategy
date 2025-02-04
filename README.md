# Deep Q-Learning for Portfolio Trading Strategy

This repository presents an innovative approach to portfolio trading using Deep Q-Learning (DQL). The strategy is designed to optimize trading actions by training an intelligent agent within a Markov Decision Process (MDP) framework, making it highly effective for real-world applications.

## Overview

The project introduces a novel trading strategy that leverages deep reinforcement learning to make precise portfolio decisions. By implementing a discrete combinatorial action space, the model identifies the best trading direction at specified trade sizes for each asset, ensuring it can be applied practically in actual trading scenarios.

### Highlights

1. **Action Feasibility Mapping**:
   - A unique mapping function is implemented to convert initially infeasible actions into feasible ones, closely aligning them with the optimal actions originally suggested by the model.

2. **Dimensionality Reduction**:
   - The study effectively addresses the dimensionality challenge by creating models for both the agent and the Q-network, which are crucial for deriving a multi-asset trading strategy within the predefined action space.

3. **Extensive Action Simulation**:
   - The approach includes a method that allows the agent to explore all feasible actions within each state, resulting in a well-rounded and efficient multi-asset trading strategy.

### Backtesting Results

Comprehensive backtesting was performed on two representative portfolios, showcasing the strategy's superiority over traditional benchmark methods. The results highlight the effectiveness and robustness of the proposed approach.


