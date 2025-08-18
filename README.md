# Hi there, I'm Ruihan Li 👋

## 🚀 Infrastructure & High-Performance Computing Engineer

I'm a Computer Engineering graduate student at NYU with a passion for building high-performance systems and optimizing computational workloads at scale. My expertise spans from low-level GPU kernel optimization to compiler infrastructure and distributed systems.

📍 Brooklyn, NY | 📧 rl5409@nyu.edu | 🎓 NYU '25

---

## 🔥 Technical Highlights

- **41.8 TFLOPS** achieved on 4096×4096 SGEMM (81.6% of cuBLAS performance) through custom CUDA kernels
- **MLIR Compiler Backend** development for Ventus GPGPU architecture with custom lowering passes
- **GPU-Accelerated ETL Pipeline** with 2.3x throughput improvement using PyTorch optimizations
- **RISC-V CPU Simulator** with 5-stage pipeline and configurable cache hierarchy

---

## 💼 Professional Experience

### **Software Engineering Intern** | Suzhou Benjoe Tech | *Jun 2025 - Aug 2025*
**Impact**: Built GPU-accelerated data pipeline processing 100M+ aviation trajectory records daily

- Designed ETL pipeline for ADS-B data with coordinate transformation (LLA→ECEF) and anomaly filtering
- Integrated GPU compute nodes achieving **35% training time reduction** through:
  - `torch.compile` graph optimization and operator fusion
  - Mixed precision training (AMP) with fused AdamW optimizer
  - OneCycleLR scheduling with cuDNN autotuner
- Implemented comprehensive profiling framework using pynvml/NVTX for GPU utilization monitoring

### **MLIR Compiler Intern** | PLCT Lab, Chinese Academy of Sciences | *Jan 2025 - Apr 2025*
**Impact**: Extended MLIR framework to support novel RISC-V GPGPU architecture

- Developed complete compilation pipeline from Linalg dialect to Ventus simulator backend
- Implemented lowering passes for affine, memref, scf dialects with **memory optimization**
- Designed custom mlir-translate for GPU barrier synchronization primitives
- Enabled backpropagation algorithms with shared memory optimization

### **Research Intern** | OpenBPU, Institute of Computing Technology | *Jun 2024 - Aug 2024*
**Focus**: RISC-V GPGPU simulation infrastructure

- Extended GPGPU-Sim with CUDA PTX and OpenCL support for RISC-V targets
- Analyzed performance characteristics of GPU workloads on RISC-V architecture

---

## 🛠️ Featured Projects

### **⚡ High-Performance SGEMM Kernel**
Custom CUDA implementation approaching cuBLAS performance
```cuda
// Key optimizations implemented
- Multi-level tiling (128×128×8)
- Double-buffered shared memory
- Vectorized memory access (float4)
- Register blocking for compute intensity
```
**Results**: 41.8 TFLOPS on RTX 4090 | 81.6% cuBLAS efficiency | [Benchmark Framework](link)

### **🔧 RISC-V CPU Simulator in C++**
Full-system simulator with debugging capabilities
- 5-stage pipeline (IF/ID/EX/MEM/WB) for RV32I ISA
- GNU-compatible debugger with breakpoints and memory inspection
- Configurable cache hierarchy with performance counters
- **Performance**: 10M+ instructions/sec simulation speed

### **🏗️ Winograd Convolution Accelerator**
Hardware accelerator IP using Scala/Chisel
- Winograd algorithm implementation reducing multiplication by 2.25x
- Configurable PE arrays with ping-pong buffering
- Pipeline optimization for minimal data movement
- **Target**: 100+ GOPS on FPGA implementation

---

## 🔬 Technical Skills

### **Languages & Frameworks**
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![CUDA](https://img.shields.io/badge/-CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![MLIR](https://img.shields.io/badge/-MLIR-5C85DE?style=flat-square&logo=llvm&logoColor=white)

- **GPU Programming**: CUDA, cuBLAS, cuDNN, Triton, CUTLASS
- **Compilers**: LLVM/MLIR, GCC, PTX, SPIR-V
- **HPC Tools**: MPI, OpenMP, NCCL, UCX
- **Profiling**: NSight, VTune, perf, NVTX
- **Hardware**: Verilog, Chisel, FPGA

### **Infrastructure & Systems**
- **Distributed Systems**: Ray, Horovod, DDP
- **Container & Orchestration**: Docker, Kubernetes, Slurm
- **Monitoring**: Prometheus, Grafana, ELK Stack

---

## 📊 Open Source Contributions

### **[vLLM](https://github.com/vllm-project/vllm)** 
- Optimized attention kernel for A100 tensor cores
- Contributed to PagedAttention implementation

### **[LLVM Project](https://github.com/llvm/llvm-project)**
- RISC-V backend optimization passes
- MLIR dialect extensions for GPU operations

### **[Triton](https://github.com/openai/triton)**
- Custom kernels for specialized operators
- Performance benchmarking suite

---

## 📈 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=yourusername&show_icons=true&theme=dark&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=yourusername&layout=compact&theme=dark)

---

## 🎯 Current Focus

- 🔭 Working on distributed training infrastructure for LLMs
- 🌱 Learning about kernel fusion techniques and graph compilers
- 👯 Looking to collaborate on HPC and compiler optimization projects
- 💬 Ask me about GPU optimization, MLIR, or system performance

---

## 📫 Connect with Me

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/yourusername)
[![Email](https://img.shields.io/badge/-Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:rl5409@nyu.edu)
[![Website](https://img.shields.io/badge/-Website-000000?style=flat-square&logo=google-chrome&logoColor=white)](https://yourwebsite.com)

---

*"Performance is not just about speed, it's about doing more with less."*
