---
title: "Projects"
permalink: /projects/
layout: single
author_profile: true
---

# Projects

A selection of engineering and research projects I have worked on.  
All projects include code links, and some include additional research references.

---

## 1. Tensor-Core-Compatible Optimization for CP Decomposition  
**GPU Kernel Optimization for MTTKRP via Khatri–Rao Reformulation**  
*(Machine Learning Systems Lab, Advisor: Euhyun Moon)*

- Investigated the computational bottleneck in CP-ALS, specifically the MTTKRP (Matricized Tensor Times Khatri-Rao Product) operation.  
- Rewrote the Khatri-Rao product into a Tensor Core–friendly matrix multiplication form.  
- Designed CUDA kernels optimized with shared memory, warp-level parallelism, and Tensor Core acceleration.  
- Achieved significant throughput improvement compared to naïve MTTKRP implementations.  
- Research aligned with tensor decomposition methods used in large-scale ML systems.

**Code:**  
[Code](https://github.com/jshine0914/MTTKRP_Practice)

---

## 2. CUDA Matrix Multiplication Optimization  
**High-Performance GPU Matrix Multiplication via Multi-Level Tiling**  

- Implemented CUDA kernels for efficient GEMM operations.  
- Applied global memory coalescing, shared memory tiling, and register blocking.  
- Implemented **1D block-tiling** and **2D block-tiling** to increase arithmetic intensity.  
- Benchmarked performance and achieved near-cuBLAS performance levels.

**Code:**  
[Code](https://github.com/jshine0914/CUDA_matmul_optimization)




---
