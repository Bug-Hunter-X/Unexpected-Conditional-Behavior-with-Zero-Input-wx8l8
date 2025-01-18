# Julia Bug: Unexpected Conditional Behavior with Zero Input

This repository demonstrates a subtle bug in a Julia function involving a conditional statement. The function `my_function` is intended to return the square of a positive number and the negation of a negative number. However, its behavior when the input is exactly zero is unexpected.

The `bug.jl` file contains the buggy code.  The solution is provided in `bugSolution.jl`, demonstrating the corrected function behavior.

## Bug Description

The original implementation does not explicitly handle the case where the input is 0, leading to potentially unintended consequences. The solution modifies the condition to include an equality check to ensure proper behavior.