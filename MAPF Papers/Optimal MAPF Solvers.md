# Optimal MAPF Solvers
- **Extensions of A-Star.** These are algorithms that search the k-agent search space using a variant of the A* algorithm.
- **The Increasing Cost Tree Search.** This algorithm splits the MAPF problem into two problems: ﬁnding the cost added by each agent, and ﬁnding a valid solution with these costs.
- **Conflict-Based Search.** This algorithmic family solves MAPF by solving multiple single-agent pathﬁnding problems. To achieve coordination, speciﬁc constraints are added incrementally to the single-agent pathﬁnding problems, in a way that veriﬁes soundness, completeness, and optimality.
- **Constraints programming.** This approach compiles MAPF to a set of constraints and solves them with a general purpose constraints solver.
## Extensions of A*
