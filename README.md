# HW3-All-Pairs-Shortest-Path-CPU
## Goal:
This homework helps you understand the all-pairs shortest path problem.

## Requirements:
In this assignment, you are asked to:
1. Implement a program that solves the all-pairs shortest path problem.
        You are required to use threading to parallelize the computation in your program.
        You can choose any threading library or framework you like (pthread, std::thread, OpenMP, Intel TBB, etc).
        You can choose any algorithm to solve the problem.
        You must implement the shortest path algorithm yourself. (Do not use libraries to solve the problem. Ask TA if unsure).
2. Create your input test case.

Execute by: 
```
make
srun -N1 -n1 -cCPUs ./hw3 <input_path> <output_path>
```
