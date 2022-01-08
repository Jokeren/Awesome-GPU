Awesome-GPU
=================

   * [Architecture](#architecture)
      * [Resources Management](#resources-management)
      * [Parallelism](#parallelism)
      * [Cache](#cache)
      * [Memory](#memory)
      * [White Papers](#white-papers)
   * [Algorithms](#algorithms)
      * [BLAS](#blas)
      * [Stencils](#stencils)
      * [Scans](#scans)
   * [Applications](#applications)
      * [Deep Learning](#deep-learning)
   * [Tools](#tools)
      * [Benchmarks](#benchmarks)
      * [Models](#models)
      * [Simulators](#simulators)
      * [Profilers](#profilers)
   * [Runtime](#runtime)
      * [Scheduling](#scheduling)
   * [Code Generation](#code-generation)
      * [Compilers](#compilers)
      * [Programming Models](#programming-models)
      * [Profile Guided Optimization](#profile-guided-optimization)
      * [Binaries](#binaries)

## Architecture

### Resources Management

- **TECS'21**-[Reducing Energy in GPGPUs through Approximate Trivial Bypassing](https://dl.acm.org/doi/10.1145/3429440)
- **ASPLOS'17**-[Locality-Aware CTA Clustering for Modern GPUs](http://dl.acm.org/citation.cfm?id=3037709)
- **ASPLOS'17**-[Dynamic Resource Management for Efficient Utilization of Multitasking GPUs](http://dl.acm.org/citation.cfm?id=3037707)
- **HPCA'17**-[Dynamic GPGPU Power Management Using Adaptive Model Predictive Control](http://ieeexplore.ieee.org/document/7920860/)
- **ISCA'16**-[Transparent Offloading and Mapping (TOM): Enabling Programmer-Transparent Near-Data Processing in GPU Systems](http://ieeexplore.ieee.org/document/7551394/)

### Parallelism

- **HPCA'18**-[Accelerate GPU Concurrent Kernel Execution by Mitigating Memory Pipeline Stalls](https://ieeexplore.ieee.org/abstract/document/8327010)
- **HPCA'17**-[Controlled Kernel Launch for Dynamic Parallelism in GPUs](http://ieeexplore.ieee.org/document/7920863/)
- **GTC'17**-[COOPERATIVE GROUPS](http://on-demand.gputechconf.com/gtc/2017/presentation/s7622-Kyrylo-perelygin-robust-and-scalable-cuda.pdf)
- **ISCA'16**-[LaPerm: Locality Aware Scheduler for Dynamic Parallelism on GPUs](http://ieeexplore.ieee.org/document/7551424/)
- **ISCA'16**-[Virtual Thread Maximizing Thread-Level Parallelism beyond GPU Scheduling Limit](http://ieeexplore.ieee.org/document/7551426/)
- **Berkeley TechRpts'16**-[Understanding Latency Hiding on GPUs](https://www2.eecs.berkeley.edu/Pubs/TechRpts/2016/EECS-2016-143.html)

### Cache

- **ISCA'16**-[APRES: Improving Cache Efficiency by Exploiting Load Characteristics on GPUs](http://ieeexplore.ieee.org/document/7551393/)
- **SC'15**-[Adaptive and Transparent Cache Bypassing for GPUs](https://ieeexplore.ieee.org/document/7832791)

### Memory

- **ICCAD'21**-[Improving Inter-kernel Data Reuse With CTA-Page Coordination in GPGPU](https://ieeexplore.ieee.org/document/9643535)
- **SC'21**-[In-Depth Analyses of Unified Virtual Memory System for GPU Accelerated Computing](https://dl.acm.org/doi/10.1145/3458817.3480855)
- **IBM'20**-[Umpire: Application-Focused Management and Coordination of Complex Hierarchical Memory](https://ieeexplore.ieee.org/document/8907404)
- **HPCA'13**-[Reducing GPU Offload Latency via Fine-Grained CPU-GPU Synchronization](https://ieeexplore.ieee.org/document/6522332)

### White Papers

- **NVIDIA Ampere**-[NVIDIA A100 Tensor Core GPU Architecture](https://www.nvidia.com/content/dam/en-zz/Solutions/Data-Center/nvidia-ampere-architecture-whitepaper.pdf)
- **NVIDIA Turing**-[NVIDIA TURING GPU ARCHITECTURE](https://www.nvidia.com/en-us/design-visualization/technologies/turing-architecture/)
- **NVIDIA Volta**-[NVIDIA TESLA V100](http://www.nvidia.com/object/volta-architecture-whitepaper.html)
- **NVIDIA Pascal**-[NVIDIA TESLA P100](http://www.nvidia.com/object/gpu-architecture.html)
- **NVIDIA Kepler**-[NVIDIA’s Next Generation CUDA Compute Architecture: Kepler](https://www.nvidia.com/content/PDF/kepler/NVIDIA-Kepler-GK110-Architecture-Whitepaper.pdf)
- **NVIDIA Fermi**-[NVIDIA’s Next Generation CUDA Compute Architecture: Fermi](https://www.nvidia.com/content/PDF/fermi_white_papers/NVIDIA_Fermi_Compute_Architecture_Whitepaper.pdf)
- **AMD CDNA 2**-[INTRODUCING AMD CDNA 2 ARCHITECTURE](https://www.amd.com/system/files/documents/amd-cdna2-white-paper.pdf)
- **AMD CDNA**-[INTRODUCING AMD CDNA ARCHITECTURE](https://www.amd.com/system/files/documents/amd-cdna-whitepaper.pdf)

## Algorithms

### BLAS

- **IPDPS'20**-[Demystifying Tensor Cores to Optimize Half-Precision Matrix Multiply](https://ieeexplore.ieee.org/abstract/document/9139835)
- **PPoPP'19**-[A Coordinated Tiling and Batching Framework for Efficient GEMM on GPU](https://dl.acm.org/doi/10.1145/3293883.3295734)
- **GTC'18**-[CUTLASS: CUDA TEMPLATE LIBRARY FOR DENSE LINEAR ALGEBRA AT ALL LEVELS AND SCALES](http://on-demand.gputechconf.com/gtc/2018/presentation/s8854-cutlass-software-primitives-for-dense-linear-algebra-at-all-levels-and-scales-within-cuda.pdf)

### Stencils

- **CGO'20**-[AN5D: Automated Stencil Framework for High-Degree Temporal Blocking on GPUs](https://dl.acm.org/doi/10.1145/3368826.3377904)
- **IPDPS'20**-[On Optimizing Complex Stencils on GPUs](https://ieeexplore.ieee.org/document/8820786)
- **PPoPP'18**-[Register Optimizations for Stencils on GPUs](https://dl.acm.org/doi/abs/10.1145/3178487.3178500)

### Scans

- **NVResearch TechRpts'16**-[Single-pass Parallel Prefix Scan with Decoupled Look-back](https://research.nvidia.com/publication/single-pass-parallel-prefix-scan-decoupled-look-back)

## Applications

### Deep Learning

- **PPoPP'21**-[Understanding and bridging the gaps in current GNN performance optimizations](https://dl.acm.org/doi/10.1145/3437801.3441585)
- **SC'21**-[E.T.: re-thinking self-attention for transformer models on GPUs](https://dl.acm.org/doi/abs/10.1145/3458817.3476138)
- **OSDI'21**-[GNNAdvisor: An Adaptive and Efficient Runtime System for GNN Acceleration on GPUs](https://www.usenix.org/system/files/osdi21-wang-yuke.pdf)
- **SC'20**-[Sparse GPU Kernels for Deep Learning](https://arxiv.org/abs/2006.10901)
- **PPoPP'18**-[SuperNeurons: Dynamic GPU Memory Management for Training Deep Neural Networks](https://arxiv.org/abs/1801.04380)
- **HPCA'17**-[Towards Pervasive and User Satisfactory CNN across GPU Microarchitectures](http://ieeexplore.ieee.org/document/7920809/)

## Tools

### Benchmarks

- **GTC'18**-[Dissecting the NVIDIA Volta GPU Architecture via Microbenchmarking](https://arxiv.org/pdf/1804.06826.pdf)
- **ISPASS'10**-[Demystifying GPU Microarchitecture through Microbenchmarking](http://ieeexplore.ieee.org/document/5452013/)

### Models

- **PMBS'19**-[Instruction Roofline An insightful visual performance model for GPUs](https://ieeexplore.ieee.org/document/9059264)
- **ECP'19**-[Performance Tuning of Scientific Codes with the Roofline Model](https://crd.lbl.gov/assets/Uploads/ECP19-Roofline-1-intro.pdf)
- **GTC'18**-[VOLTA Architecture and performance optimization](http://on-demand.gputechconf.com/gtc/2018/presentation/s81006-volta-architecture-and-performance-optimization.pdf)
- **Synthesis Lectures on Computer Architecture'12**-[Performance Analysis and Tuning for General Purpose Graphics Processing Units (GPGPU)](http://ieeexplore.ieee.org/xpl/articleDetails.jsp?arnumber=6812836&newsearch=true&queryText=Performance%20Analysis%20and%20Tuning%20for%20General%20Purpose%20Graphics%20Processing%20Units%2038%20.LB.GPGPU.RB.)
- **SC'10**-[Fundamental_Optimizations](https://www.nvidia.com/content/PDF/sc_2010/CUDA_Tutorial/SC10_Fundamental_Optimizations.pdf)

### Simulators

- **ISPASS'10**-[Visualizing Complex Dynamics in Many-Core Accelerator Architectures](http://ieeexplore.ieee.org/document/5452029/)
- **ISPASS'09**-[Analyzing CUDA Workloads Using a Detailed GPU Simulator](http://ieeexplore.ieee.org/abstract/document/4919648/)

### Profilers

- **PLDI'18**-[GPU Code Optimization using Abstract Kernel Emulation and Sensitivity Analysis](https://dl.acm.org/citation.cfm?id=3192397)
- **CGO'18**-[CUDAAdvisor: LLVM-based runtime profiling for modern GPUs](https://dl.acm.org/citation.cfm?id=3168831)
- **CCGRID'18**-[Exposing Hidden Performance Opportunities in High Performance GPU Applications ](https://ieeexplore.ieee.org/document/8411034)
- **THPC'16**-[Monitoring Heterogeneous Applications with the OpenMP Tools Interface](https://link.springer.com/chapter/10.1007/978-3-319-56702-0_3)
- **Euro-Par'15**-[Identifying Optimization Opportunities Within Kernel Execution in GPU Codes](https://link.springer.com/chapter/10.1007/978-3-319-27308-2_16)
- **SC'13**-[Effective sampling-driven performance tools for GPU-accelerated supercomputers](https://dl.acm.org/citation.cfm?id=2503299)
- **ISPASS'12**-[Lynx: A dynamic instrumentation system for data-parallel applications on GPGPU architectures ](https://ieeexplore.ieee.org/document/6189206)
- **ICPP'11**-[Parallel Performance Measurement of Heterogeneous Parallel Systems with GPUs](https://dl.acm.org/citation.cfm?id=2066951)
- [**Vampir|Score-P**](http://www.vi-hps.org/projects/score-p/)
- [**TAU**](https://www.cs.uoregon.edu/research/tau/home.php)
- [**PAPI**](http://icl.utk.edu/papi/)
- [**Allinea MAP**](https://www.allinea.com/products/map/)
- [**Open|SpeedShop**](https://openspeedshop.org/)
- [**HPCToolkit**](http://hpctoolkit.org/)
- [**NVIDIA Nsight Systems**](https://developer.nvidia.com/nsight-systems)
- [**NVIDIA Nsight Compute**](https://developer.nvidia.com/nsight-compute)
- [**SASSI**](https://github.com/NVlabs/SASSI/blob/master/doc/SASSI-Tutorial-Micro2015.pptx)
- [**NVBit**](https://github.com/NVlabs/NVBit/releases)

## Runtime

### Scheduling

- **PPoPP'22**-[CASE: A Compiler-Assisted SchEduling Framework for Multi-GPU Systems](https://arxiv.org/abs/2107.08538)
- **TPDS'20**-[cCUDA: Effective Co-Scheduling of Concurrent Kernels on GPUs](https://www.computer.org/csdl/journal/td/2020/04/08853389/1dKnnndWFwY)

## Code Generation

### Compilers

- **AMD'21**-[Generating GPU Compiler Heuristics using Reinforcement Learning](https://arxiv.org/abs/2111.12055)
- **TACO'21**-[Domain-Specific Multi-Level IR Rewriting for GPU: The Open Earth Compiler for GPU-accelerated Climate Simulation](https://dl.acm.org/doi/10.1145/3469030)
- **LLVM'17**-[Implementing implicit OpenMP data sharing on GPUs](https://dl.acm.org/citation.cfm?id=3148189)
- **CGO'16**-[gpucc: An Open-Source GPGPU Compiler](http://dl.acm.org/citation.cfm?id=2854041)
- **LLVM'16**-[Offloading Support for OpenMP in Clang and LLVM](https://dl.acm.org/citation.cfm?id=3018870)
- **PMBS'15**-[Performance Analysis of OpenMP on a GPU using a CORAL Proxy Application](https://dl.acm.org/citation.cfm?id=2832089)
- **LLVM'15**-[Integrating GPU Support for OpenMP Ofﬂoading Directives into Clang](https://dl.acm.org/citation.cfm?id=2833161)
- **LLVM'14**-[Coordinating GPU Threads for OpenMP 4.0 in LLVM](https://dl.acm.org/citation.cfm?id=2688364)

### Programming Models

- **CGO'21**-[C-for-metal: high performance SIMD programming on intel GPUs](https://dl.acm.org/doi/abs/10.1109/CGO51591.2021.9370324)
- **ECRTS'19**-[Novel Methodologies for Predictable CPU-To-GPU Command Offloading](https://drops.dagstuhl.de/opus/volltexte/2019/10759/)
- **ASPLOS'14**-[Paraprox: Pattern-Based Approximation for Data Parallel Applications](https://dl.acm.org/citation.cfm?id=2541948)

### Profile Guided Optimization

- **Geometry and Optimization'21**-[Cooperative Profile Guided Optimizations](https://doi.org/10.1111/cgf.14382)
- **IPDPS'13**-[Kernel Specialization for Improved Adaptability and Performance on Graphics Processing Units (GPUs)](https://ieeexplore.ieee.org/document/6569883)

### Binaries

- **CGO'19**-[Decoding CUDA binary](https://dl.acm.org/citation.cfm?id=3314900)
- **ISCA'15**-[Flexible software profiling of GPU architectures](http://ieeexplore.ieee.org/document/7284065/)

