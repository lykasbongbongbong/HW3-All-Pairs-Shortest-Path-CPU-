# HW3-All-Pairs-Shortest-Path-CPU
## Goal:
This homework helps us understand the all-pairs shortest path problem.

## Requirements:
In this assignment, we are asked to:
1. Implement a program that solves the all-pairs shortest path problem.
        we are required to use threading to parallelize the computation in your program.
        we can choose any threading library or framework you like (pthread, std::thread, OpenMP, Intel TBB, etc).
        we can choose any algorithm to solve the problem.
        we must implement the shortest path algorithm ourselves. 
2. Create our input test case.

Execute by: 
```
make
srun -N1 -n1 -cCPUs ./hw3 <input_path> <output_path>
```
