.. _experience:

Research Projects
=================

Computer Science Department at Purdue University
-------------------------------------------------

**Jan 2020 ~ Now, cross-environment in-situ workflow management (in progress)** 

* Design, and prototype a framework that can be used to launch in-situ workflows across HPC and Cloud systems.
* Formalize the scheduling problem for in-situ workflows, design and evaluate heuristic-based algorithms to improve workflow metrics such as throughput and latency.
* A :ref:`paper <bib-li2021xcomposer>` was accepted by PASC'21.


**Jan 2020 ~ Now, on demand HPC/Cloud access for CyberWater project (in progress)** 

* Design/test/improve the 'on demand' HPC/Cloud acceleration feature for `Cyberwater project <https://www.cuahsi.org/projects/cyberwater/>`_ -- a community-driven, multi-institutional earth-science project.
* Enhance local development environment with Airavata SciGap based gateway APIs, so that computationally expensive/data-intensive operations are offloaded to XSEDE HPCs and public Clouds.
* Test, refine, and optimize hydrology simulation models in modern HPC environments.
* A :ref:`paper <bib-li2021launchagent>` was accepted by e-science'21.

**Jan 2019~ Dec 2019, Architecture-aware Neural Network**

Optimize Neural Networks from the system perspective:

* Co-locate data in deep/heterogeneous memory hierarchy, so that communication overhead between different components can be minimized.
* Intelligent scheduling algorithm for computation kernels to enable efficient and large-scale parallelism in modern SIMD and NUMA architectures.
* `github repo <https://github.com/fengggli/gpu-computing-materials>`_.

**Nov 2017~  Mar 2018, Memory-aware Lattice-Boltzmann Method**

Prototype and optimize a memory-aware Lattice-Boltzmann Method (LBM, a computational fluid dynamics approach to simulating complex fluid flows), which can enhance data reuse across multiple time steps.

* A :ref:`paper <bib-fu2018lbm>` was accepted by SBAC-PAD'18.

**April 2017~ Nov 2017, Performance Analysis of In-situ Methods in HPC**

In-depth performance evaluation of various high-performance transport methods (ADIOS, flexpath, DataSpaces, Decaf, DIMEs) in multiple HPC systems.

* A :ref:`paper <bib-fu2018zipper>` was accepted by HPDC'18.
* Artifacts available at: https://github.com/IUPU-HPC/workflow-bench

**Aug 2016 ~ Mar 2017, Machine Learning Workflow in HPC**

Working on s software framework for scientific workflows where RDMA technique is used to couple numerical simulation, data analysis and real-time visualization application together. 

* A distributed and optimized anomaly detection method is used to detect vortex and other special patterns from turbulence flows. 
* A :ref:`paper <bib-li2017mlworkflow>` was accepted by PEARC'17 (**Best Student Paper Award**).

**Aug 2015 ~ Apr 2016, KSSR**

Working on a kernelized sparse self-representation model(KSSR) and a novel Kernelized Fast Iterative Soft-Thresholding Algorithm(K-FISTA), to recover the underlying nonlinear structure among data.

* My work mainly includes the implementation, evaluation of the KSSR model and K-FISTA algorithm.
* A :ref:`paper <bib-bian2016kfista>`  was accepted in SDM'16.

Storage system group at IBM Research, Almaden
----------------------------------------------

**May 2019~ Aug 2019, research internship**

* Designed and implemented a unified file system interface (KVFS) for multiple key-value store backends, so that file operations are translated into key-value store put/get operations.
* Used FUSE to implement KVFS, and designed mechanisms to handle the mappings between file abstractions and data objects.
* Code base in IBM Comanche: https://github.com/IBM/comanche/tree/unstable/src/fuse. 


**May 2018~ Aug 2018, research internship**

* Worked on a high-performance key-value store, which uses NVMe SSD as data storage and keeps critical metadata in the persistent memory (pmem).
* By utilizing the advantages of persistent memory, the access to metadata such as block allocation and key-value mappings can be both hardened and fast.

**May 2017~ Aug 2017, research internship**

* Designed and implemented an NVMe-backed light-weight memory service — CO-PAGER (Collaborative Paging).
* CO-PAGER captures virtual memory page faults and performs paging operations on NVMe SSDs using fast userspace I/O.
* A :ref:`paper <bib-li2019copager>`  is accepted in HP3C'19.

..
  Wuhan National Laboratory for Optoelectronics, HUST, China
  ----------------------------------------------------------

  **Feb 2015 ~ June 2015, undergraduate thesis**

  Working on how to add SSD to Ceph(a distributed file system) as cache to improve its data access performance.

  My work mainly includes how to utilize the storage of SSD and design the new data caching algorithm.

  **Sep 2014 ~ Feb 2015, undergraduate research internship**

  Worked as a key member in a collaborative project with Huawei Company, China. Our task is to design metadata management algorithm for MRAM-based file systems. a patent is under process, and my work includes:

  * changed the original metadata access pattern, optimized the identification of performance-critical data and page replacement policy. 
  * read papers and wrote reviews about how MRAM( or other NVRAM) can be used in different methods to enhance system performance and or reduce energy consumption.
  * reviewed related patents searched from USPTO, analyzed recent technology (eg.Page Placement in hybrid PRAM and DRAM Main Memory), then made my suggestion for the project. 

Skills
=================

I use those tools intensively in my research workflow:

* Programming languages (C/C++/Java/Scala/Python)
* Performance analysis tools (Intel Vtune, Linux Perf, TAU)
* Mathematical-modelling tool (CPLEX)
* Big Data/Deep learning frameworks (Tensorflow/Pytorch/Apache Spark) 
* Storage related: redis, spdk, dpdk, pmdk, fuse, fio
* Cloud/container solutions(Google Cloud Platform, Amazon AWS, Openstack, Docker, k8s)
* CI/Build tools(cmake, Apache Maven, travis CI, Google Gtest)
