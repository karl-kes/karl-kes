# Karl Keshavarzi

**Computer Engineering, University of Waterloo**

I write low-level systems and HPC software: CUDA kernels, parallel solvers, and code that lives close to the hardware. My research experience centers on distributed GPU algorithms for maximally independent sets. I've recently begun work on ML compilers with the UWHPC design team.

## Projects

### ∂T/∂t = α∇²T
**[3D Heat Solver](https://github.com/karl-kes/3d-heat-solver)**  
A C++ solver for the 3D heat equation using an explicit forward Euler finite-difference scheme, with dual-backend CPU (OpenMP/SIMD) and GPU (CUDA) execution from unified source. Achieves 60-68x GPU speedup at large grid sizes, validated against Neumann eigenfunction solutions.

### **∇ × E = −∂B/∂t**
**[Finite-Difference Maxwell Solver](https://github.com/karl-kes/FDTD-Wave-Solver)**  
A 3D Finite-Difference Time-Domain (FDTD) Maxwell Solver with CPML boundary conditions. Capable of simulating and visualizing electromagnetic vector fields. Parallelized with OpenMP (CUDA in progress).

### **F = Gm₁m₂/r²**
**[N-Body Gravity Engine](https://github.com/karl-kes/N-Body-Gravity-Simulator)**  
N-Body physics engine simulationg gravity with symplectic Yoshida integration. Validated solar system dynamics with NASA JPL Horizons data across 249 years.

### **u(r) = ar / (1 + br)**
**[Variational Monte Carlo Engine](https://github.com/UWHPC/Variational-Monte-Carlo)**  
A Variational Monte Carlo engine simulating the homogeneous electron gas, built as part of UW High Performance Computing. Uses a trial wavefunction and stochastic optimization to estimate ground-state energies.

## Contact

karl.keshavarzi@uwaterloo.ca
