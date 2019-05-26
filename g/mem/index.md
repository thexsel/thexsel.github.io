# Efficient Exploitation of Heterogeneous Memory through OS/Compiler Support 

NSF project CNS#1619075 and #1618620 is synergey between Purdue University and College of William & Mary. 

This project focused on co-designing the compiler and the OS for emerging memories, e.g. 3D-stacked DRAM, taking HPC/analytics performance to the next level. This project developed new compiler and tool infrastructures for data management and new OS facilities for data move and sharing. 


Project duration: Sept 2016 –- Sept 2019.

## Overview

Memory is a key component of computers. Modern parallel architectures begin to employ heterogeneous memory to improve both latency and bandwidth of the memory subsystem. Typically, a heterogeneous memory system consists of a fast and a slow component and requires explicit software management. It puts unique burdens on programmers and compilers, especially in the domains of high-performance computing (HPC) and big data analytics. These challenges are crucial to the evolution of computer systems and therefore are key to future scientific discovery, economic prosperity, and national security.

To address these challenges in exploiting heterogeneous memory, this project targets co-designing the compiler and the operating system (OS): it explores i) a new compiler design that supports heterogeneity-aware data management and ii) new OS facilities for efficient data move and fair memory sharing. Overall, this project serves as a stepping stone towards a long-term vision -- taming emerging heterogeneous hardware by tightly integrating programming and OS support.

This project produced opensource codebases: Dr-BW, a bandwidth contention detector; ProfDP, a profiler for data placement; CCProf, a cache conflict analyzer; NUMA-Caffe, a deep learning framework for NUMA; StreamBox, a stream processing engine; VStore, a data store for video analytics. This project resulted in publications at ASPLOS (3), HPCA, Eurosys (2), USENIX ATC (2), ICS (2), CGO (4), IPDPS, and TACO. 

## Principal Investigators

* Felix Xiaozhu Lin, Purdue ECE

* Xu Liu, College of William and Mary

## Publications

"VStore: A Data Store for Analytics on Large Videos," Tiantu Xu, Luis Materon Botelho, and Felix Xiaozhu Lin, in Proc. Eurosys Conference, 2019.

"StreamBox-TZ: A Secure IoT Analytics Engine at the Edge," Heejin Park, Shuang Zhai, Long Lu, and Felix Xiaozhu Lin, to appear at Proc. USENIX Annual Technical Conference, 2019.

"StreamBox: Modern Stream Processing on a Multicore Machine," Hongyu Miao, Heejin Park, Myeongjae Jeon, Gennady Pekhimenko, Kathryn S. McKinley, and Felix Xiaozhu Lin, USENIX ATC, 2017.

"StreamBox-HBM: Stream Analytics on High Bandwidth Hybrid Memory," Hongyu Miao, Myeongjae Jeon, Gennady Pekhimenko, Kathryn S. McKinley, and Felix Xiaozhu Lin, in Proc. ACM Int. Conf. Architectural Support for Programming Languages and Operating Systems, 2019.

"Power SandBox: Power Awareness Redefined," Liwei Guo*, Tiantu Xu*, Mengwei Xu, Xuanzhe Liu, and Felix Xiaozhu Lin, (\*=co-primary) in Proc. Eurosys Conference, 2018.

"Dr-BW: Identifying Bandwidth Contention in NUMA Architectures with Supervised Learning," Hao Xu, Shasha Wen, Alfredo Gimenez, Todd Gamblin and Xu Liu, IEEE IPDPS, 2017.

"ProfDP: A Lightweight Profiler to Guide Data Placement in Heterogeneous Memory Systems", Shasha Wen, Lucy Cherkasova, Felix Xiaozhu Lin, Xu Liu,  ACM ICS, 2018. 

## Software deliverables

[ProfDP](http://www.cs.wm.edu/~xl10/profdp.html) -- **A Novel Differential, Data-centric Profiler that Guides Data Placement in Heterogeneous Memory Systems** 

Lead Unit: College of W&M. 

[StreamBox](https://xsel.rocks/p/streambox) -- **Stream processing at the memory speed**. 

Lead Unit: Purdue. 

[VStore](https://thexsel.github.io/p/vstore/) -- **A video store for AI**

Lead Unit: Purdue. 


## Our experiences with 3D memory, in one slide: 
![alt text][guide]

[guide]: https://thexsel.github.io/g/mem/guide.png "Guide"


