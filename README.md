# Parallel-and-Distributed-Computing-Assignments
Assignments 1-3 Solutions

Assignment 1
This assignment focuses on basic message passing and communication in C++.
Files:
1) DynamicRecv.cpp - Implements dynamic message receiving between processes.
2) HelloWorld.cpp - A simple program that prints "Hello, World!".
3) RandomWalk.cpp - Simulates a random walk process.
4) SendRecv.cpp - Demonstrates basic send and receive operations in communication.

Assignment 2
This assignment covers parallel computing techniques, including sorting, matrix operations, and parallel reductions.
Files:
EvenOddSort.cpp - Implements an even-odd sort algorithm in parallel.
HeatDistribution.cpp - Simulates heat distribution using computational grids.
MatrixMultiply.cpp - Performs matrix multiplication in parallel.
MonteCarlo.cpp - Uses Monte Carlo methods for estimation.
ParallelDotProduct.cpp - Computes the dot product of two vectors in parallel.
ParallelReduction.cpp - Demonstrates parallel reduction techniques.
PrefixScan.cpp - Implements a parallel prefix sum (scan) operation.
TransposeMatrix.cpp - Performs matrix transposition using parallel computation.

Assignment 3
This assignment deals with numerical computations and optimizations.
Files:
CalculatingPi.cpp - Estimates the value of Pi using computational methods.
CountPrime.cpp - Counts the number of prime numbers within a given range.
DAXPY.cpp - Implements the DAXPY operation (Double-precision A·X Plus Y) for vector computations.

How to Compile and Run

Each C++ file can be compiled using g++. Example:
g++ filename.cpp -o output
./output

Requirements
C++ Compiler (g++)
MPI (for message passing programs)
OpenMP (for parallel computing programs, if applicable)
