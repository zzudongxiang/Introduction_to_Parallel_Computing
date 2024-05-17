# Introduction to Parallel Computing

> 原文参考链接：[http://users.atw.hu/parallelcomp/index.html](http://users.atw.hu/parallelcomp/index.html)

- [ ] [Chapter 1 - Introduction to Parallel Computing](./Chapter 1 - Introduction to Parallel Computing/)
  - [ ] [1.1 Motivating Parallelism](#)
  - [ ] [1.2 Scope of Parallel Computing](#)
  - [ ] [1.3 Organization and Contents of the Text](#)
  - [ ] [1.4 Bibliographic Remarks](#)
- [ ] [Chapter 2 - Parallel Programming Platforms](./Chapter 2 - Parallel Programming Platforms/)
  - [ ] [2.1 Implicit Parallelism: Trends in Microprocessor Architectures](#)
  - [ ] [2.2 Limitations of Memory System Performance](#)
  - [ ] [2.3 Dichotomy of Parallel Computing Platforms](#)
  - [ ] [2.4 Physical Organization of Parallel Platforms](#)
  - [ ] [2.5 Communication Costs in Parallel Machines](#)
  - [ ] [2.6 Routing Mechanisms for Interconnection Networks](#)
  - [ ] [2.7 Impact of Process-Processor Mapping and Mapping Techniques](#)
  - [ ] [2.8 Bibliographic Remarks](#)
- [ ] [Chapter 3 - Principles of Parallel Algorithm Design](./Chapter 3 - Principles of Parallel Algorithm Design/)
  - [ ] [3.1 Preliminaries](#)
  - [ ] [3.2 Decomposition Techniques](#)
  - [ ] [3.3 Characteristics of Tasks and Interactions](#)
  - [ ] [3.4 Mapping Techniques for Load Balancing](#)
  - [ ] [3.5 Methods for Containing Interaction Overheads](#)
  - [ ] [3.6 Parallel Algorithm Models](#)
  - [ ] [3.7 Bibliographic Remarks](#)
- [ ] [Chapter 4 - Basic Communication Operations](./Chapter 4 - Basic Communication Operations/)
  - [ ] [4.1 One-to-All Broadcast and All-to-One Reduction](#)
  - [ ] [4.2 All-to-All Broadcast and Reduction](#)
  - [ ] [4.3 All-Reduce and Prefix-Sum Operations](#)
  - [ ] [4.4 Scatter and Gather](#)
  - [ ] [4.5 All-to-All Personalized Communication](#)
  - [ ] [4.6 Circular Shift](#)
  - [ ] [4.7 Improving the Speed of Some Communication Operations](#)
  - [ ] [4.8 Summary](#)
  - [ ] [4.9 Bibliographic Remarks](#)
- [ ] [Chapter 5 - Analytical Modeling of Parallel Programs](./Chapter 5 - Analytical Modeling of Parallel Programs/)
  - [ ] [5.1 Sources of Overhead in Parallel Programs](#)
  - [ ] [5.2 Performance Metrics for Parallel Systems](#)
  - [ ] [5.3 The Effect of Granularity on Performance](#)
  - [ ] [5.4 Scalability of Parallel Systems](#)
  - [ ] [5.5 Minimum Execution Time and Minimum Cost-Optimal Execution Time](#)
  - [ ] [5.6 Asymptotic Analysis of Parallel Programs](#)
  - [ ] [5.7 Other Scalability Metrics](#)
  - [ ] [5.8 Bibliographic Remarks](#)
- [ ] [Chapter 6 - Programming Using the Message-Passing Paradigm](./Chapter 6 - Programming Using the Message-Passing Paradigm/)
  - [ ] [6.1 Principles of Message-Passing Programming](#)
  - [ ] [6.2 The Building Blocks: Send and Receive Operations](#)
  - [ ] [6.3 MPI: the Message Passing Interface](#)
  - [ ] [6.4 Topologies and Embedding](#)
  - [ ] [6.5 Overlapping Communication with Computation](#)
  - [ ] [6.6 Collective Communication and Computation Operations](#)
  - [ ] [6.7 Groups and Communicators](#)
  - [ ] [6.8 Bibliographic Remarks](#)
- [ ] [Chapter 7 - Programming Shared Address Space Platforms](./Chapter 7 - Programming Shared Address Space Platforms/)
  - [ ] [7.1 Thread Basics](#)
  - [ ] [7.2 Why Threads?](#)
  - [ ] [7.3 The POSIX Thread API](#)
  - [ ] [7.4 Thread Basics: Creation and Termination](#)
  - [ ] [7.5 Synchronization Primitives in Pthreads](#)
  - [ ] [7.6 Controlling Thread and Synchronization Attributes](#)
  - [ ] [7.7 Thread Cancellation](#)
  - [ ] [7.8 Composite Synchronization Constructs](#)
  - [ ] [7.9 Tips for Designing Asynchronous Programs](#)
  - [ ] [7.10 OpenMP: a Standard for Directive Based Parallel Programming](#)
  - [ ] [7.11 Bibliographic Remarks](#)
- [ ] [Chapter 8 - Dense Matrix Algorithms](./Chapter 8 - Dense Matrix Algorithms/)
  - [ ] [8.1 Matrix-Vector Multiplication](#)
  - [ ] [8.2 Matrix-Matrix Multiplication](#)
  - [ ] [8.3 Solving a System of Linear Equations](#)
  - [ ] [8.4 Bibliographic Remarks](#)
- [ ] [Chapter 9 - Sorting](./Chapter 9 - Sorting/)
  - [ ] [9.1 Issues in Sorting on Parallel Computers](#)
  - [ ] [9.2 Sorting Networks](#)
  - [ ] [9.3 Bubble Sort and its Variants](#)
  - [ ] [9.4 Quicksort](#)
  - [ ] [9.5 Bucket and Sample Sort](#)
  - [ ] [9.6 Other Sorting Algorithms](#)
  - [ ] [9.7 Bibliographic Remarks](#)
- [ ] [Chapter 10 - Graph Algorithms](./Chapter 10 - Graph Algorithms/)
  - [ ] [10.1 Definitions and Representation](#)
  - [ ] [10.2 Minimum Spanning Tree: Prim's Algorithm](#)
  - [ ] [10.3 Single-Source Shortest Paths: Dijkstra's Algorithm](#)
  - [ ] [10.4 All-Pairs Shortest Paths](#)
  - [ ] [10.5 Transitive Closure](#)
  - [ ] [10.6 Connected Components](#)
  - [ ] [10.7 Algorithms for Sparse Graphs](#)
  - [ ] [10.8 Bibliographic Remarks](#)
- [ ] [Chapter 11 - Search Algorithms for Discrete Optimization Problems](./Chapter 11 - Search Algorithms for Discrete Optimization Problems/)
  - [ ] [11.1 Definitions and Examples](#)
  - [ ] [11.2 Sequential Search Algorithms](#)
  - [ ] [11.3 Search Overhead Factor](#)
  - [ ] [11.4 Parallel Depth-First Search](#)
  - [ ] [11.5 Parallel Best-First Search](#)
  - [ ] [11.6 Speedup Anomalies in Parallel Search Algorithms](#)
  - [ ] [11.7 Bibliographic Remarks](#)
- [ ] [Chapter 12 - Dynamic Programming](./Chapter 12 - Dynamic Programming/)
  - [ ] [12.1 Overview of Dynamic Programming](#)
  - [ ] [12.2 Serial Monadic DP Formulations](#)
  - [ ] [12.3 Nonserial Monadic DP Formulations](#)
  - [ ] [12.4 Serial Polyadic DP Formulations](#)
  - [ ] [12.5 Nonserial Polyadic DP Formulations](#)
  - [ ] [12.6 Summary and Discussion](#)
  - [ ] [12.7 Bibliographic Remarks](#)
- [ ] [Chapter 13 - Fast Fourier Transform](./Chapter 13 - Fast Fourier Transform/)
  - [ ] [13.1 The Serial Algorithm](#)
  - [ ] [13.2 The Binary-Exchange Algorithm](#)
  - [ ] [13.3 The Transpose Algorithm](#)
  - [ ] [13.4 Bibliographic Remarks](#)