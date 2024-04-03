---
layout: post
title:  "ViolationLS: Constraint-Based Local Search in CP-SAT"
date:   2024-04-03
categories: paper
---
We introduce ViolationLS, a Constraint-Based Local Search (CBLS) solver based on the Feasibility Jump Mixed-Integer Programming Heuristic.
Our solver uses a novel approach for finding multi-variable moves without requiring any "implicit" or "one-way" constraints traditionally used by CBLS solvers.
The new solver significantly outperforms other CBLS solvers on the MiniZinc challenge benchmarks, both with and without multi-variable moves.
ViolationLS is integrated into the parallel portfolio framework of the state-of-the-art CP-SAT Lazy Clause Generation solver, and we show that this integration improves performance on more than half of the instances in the MiniZinc challenge.
To our knowledge this is the first instance of such an integration of CBLS and Lazy Clause Generation inside the same solver.

[pdf](_papers/ViolationLSPaper.pdf)

