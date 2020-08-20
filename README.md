# Serial and Parallel Optimisation of the Jacobi Algorithm

This repository contains three versions (original, serialy optimised and parallellised) of the iterative Jacobi method used to solve a system of linear equations.
See the [Wikipedia page](https://en.wikipedia.org/wiki/Jacobi_method) for a full description of the Jacobi method.

### Compiling and running

The code can be compiled by typing `make`. To change the compiler or flags, you should modify the Makefile.

The program can be run without any arguments to solve a default problem.
The `-n` and `-i` arguments can be used to control the matrix size and maximum number of iterations.
For example, to solve for a 500x500 matrix, use the following command:

    ./jacobi -n 500

Use `--help` to see a full description for all of the command-line arguments.
