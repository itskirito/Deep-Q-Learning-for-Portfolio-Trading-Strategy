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


<br />

## 🪪 License
This project follows the [MIT LICENSE](https://choosealicense.com/licenses/mit/).

<br />

<div align="center">
<h3> Connect with me<a href="https://gifyu.com/image/Zy2f"><img src="https://github.com/milaan9/milaan9/blob/main/Handshake.gif" width="50px"></a>
</h3> 
<p align="center">
    <a href="https://github.com/Syd-B" target="_blank" rel="noreferrer"><img alt="Github" width="37px" src="https://github.githubassets.com/assets/GitHub-Mark-ea2971cee799.png"></a> &nbsp&nbsp&nbsp
    <a href="https://www.linkedin.com/in/siddharth-butoliya-703760207/" target="_blank"><img alt="LinkedIn" width="35px" src="https://i.pinimg.com/736x/96/8e/a6/968ea62882943e88bbd318ae5fa67429.jpg"></a> &nbsp&nbsp&nbsp

<p align="right">(<a href="#top">Back to top</a>)</p>
</p> 
