# POLICY ITERATION ALGORITHM

## AIM:

To develop a Python program to find the optimal policy for the given MDP using the policy iteration algorithm.

## PROBLEM STATEMENT:

The bandit slippery walk problem is a reinforcement learning problem in which an agent must learn to navigate a 7-state environment in order to reach a goal state. The environment is slippery, so the agent has a chance of moving in the opposite direction of the action it takes.

## POLICY ITERATION ALGORITHM:

Policy iteration is a dynamic programming algorithm used to determine the optimal policy in a Markov decision process (MDP). The process unfolds in several key steps:

Initialization: We begin by initializing the policy, denoted as π. Initially, random actions are assigned to each state in the MDP, forming an initial policy.

Iterative Loop: The heart of policy iteration lies in an iterative loop, which continues until the policy no longer changes significantly. This termination condition is achieved by comparing the current policy with the previous one.

Policy Evaluation: Within each iteration, we perform policy evaluation using the function policy_evaluation. This step calculates the state-values (V) for each state under the current policy. These values represent the expected cumulative rewards, accounting for discounting future rewards by a factor of γ.

Policy Improvement: Following policy evaluation, we update the policy using policy_improvement. This step leverages the computed state-values to enhance the policy, aiming to make better decisions.

Convergence Check: After each policy improvement step, we check for convergence by comparing the current policy with the previous one. If there is no significant change across all states, the loop terminates, signifying that the optimal policy has been found.

## POLICY IMPROVEMENT FUNCTION
Include the policy improvement function

## POLICY ITERATION FUNCTION
Include the policy iteration function

## OUTPUT:
Mention the optimal policy, optimal value function , success rate for the optimal policy.

## RESULT:

Write your result here
