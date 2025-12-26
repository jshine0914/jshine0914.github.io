---
title: "Projects"
permalink: /projects/
layout: single
author_profile: true
---

# Projects

A set of selected research and engineering projects.  
Descriptions are aligned with the corresponding entries in my CV.

---

## 1. Tensor-Core-Compatible Optimization for CP Decomposition  
*(Machine Learning Systems Lab, Advisor: Prof. Euhyun Moon)*

**Topic:** Tensor-Core-Compatible Optimization for CP Decomposition

- Investigated CP Decomposition, a tensor factorization method typically solved using the CP-ALS algorithm.
- Identified a major computational bottleneck in CP-ALS caused by the **MTTKRP (Matricized Tensor Times Khatri-Rao Product)** operation, which heavily depends on the Khatri-Rao product.
- Investigated a reformulation that converts the Khatri-Rao product into a matrix multiplication, enabling **Tensor Core compatibility**.

**Code:**  
[Code](https://github.com/jshine0914/MTTKRP_Practice)

---

## 2. CUDA Matrix Multiplication Optimization  

**Tools:** C/C++, CUDA

- Learned and applied optimization techniques such as:
  - global memory coalescing  
  - shared memory cache-blocking  
  - 1D blocktiling for calculating multiple results per thread  
  - increasing arithmetic intensity via **2D blocktiling**
- Achieved **near-cuBLAS performance**.

**Code:**  
[Code](https://github.com/jshine0914/CUDA_matmul_optimization)



---
