# C Pointer Bug: Unexpected Value Change
This repository demonstrates a common C programming error involving pointers and how to avoid it. The `bug.c` file contains code that leads to an unexpected change in the value of a variable due to incorrect pointer manipulation. The solution is presented in `bugSolution.c`.

**Error Explanation**
The original code directly manipulates the memory location pointed to by `ptr` without considering potential side effects. This can lead to unexpected behavior and data corruption.