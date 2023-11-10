# Optimal MAPF Solvers
- **Extensions of A-Star.** These are algorithms that search the k-agent search space using a variant of the A* algorithm.
- **The Increasing Cost Tree Search.** This algorithm splits the MAPF problem into two problems: ﬁnding the cost added by each agent, and ﬁnding a valid solution with these costs.
- **Conflict-Based Search.** This algorithmic family solves MAPF by solving multiple single-agent pathﬁnding problems. To achieve coordination, speciﬁc constraints are added incrementally to the single-agent pathﬁnding problems, in a way that veriﬁes soundness, completeness, and optimality.
- **Constraints programming.** This approach compiles MAPF to a set of constraints and solves them with a general purpose constraints solver.
## Extensions of A*
1. [Optimal Multi-robot Path Finding Algorithm Based on A*](https://link.springer.com/chapter/10.1007/978-3-030-00184-1_16)
2. [Finding Optimal Solutions to Cooperative Pathfinding Problems](https://ojs.aaai.org/index.php/AAAI/article/view/7564) : Operator Decomposition(OD) and Simple Independence Detectio(SID)
3. [Complete Algorithms for Cooperative Pathfinding Problems](https://www.ijcai.org/Proceedings/11/Papers/118.pdf) : Full Independence Detection(OD+ID)
