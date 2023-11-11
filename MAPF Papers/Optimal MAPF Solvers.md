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
5. [Subdimensional expansion for multirobot path planning](https://www.sciencedirect.com/science/article/pii/S0004370214001271) : Introduce a new approach that combines the advantages of coupled and decoupled algorithms called subdimensional expansion. 
