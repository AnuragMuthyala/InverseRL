# Inverse RL Algorithms

## Objective
We implement the inverse RL algorithms to derive the state values given the policy followed by the agent

## Finite State Value approximation
Given the policy for the discrete space, we will try to determine the rewards for each state which can be used to train another agent on a similar environment. The environment chosen is the _Cliff Walking_ Environment with certain noise added in terms of downward wind.

## Linear State Value Approximation
Given the policy for the continuous space, we will try to determine the rewards for each state which can be used to train another agent on a similar environment. The environment chosen is the _Mountain Car_ Environment.

## Reference
We have implemented the algorithms following the ideas from this paper: https://ai.stanford.edu/~ang/papers/icml00-irl.pdf
