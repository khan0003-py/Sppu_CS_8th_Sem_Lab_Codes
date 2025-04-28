
# 🚀 HPC Practical 4 - Vector Addition and Matrix Multiplication using OpenMP

This repository contains C programs for:
- **Vector Addition** using OpenMP
- **Matrix Multiplication** using OpenMP

These codes are designed for systems **without an NVIDIA GPU**, utilizing **CPU parallelism**.

---

## 📋 Requirements

- Ubuntu (WSL or native)
- GCC Compiler with OpenMP support

Install GCC if not already installed:

```bash
sudo apt update
sudo apt install gcc
```

---

## 🛠 How to Compile and Run

### 1. Vector Addition

**Compile:**
```bash
gcc -fopenmp vector_add_omp.c -o vector_add_omp
```

**Run:**
```bash
./vector_add_omp
```

---

### 2. Matrix Multiplication

**Compile:**
```bash
gcc -fopenmp matrix_mul_omp.c -o matrix_mul_omp
```

**Run:**
```bash
./matrix_mul_omp
```

---

## ❓ Why OpenMP instead of CUDA?

CUDA requires an NVIDIA GPU to run programs on GPU hardware.  
The current system does not have an NVIDIA GPU.

OpenMP allows efficient parallel programming on multi-core CPUs without needing any special hardware.  
Hence, **OpenMP** is the preferred approach for this setup.

---

**Author:** Arshad Ahmad Khan  
**Copyright:** ©2025 Arshad Ahmad Khan. All Rights Reserved.

## 🔗 Connect with Me:

[![YouTube](https://img.shields.io/badge/-YouTube-red?logo=youtube&logoColor=white)](https://www.youtube.com/@khan0003-py)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-blue?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/khan0003-py/)
[![Instagram](https://img.shields.io/badge/-Instagram-pink?logo=instagram&logoColor=white)](https://instagram.com/khan0003.py)
[![Gmail](https://img.shields.io/badge/-Gmail-blueviolet?logo=gmail&logoColor=white)](mailto:khan0003.py@gmail.com)
