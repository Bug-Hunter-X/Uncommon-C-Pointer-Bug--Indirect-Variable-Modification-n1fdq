# Uncommon C Pointer Bug: Indirect Variable Modification

This repository demonstrates a common yet subtle bug in C programming involving the use of pointers and indirect variable modification.  The bug involves unexpected behavior arising from modifying a variable indirectly through a pointer. The solution shows how to understand and avoid this issue.

## Bug Description
The original code attempts to modify the value of an integer variable indirectly using a pointer. While this is a valid operation, it's crucial to understand the implications and potential for unexpected behavior.

## Bug Solution
The solution emphasizes careful pointer usage and memory management.  It demonstrates the correct way to modify variables indirectly via pointers, mitigating the risk of unintended side effects. 

## How to Run
1. Clone this repository.
2. Compile the `bug.c` and `bugSolution.c` files using a C compiler (e.g., GCC):
   ```bash
gcc bug.c -o bug
gcc bugSolution.c -o bugSolution
   ```
3. Run the executables:
   ```bash
./bug
./bugSolution
   ```
Observe the different outputs to understand the bug and its solution.