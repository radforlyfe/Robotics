# Robotics

### 1) Markov Decision Process
The objective of this lab was to explore Markov Decision Processes (MDP) by developing and implementing a model of simple discretized robot behaviour in 2D grid world and using it to accomplish some prescribed tasks (goal state). The goal was to find the optimal policy (set of best actions for each state) that maximizes the expected sum of rewards.

### 2) Path Planning
The objective of this lab was to build autonomy into a simple two-wheeled non-holonomic robot. The robot occupies a space of 90mm X100mm and has two wheels of given radius separated by a given distance. We implemented sampling based planning algorithm such as Rapidly-exploring-Random-Tree (RRT) and RRT* (optimized RRT) to get our robot to a desired state.

### 3) Kalman Filter
The objective of this lab was to estimate the state of a simple two-wheeled non-holonomic robot with realistic hardware using extended kalman filter (EKF). We develop and implement a mathematical model of the robot sensor and actuator behaviour and use it to evaluate a state estimation algorithm.

### 4) Literature Review 
A Literature Review on the Use of Active Learning for Inverse Reinforcement Learning

In this paper, we provide a comprehensive review of the use of active learning for reward estimation in inverse reinforcement learning (IRL). The major incentives for incorporating active learning in IRL are: 1) it provides an elegant approach to select the most informative states to actively query the expert based on the measure of uncertainty in policy estimation; and 2) it minimizes the number of state-action pair samples required from the expert. We will begin by giving a brief introduction on learning from demonstration (LfD) algorithms, IRL, active learning in general and active learning in IRL framework. Next, we will discuss the background information on Markov Decision Processes (MDP), reinforcement learning (RL) framework, followed by IRL framework, and Bayesian IRL. Next, we will provide a brief timeline of all the different learnings associated with IRL and then provide an in-depth review of the literature involved in active learning IRL framework. Lastly, we will discuss where the field of active learning in IRL is lacking and where future improvements in research can be made. The aim of this paper is to provide an overview of the theoretical background and applications of using active learning for reward estimation in IRL.
