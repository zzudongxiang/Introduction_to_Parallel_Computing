# Introduction to Parallel Computing

> 原文参考链接：[http://users.atw.hu/parallelcomp/index.html](http://users.atw.hu/parallelcomp/index.html)

## [**Chapter 1 - 并行计算简介**](./Chapter%201%20-%20Introduction%20to%20Parallel%20Computing/)

  - [x] 1.1 并行计算的动机
  - [x] 1.2 并行计算的应用
  - [x] 1.3 本书的组织结构

## [**Chapter 2 - 并行编程平台**](./Chapter%202%20-%20Parallel%20Programming%20Platforms/)

  - [x] [2.1 隐式并行 - 微处理器架构的趋势](./Chapter%202%20-%20Parallel%20Programming%20Platforms/2.1%20Implicit%20Parallelism%20Trends%20in%20Microprocessor%20Architectures/)
  - [x] [2.2 内存系统性能的限制](./Chapter%202%20-%20Parallel%20Programming%20Platforms/2.2%20Limitations%20of%20Memory%20System%20Performance/)
  - [x] [2.3 并行计算平台的两部分](./Chapter%202%20-%20Parallel%20Programming%20Platforms/2.3%20Dichotomy%20of%20Parallel%20Computing%20Platforms/)
  - [x] [2.4 并行平台的物理结构](./Chapter%202%20-%20Parallel%20Programming%20Platforms/2.4%20Physical%20Organization%20of%20Parallel%20Platforms)
  - [ ] [2.5 Communication Costs in Parallel Machines](#)
  - [ ] [2.6 Routing Mechanisms for Interconnection Networks](#)
  - [ ] [2.7 Impact of Process-Processor Mapping and Mapping Techniques](#)

## [**Chapter 3 - Principles of Parallel Algorithm Design**](./Chapter%203%20-%20Principles%20of%20Parallel%20Algorithm%20Design/)

  - [ ] [3.1 Preliminaries](#)
  - [ ] [3.2 Decomposition Techniques](#)
  - [ ] [3.3 Characteristics of Tasks and Interactions](#)
  - [ ] [3.4 Mapping Techniques for Load Balancing](#)
  - [ ] [3.5 Methods for Containing Interaction Overheads](#)
  - [ ] [3.6 Parallel Algorithm Models](#)

## [**Chapter 4 - Basic Communication Operations**](./Chapter%204%20-%20Basic%20Communication%20Operations/)

  - [ ] [4.1 One-to-All Broadcast and All-to-One Reduction](#)
  - [ ] [4.2 All-to-All Broadcast and Reduction](#)
  - [ ] [4.3 All-Reduce and Prefix-Sum Operations](#)
  - [ ] [4.4 Scatter and Gather](#)
  - [ ] [4.5 All-to-All Personalized Communication](#)
  - [ ] [4.6 Circular Shift](#)
  - [ ] [4.7 Improving the Speed of Some Communication Operations](#)
  - [ ] [4.8 Summary](#)

## [**Chapter 5 - Analytical Modeling of Parallel Programs**](./Chapter%205%20-%20Analytical%20Modeling%20of%20Parallel%20Programs/)

  - [ ] [5.1 Sources of Overhead in Parallel Programs](#)
  - [ ] [5.2 Performance Metrics for Parallel Systems](#)
  - [ ] [5.3 The Effect of Granularity on Performance](#)
  - [ ] [5.4 Scalability of Parallel Systems](#)
  - [ ] [5.5 Minimum Execution Time and Minimum Cost-Optimal Execution Time](#)
  - [ ] [5.6 Asymptotic Analysis of Parallel Programs](#)
  - [ ] [5.7 Other Scalability Metrics](#)

## [**Chapter 6 - Programming Using the Message-Passing Paradigm**](./Chapter%206%20-%20Programming%20Using%20the%20Message-Passing%20Paradigm/)

  - [ ] [6.1 Principles of Message-Passing Programming](#)
  - [ ] [6.2 The Building Blocks: Send and Receive Operations](#)
  - [ ] [6.3 MPI: the Message Passing Interface](#)
  - [ ] [6.4 Topologies and Embedding](#)
  - [ ] [6.5 Overlapping Communication with Computation](#)
  - [ ] [6.6 Collective Communication and Computation Operations](#)
  - [ ] [6.7 Groups and Communicators](#)

## [**Chapter 7 - Programming Shared Address Space Platforms**](./Chapter%207%20-%20Programming%20Shared%20Address%20Space%20Platforms/)

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

## [**Chapter 8 - Dense Matrix Algorithms**](./Chapter%208%20-%20Dense%20Matrix%20Algorithms/)

  - [ ] [8.1 Matrix-Vector Multiplication](#)
  - [ ] [8.2 Matrix-Matrix Multiplication](#)
  - [ ] [8.3 Solving a System of Linear Equations](#)

## [**Chapter 9 - Sorting**](./Chapter%209%20-%20Sorting/)

  - [ ] [9.1 Issues in Sorting on Parallel Computers](#)
  - [ ] [9.2 Sorting Networks](#)
  - [ ] [9.3 Bubble Sort and its Variants](#)
  - [ ] [9.4 Quicksort](#)
  - [ ] [9.5 Bucket and Sample Sort](#)
  - [ ] [9.6 Other Sorting Algorithms](#)

## [**Chapter 10 - Graph Algorithms**](./Chapter%2010%20-%20Graph%20Algorithms/)

  - [ ] [10.1 Definitions and Representation](#)
  - [ ] [10.2 Minimum Spanning Tree: Prim's Algorithm](#)
  - [ ] [10.3 Single-Source Shortest Paths: Dijkstra's Algorithm](#)
  - [ ] [10.4 All-Pairs Shortest Paths](#)
  - [ ] [10.5 Transitive Closure](#)
  - [ ] [10.6 Connected Components](#)
  - [ ] [10.7 Algorithms for Sparse Graphs](#)

## [**Chapter 11 - Search Algorithms for Discrete Optimization Problems**](./Chapter%2011%20-%20Search%20Algorithms%20for%20Discrete%20Optimization%20Problems/)

  - [ ] [11.1 Definitions and Examples](#)
  - [ ] [11.2 Sequential Search Algorithms](#)
  - [ ] [11.3 Search Overhead Factor](#)
  - [ ] [11.4 Parallel Depth-First Search](#)
  - [ ] [11.5 Parallel Best-First Search](#)
  - [ ] [11.6 Speedup Anomalies in Parallel Search Algorithms](#)

## [**Chapter 12 - Dynamic Programming**](./Chapter%2012%20-%20Dynamic%20Programming/)

  - [ ] [12.1 Overview of Dynamic Programming](#)
  - [ ] [12.2 Serial Monadic DP Formulations](#)
  - [ ] [12.3 Nonserial Monadic DP Formulations](#)
  - [ ] [12.4 Serial Polyadic DP Formulations](#)
  - [ ] [12.5 Nonserial Polyadic DP Formulations](#)
  - [ ] [12.6 Summary and Discussion](#)

## [Chapter 13 - Fast Fourier Transform](./Chapter%2013%20-%20Fast%20Fourier%20Transform/)

  - [ ] [13.1 The Serial Algorithm](#)
  - [ ] [13.2 The Binary-Exchange Algorithm](#)
  - [ ] [13.3 The Transpose Algorithm](#)
