#### Parallel Computing Optimization of the ICON Weather Forecasting Model Module

During the optimization of the ICON weather forecasting model jointly developed by the German Weather Service (DWD) and the Max Planck Institute for Meteorology in ISC' 24 SCC, I was responsible for parallel computing optimization of the μphys module. Using OpenMP GPU Offload technology, I conducted an in-depth analysis of the module's computational hotspots and migrated key computation tasks to the GPU. By optimizing parallelization strategies and memory transfer, I maximized GPU resource utilization efficiency. As a result, the optimized module achieved a **300x speedup** compared to the serial version, outperforming supercomputing teams from institutions such as ETH Zurich and Tsinghua University. Due to this achievement, **I was invited to become a co-developer of the application** and **shared this optimization technique in the SC’24 Student Lightning Talk**.

#### YatsenOS-v2

[[code]](https://github.com/henry-y/YatSenOS-v2)

I developed an x86_64 architecture operating system using Rust in my Operating-System course, focusing on implementing key operating system functionalities. The system includes process scheduling, interrupt handling, user-space and kernel-space switching, system calls, the fork mechanism, concurrency handling, lock mechanisms, memory management, and a basic shell. Through the implementation of these modules, I gained an in-depth understanding of the core principles behind operating system mechanisms and effectively addressed complex issues such as multi-threaded concurrency and resource management.
