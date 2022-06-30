# Reinforcement Learning (Reward-seeking robots!)
 This repository has 3 different problem sets where the aim is to make an agent learn the optimal policy (set of rules for deciding what to do for any situation it encounters) for a certain Markov Decision Process. Especifically, the MDP to study is a simple controlled queueing system where the goal is to control the number of requests waiting in a queue. 

 1. In the first notebook, we use standard dynamic programming methods (Value and Policy Iteration) for solving Markov decision processes with known transition and reward.

 2. In the second problem set, the agent is oblivious of the exact transition matrix and we generate many experiences so it can infer it. We use different linear function approximations and a greedy approach for determining which action to take.

 3. In this case, during the policy iteration step, to determine which action should be saved as policy for a given state we employ a soft-max function which adds stochasticity to the process.

