# TypeScript Array Comparison Bug

This repository demonstrates a common bug in TypeScript when comparing arrays: the code only checks for strict equality, failing to account for arrays with the same elements but in different orders.  The `bug.ts` file contains the buggy code, while `bugSolution.ts` provides a corrected version.

The bug is subtle but can lead to unexpected behavior in applications that rely on accurate array comparisons. The solution introduces a more robust approach to comparing the contents of arrays, regardless of their order.