# Robotics

### 1) Markov Decision Process
##### Problem Statement:
The objective of this lab was to explore Markov Decision Processes (MDP) by developing and implementing a model of simple discretized robot behaviour in 2D grid world and using it to accomplish some prescribed tasks (goal state). The goal was to find the optimal policy (set of best actions for each state) that maximizes the expected sum of rewards.

##### Tasks:
##### - Set up the MDP System:
The robot lives in 2D grid world of length L and W and can face in any 12 headings and choose from several actions (movement followed by rotation) with a pre-rotation error. Create objects to represent state space and action space and functions that returns the state transition probability, the next state and the reward. Formulate this problem as MDP by assuming that every state is fully observable by the robot and that the Markov property holds for every state.
Goal: Given MDP{S, A, P, R, H, γ } → find the optimal policy π*.
##### - Policy Iteration:
Solve the policy iteration by repeatedly performing two steps: Policy Evaluation and Policy Improvement. 
​Policy Evaluation​: Start with a random initial policy π0 and evaluate this initial policy by identifying the optimal actions with respect to the current value function until convergence.Find the values with simplified Bellman updates and iterate until the values converge:
$V_{i+1)^{\pi_k} = $

### 2) Path Planning
The objective of this lab was to build autonomy into a simple two-wheeled non-holonomic robot. The robot occupies a space of 90mm X100mm and has two wheels of given radius separated by a given distance. We implemented sampling based planning algorithm such as Rapidly exploring Random Tree (RRT) and RRT* (optimized RRT) to get our robot to a desired state.

### 3) Kalman Filter
The objective of this lab was to estimate the state of a simple two-wheeled non-holonomic robot with realistic hardware using extended kalman filter (EKF). We develop and implement a mathematical model of the robot sensor and actuator behaviour and use it to evaluate a state estimation algorithm.
