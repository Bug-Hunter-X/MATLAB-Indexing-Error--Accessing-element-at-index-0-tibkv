# MATLAB Indexing Error
This repository demonstrates a common error in MATLAB: attempting to access an array element using index 0.  MATLAB uses 1-based indexing, so index 0 is invalid.

The `bug.m` file shows the incorrect code, while `bugSolution.m` provides the corrected version.

## How to reproduce the bug
1. Run `bug.m`.
2. Observe the error message indicating an index out of bounds.

## Solution
The solution is to remember that MATLAB uses 1-based indexing.  Access array elements using indices starting from 1.