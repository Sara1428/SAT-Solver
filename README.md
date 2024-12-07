# SAT Solver

This repository contains a C++ implementation of an SAT (Boolean satisfiability problem) solver using the DPLL algorithm. The solver efficiently searches for satisfying assignments for Boolean formulas represented in Conjunctive Normal Form (CNF).

## Implementation

- A backtracking-based algorithm **DPLL Algorithm** is used that systematically explores possible truth assignments to solve the SAT problem.
- **Unit Propagation** is implemented which identifies unit clauses (clauses with only one unassigned literal) and propagates their values, reducing the search space and eliminating unnecessary backtracking.
- **Pure Literal Elimination** is implemented which detects pure literals (variables that appear with the same polarity in all clauses) and assigns them a value that satisfies all related clauses, simplifying the formula.
