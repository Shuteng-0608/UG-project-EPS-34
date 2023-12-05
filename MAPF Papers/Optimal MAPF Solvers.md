# Optimal MAPF Solvers
- **Extensions of A-Star.** These are algorithms that search the k-agent search space using a variant of the A* algorithm.
- **The Increasing Cost Tree Search.** This algorithm splits the MAPF problem into two problems: ﬁnding the cost added by each agent, and ﬁnding a valid solution with these costs.
- **Conflict-Based Search.** This algorithmic family solves MAPF by solving multiple single-agent pathﬁnding problems. To achieve coordination, speciﬁc constraints are added incrementally to the single-agent pathﬁnding problems, in a way that veriﬁes soundness, completeness, and optimality.
- **Constraints programming.** This approach compiles MAPF to a set of constraints and solves them with a general purpose constraints solver.
## Extensions of A*
A straightforward multirobot path planner could use standard A* to find a path for a multirobot system, resulting in a simple, coupled planner. However, the exponential growth in the number of possible joint actions would render such an approach computationally infeasible as the number of robots increases.
1. [Optimal Multi-robot Path Finding Algorithm Based on A*](https://link.springer.com/chapter/10.1007/978-3-030-00184-1_16)
2. [Finding Optimal Solutions to Cooperative Pathfinding Problems](https://ojs.aaai.org/index.php/AAAI/article/view/7564) : Operator Decomposition(OD) and Simple Independence Detectio(SID)
3. [Complete Algorithms for Cooperative Pathfinding Problems](https://www.ijcai.org/Proceedings/11/Papers/118.pdf) : Full Independence Detection(OD+ID)
4. [Independence Detection for Multi-Agent Pathfinding Problems](http://trevorstandley.com/papers/ID_for_MAPP.pdf) : Introduction to Independence Detection and aims to clarify its details.
5. [M*: a complete multirobot path planning algorithm with performance bounds](https://ieeexplore.ieee.org/abstract/document/6095022) : M* and Recursive M* (rM*)
6. [ODrM*: optimal multirobot path planning in low dimensional search spaces](https://ieeexplore.ieee.org/abstract/document/6631119) : ODrM* which replace A* with operator decomposition as the underlying planning algorithm in M*
7. [Subdimensional expansion for multirobot path planning](https://www.sciencedirect.com/science/article/pii/S0004370214001271) : Introduce a new approach that combines the advantages of coupled and decoupled algorithms called **Subdimensional Expansion.** 
## The Increasing Cost Tree Search
1. [The Increasing Cost Tree Search for Optimal Multi-Agent Pathfinding](https://www.ijcai.org/Proceedings/11/Papers/117.pdf): ICTs
## Conflict-Based Search
1. [Conflict-based search for optimal multi-agent pathfinding](https://www.sciencedirect.com/science/article/pii/S0004370214001386) : CBS and Meta-Agent CBS (MA-CBS), MA-CBS allows agents to be merged into small groups of joint agents
## Others
1. [Optimal Multirobot Path Planning on Graphs: Complete Algorithms and Effective Heuristics](https://ieeexplore.ieee.org/abstract/document/7539623/footnotes#full-text-header)
2. [Dragonfly algorithm: a new meta-heuristic optimization technique for solving single-objective, discrete, and multi-objective problems](https://link.springer.com/article/10.1007/s00521-015-1920-1) : DA
3. [An Improved Real-Time Path Planning Method Based on Dragonfly Algorithm for Heterogeneous Multi-Robot System](https://ieeexplore.ieee.org/document/9152817)
