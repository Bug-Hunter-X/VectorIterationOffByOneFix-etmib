# Off-by-one Error in C++ Vector Iteration

This repository demonstrates a common off-by-one error when iterating through a `std::vector` in C++.  The error occurs because the loop condition `i <= vec.size()` attempts to access an element beyond the valid range of indices.  Vectors are 0-indexed, so the last valid index is `vec.size() - 1`.

The `bug.cpp` file contains the code with the error, while `bugSolution.cpp` provides the corrected version.