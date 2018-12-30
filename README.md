
Awesome-GPU
----

  * [Awesome-GPU](#awesome-gpu)
  * [Resources Management](#resources-management)
     * [Papers](#papers)
  * [Parallelism](#parallelism)
     * [Papers](#papers-1)
     * [Slides](#slides)
  * [Cache](#cache)
     * [Papers](#papers-2)
  * [Algorithm](#algorithm)
     * [Papers](#papers-3)
  * [Performance Analysis](#performance-analysis)
     * [Papers](#papers-4)
     * [Books](#books)
     * [Slides](#slides-1)
     * [Software](#software)
  * [Compiler](#compiler)
  * [Approximate Computing](#approximate-computing)
  * [Documentations](#documentations)
     * [White Papers](#white-papers)
     * [APIs](#apis)
  * [GTC](#gtc)


## Resources Management

### Papers

1. **ASPLOS'17**-[Locality-Aware CTA Clustering for Modern GPUs](http://dl.acm.org/citation.cfm?id=3037709)
2. **ASPLOS'17**-[Dynamic Resource Management for Efficient Utilization of Multitasking GPUs](http://dl.acm.org/citation.cfm?id=3037707)
4. **HPCA'17**-[Dynamic GPGPU Power Management Using Adaptive Model Predictive Control](http://ieeexplore.ieee.org/document/7920860/)
5. **ISCA'16**-[Transparent Offloading and Mapping (TOM): Enabling Programmer-Transparent Near-Data Processing in GPU Systems](http://ieeexplore.ieee.org/document/7551394/)

## Parallelism

### Papers


1. **HPCA'17**-[Controlled Kernel Launch for Dynamic Parallelism in GPUs](http://ieeexplore.ieee.org/document/7920863/)
2. **ISCA'16**-[LaPerm: Locality Aware Scheduler for Dynamic Parallelism on GPUs](http://ieeexplore.ieee.org/document/7551424/)
3. **ISCA'16**-[Virtual Thread Maximizing Thread-Level Parallelism beyond GPU Scheduling Limit](http://ieeexplore.ieee.org/document/7551426/)

### Slides

1. **GTC'17**-[COOPERATIVE GROUPS](http://on-demand.gputechconf.com/gtc/2017/presentation/s7622-Kyrylo-perelygin-robust-and-scalable-cuda.pdf)

## Cache

### Papers

1. **ISCA'16**-[APRES: Improving Cache Efficiency by Exploiting Load Characteristics on GPUs](http://ieeexplore.ieee.org/document/7551393/)
2. **SC'15**-[Adaptive and Transparent Cache Bypassing for GPUs](https://ieeexplore.ieee.org/document/7832791)

## Algorithm

### Papers

1. **HPCA'17**-[Towards Pervasive and User Satisfactory CNN across GPU Microarchitectures](http://ieeexplore.ieee.org/document/7920809/)

## Performance Analysis

### Papers

1. **PLDI'18**-[GPU Code Optimization using Abstract Kernel Emulation and Sensitivity Analysis](https://dl.acm.org/citation.cfm?id=3192397)
1. **ISCA'15**-[Flexible software profiling of GPU architectures](http://ieeexplore.ieee.org/document/7284065/)
2. **SC'13**-[Effective sampling-driven performance tools for GPU-accelerated supercomputers](https://dl.acm.org/citation.cfm?id=2503299)
3. **ISPASS'10**-[Demystifying GPU Microarchitecture through Microbenchmarking](http://ieeexplore.ieee.org/document/5452013/)
4. **ISPASS'10**-[Visualizing Complex Dynamics in Many-Core Accelerator Architectures](http://ieeexplore.ieee.org/document/5452029/)
5. **ISPASS'09**-[Analyzing CUDA Workloads Using a Detailed GPU Simulator](http://ieeexplore.ieee.org/abstract/document/4919648/)

### Books

1. [Performance Analysis and Tuning for General Purpose Graphics Processing Units (GPGPU)](http://ieeexplore.ieee.org/xpl/articleDetails.jsp?arnumber=6812836&newsearch=true&queryText=Performance%20Analysis%20and%20Tuning%20for%20General%20Purpose%20Graphics%20Processing%20Units%2038%20.LB.GPGPU.RB.)
2. [Monitoring Heterogeneous Applications with the OpenMP Tools Interface](https://link.springer.com/chapter/10.1007/978-3-319-56702-0_3)

### Slides

1. [SASSI](https://github.com/NVlabs/SASSI/blob/master/doc/SASSI-Tutorial-Micro2015.pptx)

### Software

1. [Vampir|Score-P](http://www.vi-hps.org/projects/score-p/)
2. [TAU](https://www.cs.uoregon.edu/research/tau/home.php)
3. [PAPI](http://icl.utk.edu/papi/)
4. [Allinea MAP](https://www.allinea.com/products/map/)
5. [Open|SpeedShop](https://openspeedshop.org/)
6. [HPCToolkit](http://hpctoolkit.org/)

## Compiler

1. **LLVM'17**-[Implementing implicit OpenMP data sharing on GPUs](https://dl.acm.org/citation.cfm?id=3148189)
2. **CGO'16**-[gpucc: An Open-Source GPGPU Compiler](http://dl.acm.org/citation.cfm?id=2854041)
3. **LLVM'16**-[Offloading Support for OpenMP in Clang and LLVM](https://dl.acm.org/citation.cfm?id=3018870)
4. **PMBS'15**-[Performance Analysis of OpenMP on a GPU using a CORAL Proxy Application](https://dl.acm.org/citation.cfm?id=2832089)
5. **LLVM'15**-[Integrating GPU Support for OpenMP Ofﬂoading Directives into Clang](https://dl.acm.org/citation.cfm?id=2833161)
6. **LLVM'14**-[Coordinating GPU Threads for OpenMP 4.0 in LLVM](https://dl.acm.org/citation.cfm?id=2688364)

## Approximate Computing

1. **ASPLOS'14**-[Paraprox: Pattern-Based Approximation for Data Parallel Applications](https://dl.acm.org/citation.cfm?id=2541948)
2. **ASPLOS'17**-[REDSPY: Exploring Value Locality in Software](https://dl.acm.org/citation.cfm?id=3037729)

## Documentations

### White Papers

1. **Volta**-[NVIDIA TESLA V100](http://www.nvidia.com/object/volta-architecture-whitepaper.html)
2. **Pascal**-[NVIDIA TESLA P100](http://www.nvidia.com/object/gpu-architecture.html)
3. **Kepler**-[NVIDIA’s Next Generation CUDA Compute Architecture: Kepler](https://www.nvidia.com/content/PDF/kepler/NVIDIA-Kepler-GK110-Architecture-Whitepaper.pdf)
4. **Fermi**-[NVIDIA’s Next Generation CUDA Compute Architecture: Fermi](https://www.nvidia.com/content/PDF/fermi_white_papers/NVIDIA_Fermi_Compute_Architecture_Whitepaper.pdf)

### APIs

1. **CUDA Toolkit Documentation**-[CUDA Toolkit Documentation](http://docs.nvidia.com/cuda/)

## GTC

1. **GTC**-[GPU Technology Conference](https://www.nvidia.com/en-us/gtc/)
