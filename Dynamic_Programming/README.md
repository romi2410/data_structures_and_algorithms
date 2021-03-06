- Dynamic Programming uses additional memory to save computation time (time-memory trade-off). Savings may be dramatic - exponential time to polynomial time.

- Two ways to implement DP approach - 
  1. Top-Down - 
  Write procedure recursively, but save the result of each subproblem. First check if subproblem has been solved previously. If so, return the saved value; if not, compute value in usual manner.
  
  2. Bottom-Up -
  Sort the subproblems by size and solve them in size order, smallest first. When solving a particular subproblem, we have already solved all of the smaller subproblems its solution depends upon, and we have saved their solutions. This approach is much better because of less overhead of recursive calls.
  
- The problem must have two properties in order for DP to apply -
  1. Optimal Substructure -
  Optimal solution to the problem contains within it optimal solution to subproblems.
  
  2. Overlapping Subproblems -
  An algorithm revists the same problem repeatedly.
