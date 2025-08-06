# cuda-projects
A collection of independent CUDA programs exploring GPU computing, parallel processing, and performance optimization using NVIDIA's CUDA framework. (It’s a work in progress that I’m continuously extending as I explore new ideas and techniques.)

2D reduction.ipynb provides different implementations of reducing a 2D array to a 1D array such that each element in the 1D array is the sum of all the elements in a single row of the matrix. Explores different optimizations such as memory coalescing, tree-reductions, warp-level reductions and compares the execution time and other metrics.

MatrixMultiplication.ipynb implements a large scale multi-threaded matrix multiplication using shared memory and an optimization technique called tiling.

Memory_Efficient_Matrix_Transpose.ipynb - A CUDA kernel for memory-efficient matrix transpose using shared memory to ensure coalesced global memory reads and writes.


