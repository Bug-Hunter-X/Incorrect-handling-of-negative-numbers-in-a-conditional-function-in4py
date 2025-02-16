# Julia Bug: Incorrect Handling of Negative Numbers

This repository demonstrates a common error in Julia programming related to the handling of negative numbers in conditional statements. The original code in `bug.jl` contains a flaw in how negative numbers are processed.  The corrected code is presented in `bugSolution.jl`.

**Bug:**
The `myfunction` function in `bug.jl` is intended to square the input.  However, the approach taken doesn't correctly handle negative inputs. 

**Solution:**
The `bugSolution.jl` file provides the corrected implementation which uses `abs()` to ensure the squaring operation is always performed on the absolute value of the input, addressing the negative number issue.  The output now correctly reflects the expected squared values for all inputs.
