# Reinforcement Learning Projects

This repository contains a comprehensive collection of Reinforcement Learning (RL) implementations. Each project reflects a focused exploration of a specific RL concept, algorithm, or experimental setup. The goal of this repository is to build a strong, practical understanding of RL fundamentals, policy optimization, reward-driven behavior, and sequential decision-making in both deterministic and stochastic environments.

The implementations follow clear structures, include documented experiments, and often reproduce canonical examples from RL literature.

---

## Repository Structure

The repository includes the following project directories:

```
tic-tac-toe/
ten-armed-testbed/
gridworld-mdp/
gridworld-dp/
gambler-problem/
blackjack/
infinite-variance/
random-walk/
windy-gridworld/
cliff-walking/
maximization-bias/
random-walk-ntd/
mazes/
updates-comparison/
trajectory-sampling/
coarse-coding/
random-walk-fa/
mountain-car/
access-control/
counter-examples/
mountain-car-et/
random-walk-et/
```

Each project typically includes:

- A description of the environment
- Algorithms used and their implementation details
- Experimental configuration
- Results, plots, and analysis
- Optional Jupyter notebooks for interactive experimentation

---

## Project Descriptions

### tic-tac-toe
An implementation of self-play reinforcement learning for tic-tac-toe.  
Key focus areas include value function estimation, policy improvement through self-play, and exploration strategies.

### ten-armed-testbed
Reproduces the classic 10-armed bandit problem.  
Includes methods such as epsilon-greedy, optimistic initialization, and UCB to analyze action-value estimation in stationary and nonstationary settings.

### gridworld-mdp
Markov Decision Process formulation of the Gridworld problem.  
Focuses on evaluating policies via dynamic programming and analyzing state transitions in a controlled, tabular environment.

### gridworld-dp
Dynamic Programming solutions (Policy Iteration and Value Iteration) for the Gridworld environment.  
Demonstrates convergence behavior and optimal policy structure.

### gambler-problem
Implements the Gambler’s Problem from Sutton & Barto.  
Emphasizes value iteration and policy optimization in scenarios with absorbing states.

### blackjack
Monte Carlo prediction and control techniques applied to the Blackjack environment.  
Explores episodic learning, exploring starts, and policy evaluation.

### infinite-variance
Exploration of Monte Carlo estimators that exhibit infinite or extremely high variance.  
Used to demonstrate the importance of variance reduction techniques.

### random-walk
Implements the classic Random Walk example to study temporal-difference learning, prediction, and bootstrapping versus Monte Carlo estimation.

### windy-gridworld
An implementation of an environment with wind-induced transitions.  
Used to compare SARSA, Q-Learning, and planning-based methods.

### cliff-walking
Compares on-policy and off-policy TD methods in an environment with highly punitive states.  
Demonstrates the instability of certain strategies under off-policy learning.

### maximization-bias
Illustrates the effects of maximization bias in Q-Learning and how methods like Double Q-Learning reduce estimation bias.

### random-walk-ntd
Implements n-step TD methods for the Random Walk environment.  
Useful for analyzing trade-offs between bootstrapping and full-episode targets.

### mazes
A collection of maze environments solved using search-based and RL strategies.  
Explores reward shaping and sparse-reward learning challenges.

### updates-comparison
Side-by-side comparison of Monte Carlo, TD(0), n-step TD, and other update rules under controlled conditions.

### trajectory-sampling
Examines the role of trajectory sampling in reinforcement learning, including importance sampling and off-policy evaluation techniques.

### coarse-coding
Implements coarse coding for function approximation.  
Covers feature design, generalization behavior, and value estimation in continuous spaces.

### random-walk-fa
Function approximation version of the Random Walk problem.  
Used to highlight instability and divergence issues in linear function approximation.

### mountain-car
The classic Mountain Car control problem.  
Includes TD control, SARSA, Q-Learning, and function approximation solutions.

### access-control
Implements the Access Control Queuing Task.  
Focuses on average-reward RL formulations and their optimization.

### counter-examples
Collection of counterexamples showing where certain algorithms diverge, fail to converge, or behave unexpectedly.

### mountain-car-et
Mountain Car with eligibility traces.  
Analyzes the effect of lambda on learning speed and performance.

### random-walk-et
Random Walk environment augmented with eligibility traces for TD(lambda) experiments.

---

## Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/EmiliaNahapetyan/Reinforcement_Learning.git
cd Reinforcement_Learning
```

### 2. Create and activate a virtual environment
```bash
python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate
```

### 3. Open the associated notebook (if available)
```bash
jupyter notebook
```

---

## Algorithms and Techniques Covered

Across the projects, the following RL methods are implemented and compared:

- Monte Carlo prediction and control
- Temporal-Difference learning (TD(0), TD(n), TD(lambda))
- SARSA and Q-Learning
- Double Q-Learning
- Off-policy methods with importance sampling
- Dynamic Programming (Value Iteration, Policy Iteration)
- Function approximation (linear, coarse coding)
- Eligibility traces
- Exploration strategies including epsilon-greedy and UCB

---

## Dependencies

Most projects rely on:

- Python 3.8+
- NumPy
- Matplotlib
- Jupyter Notebook or JupyterLab

Additional dependencies are listed per project.

---

## Reference Material

This repository is heavily inspired by:

Reinforcement Learning: An Introduction  
Richard S. Sutton and Andrew G. Barto  
Second Edition, MIT Press, 2018

Link: https://www.andrew.cmu.edu/course/10-703/textbook/BartoSutton.pdf


