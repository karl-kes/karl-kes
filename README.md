# Karl Keshavarzi

**Computer Engineering, University of Waterloo**

I enjoy writing low-level systems and software, especially with C++. To foster a community that surrounds my passion, I founded the [UWHPC](https://www.uwhpc.com/) design team. My research experience focuses on distributed GPU algorithms for maximal independent sets. I'm particularly interested in HFT, GPU programming, and ML infrastructure. Open to discussing new opportunities and collaborations. Feel free to reach out.

## Projects

### **host ≡ device**
**[xpu](https://github.com/UWHPC/xpu)**  
A header-only C++23 library that lets the same allocation, layout, and math code compile for either CPU or CUDA. Forget about `#ifdef` wrapping.

### **u(r) = ar / (1 + br)**
**[Variational Monte Carlo Engine](https://github.com/UWHPC/Variational-Monte-Carlo)**  
Stochastically computes ground-state energies no analytic solution can reach. Halving the error costs four times the samples, so accuracy is a compute budget.

### ∂T/∂t = α∇²T
**[3D Heat Solver](https://github.com/karl-kes/3d-heat-solver)**  
Hits 91% of theoretical memory bandwidth on GPU, 68× faster than the multithreaded, vectorized CPU at 134M cells. Validated with analytical solutions.

### **∇ × E = −∂B/∂t**
**[Finite-Difference Maxwell Solver](https://github.com/karl-kes/FDTD-Wave-Solver)**  
11× faster with CUDA than the OpenMP path on 28M-cell grids. Cache-aligned SoA and SIMD cut CPU kernel time 44% over the AoS baseline.

### **F = Gm₁m₂/r²**
**[N-Body Gravity Engine](https://github.com/karl-kes/N-Body-Gravity-Simulator)**  
Barnes-Hut gives 53× over a direct OpenMP kernel at 131K bodies. A 4th-order Yoshida integrator holds energy error to 2e-12 across 249 simulated years.

## Contact

karl.keshavarzi@uwaterloo.ca
