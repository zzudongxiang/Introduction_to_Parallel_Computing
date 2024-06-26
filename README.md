# 并行计算导论

> 原文参考链接：[http://users.atw.hu/parallelcomp/index.html](http://users.atw.hu/parallelcomp/index.html)

**Get PDF File in** [./pdf](./pdf)

## [**Chapter 1 - 并行计算简介**](./Chapter%201%20-%20Introduction%20to%20Parallel%20Computing/README.md)

  - [x] 1.1 并行计算的动机
  - [x] 1.2 并行计算的应用
  - [x] 1.3 本书的组织结构

## [**Chapter 2 - 并行编程平台**](./Chapter%202%20-%20Parallel%20Programming%20Platforms/README.md)

  - [x] [2.1 隐式并行 - 微处理器架构的趋势](./Chapter%202%20-%20Parallel%20Programming%20Platforms/2.1%20Implicit%20Parallelism%20Trends%20in%20Microprocessor%20Architectures.md)
  - [x] [2.2 内存系统性能的限制](./Chapter%202%20-%20Parallel%20Programming%20Platforms/2.2%20Limitations%20of%20Memory%20System%20Performance.md)
  - [x] [2.3 并行计算平台的逻辑架构](./Chapter%202%20-%20Parallel%20Programming%20Platforms/2.3%20Dichotomy%20of%20Parallel%20Computing%20Platforms.md)
  - [x] [2.4 并行平台的物理架构](./Chapter%202%20-%20Parallel%20Programming%20Platforms/2.4%20Physical%20Organization%20of%20Parallel%20Platforms.md)
  - [x] [2.5 并行计算中的通信开销](./Chapter%202%20-%20Parallel%20Programming%20Platforms/2.5%20Communication%20Costs%20in%20Parallel%20Machines.md)
  - [x] [2.6 互联网络的路由机制](./Chapter%202%20-%20Parallel%20Programming%20Platforms/2.6%20Routing%20Mechanisms%20for%20Interconnection%20Networks.md)
  - [x] [2.7 进程到处理器的映射技术及其影响](./Chapter%202%20-%20Parallel%20Programming%20Platforms/2.7%20Impact%20of%20Process-Processor%20Mapping%20and%20Mapping%20Techniques.md)

## [**Chapter 3 - 并行算法设计原则**](./Chapter%203%20-%20Principles%20of%20Parallel%20Algorithm%20Design/README.md)

  - [x] [3.1 预备知识](./Chapter%203%20-%20Principles%20of%20Parallel%20Algorithm%20Design/3.1%20Preliminaries.md)
  - [x] [3.2 分解技术](./Chapter%203%20-%20Principles%20of%20Parallel%20Algorithm%20Design/3.2%20Decomposition%20Techniques.md)
  - [x] [3.3 任务与交互的特性](./Chapter%203%20-%20Principles%20of%20Parallel%20Algorithm%20Design/3.3%20Characteristics%20of%20Tasks%20and%20Interactions.md)
  - [x] [3.4 负载平衡的映射技术](./Chapter%203%20-%20Principles%20of%20Parallel%20Algorithm%20Design/3.4%20Mapping%20Techniques%20for%20Load%20Balancing.md)
  - [x] [3.5 控制交互开销的方法](./Chapter%203%20-%20Principles%20of%20Parallel%20Algorithm%20Design/3.5%20Methods%20for%20Containing%20Interaction%20Overheads.md)
  - [x] [3.6 并行算法模型](./Chapter%203%20-%20Principles%20of%20Parallel%20Algorithm%20Design/3.6%20Parallel%20Algorithm%20Models.md)

## [**Chapter 4 - 基本的通信操作**](./Chapter%204%20-%20Basic%20Communication%20Operations/README.md)

  - [x] [4.1 One-to-All Broadcast和All-to-One Reduction](./Chapter%204%20-%20Basic%20Communication%20Operations/4.1%20One-to-All%20Broadcast%20and%20All-to-One%20Reduction.md)
  - [x] [4.2 All-to-All Broadcast和All-to-All Reduction](./Chapter%204%20-%20Basic%20Communication%20Operations/4.2%20All-to-All%20Broadcast%20and%20Reduction.md)
  - [x] [4.3 All-Reduce和Prefix-Sum操作](./Chapter%204%20-%20Basic%20Communication%20Operations/4.3%20All-Reduce%20and%20Prefix-Sum%20Operations.md)
  - [x] [4.4 Scatter和Gather操作](./Chapter%204%20-%20Basic%20Communication%20Operations/4.4%20Scatter%20and%20Gather.md)
  - [x] [4.5 All-to-All Personalized Communication](./Chapter%204%20-%20Basic%20Communication%20Operations/4.5%20All-to-All%20Personalized%20Communication.md)
  - [x] [4.6 循环移位](./Chapter%204%20-%20Basic%20Communication%20Operations/4.6%20Circular%20Shift.md)
  - [x] [4.7 提高通信速度的方法](./Chapter%204%20-%20Basic%20Communication%20Operations/4.7%20Improving%20the%20Speed%20of%20Some%20Communication%20Operations.md)
  - [x] [4.8 总结](./Chapter%204%20-%20Basic%20Communication%20Operations/4.8%20Summary.md)

## [**Chapter 5 - Analytical Modeling of Parallel Programs**](./Chapter%205%20-%20Analytical%20Modeling%20of%20Parallel%20Programs/README.md)

  - [ ] [5.1 Sources of Overhead in Parallel Programs](#)
  - [ ] [5.2 Performance Metrics for Parallel Systems](#)
  - [ ] [5.3 The Effect of Granularity on Performance](#)
  - [ ] [5.4 Scalability of Parallel Systems](#)
  - [ ] [5.5 Minimum Execution Time and Minimum Cost-Optimal Execution Time](#)
  - [ ] [5.6 Asymptotic Analysis of Parallel Programs](#)
  - [ ] [5.7 Other Scalability Metrics](#)

## [**Chapter 6 - Programming Using the Message-Passing Paradigm**](./Chapter%206%20-%20Programming%20Using%20the%20Message-Passing%20Paradigm/README.md)

  - [ ] [6.1 Principles of Message-Passing Programming](#)
  - [ ] [6.2 The Building Blocks: Send and Receive Operations](#)
  - [ ] [6.3 MPI: the Message Passing Interface](#)
  - [ ] [6.4 Topologies and Embedding](#)
  - [ ] [6.5 Overlapping Communication with Computation](#)
  - [ ] [6.6 Collective Communication and Computation Operations](#)
  - [ ] [6.7 Groups and Communicators](#)

## [**Chapter 7 - Programming Shared Address Space Platforms**](./Chapter%207%20-%20Programming%20Shared%20Address%20Space%20Platforms/README.md)

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

## [**Chapter 8 - Dense Matrix Algorithms**](./Chapter%208%20-%20Dense%20Matrix%20Algorithms/README.md)

  - [ ] [8.1 Matrix-Vector Multiplication](#)
  - [ ] [8.2 Matrix-Matrix Multiplication](#)
  - [ ] [8.3 Solving a System of Linear Equations](#)

## [**Chapter 9 - Sorting**](./Chapter%209%20-%20Sorting/README.md)

  - [ ] [9.1 Issues in Sorting on Parallel Computers](#)
  - [ ] [9.2 Sorting Networks](#)
  - [ ] [9.3 Bubble Sort and its Variants](#)
  - [ ] [9.4 Quicksort](#)
  - [ ] [9.5 Bucket and Sample Sort](#)
  - [ ] [9.6 Other Sorting Algorithms](#)

## [**Chapter 10 - Graph Algorithms**](./Chapter%2010%20-%20Graph%20Algorithms/README.md)

  - [ ] [10.1 Definitions and Representation](#)
  - [ ] [10.2 Minimum Spanning Tree: Prim's Algorithm](#)
  - [ ] [10.3 Single-Source Shortest Paths: Dijkstra's Algorithm](#)
  - [ ] [10.4 All-Pairs Shortest Paths](#)
  - [ ] [10.5 Transitive Closure](#)
  - [ ] [10.6 Connected Components](#)
  - [ ] [10.7 Algorithms for Sparse Graphs](#)

## [**Chapter 11 - Search Algorithms for Discrete Optimization Problems**](./Chapter%2011%20-%20Search%20Algorithms%20for%20Discrete%20Optimization%20Problems/README.md)

  - [ ] [11.1 Definitions and Examples](#)
  - [ ] [11.2 Sequential Search Algorithms](#)
  - [ ] [11.3 Search Overhead Factor](#)
  - [ ] [11.4 Parallel Depth-First Search](#)
  - [ ] [11.5 Parallel Best-First Search](#)
  - [ ] [11.6 Speedup Anomalies in Parallel Search Algorithms](#)

## [**Chapter 12 - Dynamic Programming**](./Chapter%2012%20-%20Dynamic%20Programming/README.md)

  - [ ] [12.1 Overview of Dynamic Programming](#)
  - [ ] [12.2 Serial Monadic DP Formulations](#)
  - [ ] [12.3 Nonserial Monadic DP Formulations](#)
  - [ ] [12.4 Serial Polyadic DP Formulations](#)
  - [ ] [12.5 Nonserial Polyadic DP Formulations](#)
  - [ ] [12.6 Summary and Discussion](#)

## [Chapter 13 - Fast Fourier Transform](./Chapter%2013%20-%20Fast%20Fourier%20Transform/README.md)

  - [ ] [13.1 The Serial Algorithm](#)
  - [ ] [13.2 The Binary-Exchange Algorithm](#)
  - [ ] [13.3 The Transpose Algorithm](#)
