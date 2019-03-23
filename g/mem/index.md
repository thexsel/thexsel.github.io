# Efficient Exploitation of Heterogeneous Memory through OS/Compiler Support 

This web page summarizes the outcome of NSF Award 1619075 and 1618620, a collaborative project between Purdue University and College of William & Mary. 

Project duration: Sept 2016 –- Sept 2019.

## Overview

Memory is a key component of computers. Modern parallel architectures begin to employ heterogeneous memory to improve both latency and bandwidth of the memory subsystem. Typically, a heterogeneous memory system consists of a fast and a slow component and requires explicit software management. It puts unique burdens on programmers and compilers, especially in the domains of high-performance computing (HPC) and big data analytics. These challenges are crucial to the evolution of computer systems and therefore are key to future scientific discovery, economic prosperity, and national security.

To address these challenges in exploiting heterogeneous memory, this project targets co-designing the compiler and the operating system (OS): it explores i) a new compiler design that supports heterogeneity-aware data management and ii) new OS facilities for efficient data move and fair memory sharing. Overall, this project serves as a stepping stone towards a long-term vision -- taming emerging heterogeneous hardware by tightly integrating programming and OS support.


## Principal Investigators

* Felix Xiaozhu Lin, Purdue ECE

* Xu Liu, College of William and Mary

## Publications

Hao Xu, Shasha Wen, Alfredo Gimenez, Todd Gamblin and Xu Liu. "Dr-BW: Identifying Bandwidth Contention in NUMA Architectures with Supervised Learning," IEEE IPDPS, 2017.

Hongyu Miao, Heejin Park, Myeongjae Jeon, Gennady Pekhimenko, Kathryn S. McKinley, and Felix Xiaozhu Lin. "StreamBox: Modern Stream Processing on a Multicore Machine," USENIX ATC, 2017.

Shasha Wen, Lucy Cherkasova, Felix Xiaozhu Lin, Xu Liu, "ProfDP: A Lightweight Profiler to Guide Data Placement in Heterogeneous Memory Systems", ACM  ICS, 2018. 

## Software deliverables

[ProfDP](http://www.cs.wm.edu/~xl10/profdp.html) -- **A Novel Differential, Data-centric Profiler that Guides Data Placement in Heterogeneous Memory Systems** 

Lead Unit: College of W&M. 

[StreamBox](https://xsel.rocks/p/streambox) -- **Stream processing at the memory speed**. 

Lead Unit: Purdue. 


## One slide for our lessons in exploiting 3D memory: 
![alt text][guide]

[guide]: https://thexsel.github.io/g/mem/guide.png "Guide"


