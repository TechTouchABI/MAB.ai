## MAB.ai
# Multi-Armed Bandit AI

<p align="center">
  <img width="460" height="300" src="https://github.com/TechTouchABI/MAB.ai/blob/master/MAB_ALGO.PNG">
</p>

Reinforcement learning is learning what to do - how to map situations to actions - so as to maximize a numerical reward signal.
The learner is not told which actions to take, as in most forms of machine learning, but instead must discover which actions
yield the most reward by trying them. In the most interesting and challenging cases, actions may affect not only
the immediate reward, but also the next situation and, through that, all subsequent rewards. 

#The multi-armed bandit problem

Maximize the reward obtained by successively playing gamble machines (the ‘arms’ of the bandits)
Invented in early 1950s by Robbins to model decision making under uncertainty when the environment is unknown
The lotteries are unknown ahead of time

# Assumptions

Each machine 𝑖 has a different (unknown) distribution law for rewards with (unknown) expectation 𝜇𝑖:
    Successive plays of the same machine yeald rewards that are independent and identically distributed
    Independence also holds for rewards across machines
     Reward = random variable 𝑋𝑖,𝑛 ; 1 ≤ 𝑖 ≤ 𝐾, 𝑛 ≥ 1
     𝑖 = index of the gambling machine
     𝑛 = number of plays
     𝜇𝑖 = expected reward of machine 𝑖.
A policy, or allocation strategy, 𝐴 is an algorithm that chooses the next
machine to play based on the sequence of past plays and obtained
rewards.

# Many applications have been studied:
Clinical trials
Adaptive routing in networks
Advertising: what ad to put on a web-page?
Economy: auctions
Computation of Nash equilibria

This project was inspired by Unity Technologies project: https://github.com/Unity-Technologies/BanditDungeon



