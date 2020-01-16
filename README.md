# PaperList-Combi-RL

| Paper Title                                     | Conference             | Method            |Problem    |
| :-----------------------------------------------|------------ | ------------------------ |-------------------|
| Learning to Perform Local Rewriting for Combinatorial Optimization| NIPS19 | Learn a policy to pick heuristics and rewrite the local components of the current solution to iteratively improve it until convergence. [ Actor-critic methods ] | expression simplification, online job scheduling, VRP | 
| Approximation Ratios of Graph Neural Networks for Combinatorial Problems | NIPS19 | Establish a new class of GNNs that can solve a strictly wider variety of problems than existing GNNs. [Distributed local algorithms] | dominating set, vertex cover, adding coloring or weak coloring |
| Reinforcement Learning for Solving the Vehicle Routing Problem | NIPS18 | Learn a policy to find near-optimal solutions by observing the reward signals and following feasibility rules. [ Stochastic policy gradient ] | VRP |
| Attention, Learn to Solve Routing Problems! | ICLR19 | Propose a model based on attention layers and show how to train this model using REINFORCE with a simple baseline based on a deterministic greedy rollout. [ REINFORCE ] | TSP, VRP, OP(Orienteering Problem), Prize Collecing TSP|
| Exact Combinatorial Optimization with Graph Convolutional Neural Networks | NIPS19 | Propose a GCN model for learning branch-and-bound variable selection prolicies with the varibale constraint biparitite graph representation of mixed-interger linear programs. [ Imitation learning(strong branching expert rule) ] | MILP 
| Deep Symbolic Superoptimization Without Human Knowledge | ICLR20 |
| Differentiation of Blackbox Combinatorial Solvers | ICLR20 | Implement an efficient backward pass through blackbox implementations of combinatorial solvers with linear objective functions | TSP,  min-cost perfect matching problem, shortest path problem |
| Targeted sampling of enlarged neighborhood via Monte Carlo tree search for TSP |  | Use 2-opt local search to search within a small neighborhood. Use a Monte Carlo tree search to sample a number of targeted actions within an enlarged neighborhood. | TSP |
