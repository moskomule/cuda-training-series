# CUDA Training Resource
The materials in this repository accompany the CUDA Training Series presented at ORNL and NERSC.

You can find the slides and presentation recordings at https://www.olcf.ornl.gov/cuda-training-series/

1. [Introduction to CUDA C++](https://www.olcf.ornl.gov/wp-content/uploads/2019/12/01-CUDA-C-Basics.pdf)
1. [Shared Memory](https://www.olcf.ornl.gov/wp-content/uploads/2019/12/02-CUDA-Shared-Memory.pdf)
1. [Fundamental CUDA Optimization (Part 1)](https://www.olcf.ornl.gov/wp-content/uploads/2019/12/03-CUDA-Fundamental-Optimization-Part-1.pdf)
1. [Fundamental CUDA Optimization (Part 2)](https://www.olcf.ornl.gov/wp-content/uploads/2020/04/04-CUDA-Fundamental-Optimization-Part-2.pdf)
1. [Atomics, Reductions, and Warp Shuffle](https://www.olcf.ornl.gov/wp-content/uploads/2019/12/05_Atomics_Reductions_Warp_Shuffle.pdf)
1. [Managed Memory](https://www.olcf.ornl.gov/wp-content/uploads/2019/06/06_Managed_Memory.pdf)
1. [Concurrency](https://www.olcf.ornl.gov/wp-content/uploads/2020/07/07_Concurrency.pdf)
1. [GPU Performance Analysis](https://www.olcf.ornl.gov/wp-content/uploads/2020/04/08_GPU_Performance_Analysis.pdf)
1. [Cooperative Groups](https://www.olcf.ornl.gov/wp-content/uploads/2020/06/09_Cooperative_Groups.pdf)

## Using VSCode Remote Container

`Remote-Container: Clone Repository in Container Volume` will build an NVCC enabled container.

```
CUDA_VISIBLE_DEVICES=1 nvcc --run -o out FILENAME.cu
./out
```
