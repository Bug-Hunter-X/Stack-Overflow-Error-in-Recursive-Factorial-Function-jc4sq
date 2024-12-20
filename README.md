# Python Recursive Factorial with Stack Overflow Bug

This repository demonstrates a common error in recursive functions: the lack of a base case for negative input leading to a Stack Overflow error.  The `factorial_bug.py` file contains the buggy code. The `factorial_solution.py` file provides a corrected version.

**Bug:** The original factorial function doesn't check for negative input, causing infinite recursion when called with a negative integer. This leads to a `RecursionError: maximum recursion depth exceeded` exception.

**Solution:** The solution involves adding a check at the beginning of the function to handle negative input gracefully (e.g., by raising a ValueError or returning an appropriate value).