# 一、并行计算简介

## 1.1 并行计算的动机

并行计算的动机不仅来自对计算资源的需求，还来自其他（集中式）方法的不可行性（the motivation for parallelism comes not just from the need for computing resources but also from the infeasibility or undesirability of alternate (centralized) approaches）

### 1.1.1 算力的讨论

- **Moore定律**
  - 在1965年，Gordon Moore根据观察预测芯片中晶体管的数量每年翻一倍（The complexity for minimum component costs has increased at a rate of roughly a factor of two per year）
  - 在1975年之后，将这一定律修改：芯片中晶体管的数量每18个月翻一倍（He revised his rate of circuit complexity doubling to 18 months and projected from 1975 onwards at this reduced rate）
- **算力的衡量标准**
  - 较早的时候以晶体管的数量作为算力衡量的标准
  - 现在大多以每秒操作的数量（Operations per Second，OPS）作为算力的衡量标准
  - ==备注==：*现在更常用的是使用每秒钟浮点计算的次数（FLOPS）作为算力的衡量标准*

### 1.1.2 内存/硬盘速度的讨论

- **重要性**
  - 计算的整体速度不仅取决于处理器的速度，还取决于内存系统向其提供数据的能力（The overall speed of computation is determined not just by the speed of the processor, but also by the ability of the memory system to feed data to it）
- **发展现状&存在的问题**
  - 在过去的十年中，高端处理器的时钟速率每年大约提高 40%，而 DRAM 的访问时间在此期间每年大约只提高 10%（While clock rates of high-end processors have increased at roughly 40% per year over the past decade, DRAM access times have only improved at the rate of roughly 10% per year over this interval）
  - 处理器速度与 DRAM 延迟之间的这种日益严重的不匹配（This growing mismatch between processor speed and DRAM latency…）

- **解决方案**
  - 高速缓存可以弥补内存系统与处理器之间的延迟和速度不匹配的问题（… typically bridged by a hierarchy of successively faster memory devices called caches …）
  - 更大的聚合高速缓存（larger aggregate caches）
  - 更高的聚合内存系统带宽（aggregate bandwidth to the memory system）


### 1.1.3 数据通信的讨论

- **发展现状**
  - 随着网络基础设施的发展，将互联网作为一个大型异构并行分布式计算环境的愿景已经开始形成（As the networking infrastructure evolves, the vision of using the Internet as one large heterogeneous parallel/distributed computing environment has begun to take shape）
- **应用场景** 
  - 在广域分布式平台中，地外智能搜索（Search for Extra Terrestrial Intelligence，SETI）项目利用大量家用电脑的力量来分析来自外太空的电磁信号（Some of the most impressive applications of massively parallel computing have been in the context of wide-area distributed platforms. The SETI  project utilizes the power of a large number of home computers to analyze electromagnetic signals from outer space）
  - 在数据或资源在互联网上的位置都受到限制时，挖掘分布在带宽相对较低的网络上的大型商业数据集（An example of such an application is mining of large commercial datasets distributed over a relatively low bandwidth network. In such applications, even if the computing power is available to accomplish the required task without resorting to parallel computing, it is infeasible to collect the data at a central location）

## 1.2 并行计算的应用范围

并行计算的成本优势与应用对性能的要求共同构成了支持并行计算的有力论据（The cost benefits of parallelism coupled with the performance requirements of applications present compelling arguments in favor of parallel computing）

### 1.2.1 工业设计

- **应用场景**
  - 机翼设计（airfoils ）：优化升力、阻力、稳定性（optimizing lift, drag, stability）
  - 内燃机设计（internal combustion engines）：优化装料分布、燃烧（optimizing charge distribution, burn）
  - 高速电路设计（high-speed circuits）：延迟、电容和电感效应布局 (layouts for delays and capacitive and inductive effects)
  - 结构设计（structures）：优化结构完整性、设计参数、成本等（optimizing structural integrity, design parameters, cost）
  - 微机电系统（microelectromechanical）和纳米机电系统（nanoelectromechanical systems，MEMS  and NEMS）
- **发展现状**
  - 工业设计领域的应用侧重于各种流程的优化（focus on optimization of a variety of processes.）
  - 并行计算机已被用于解决各种离散和连续优化问题（Parallel computers have been used to solve a variety of discrete and continuous optimization problems）

### 1.2.2 科学应用

- **应用场景**
  - 分析生物序列以开发新药和治疗疾病和医疗条件（Analyzing biological sequences with a view to developing new drugs and cures for diseases and medical conditions）
  - 计算物理学和化学的进步侧重于理解从量子现象到大分子结构的各种过程（Advances in computational physics and chemistry have focused on understanding processes ranging in scale from quantum phenomena to macromolecular structures）
  - 天体物理学中的应用探索了星系的演化、热核过程以及对来自望远镜的超大数据集的分析（Applications in astrophysics have explored the evolution of galaxies, thermonuclear processes, and the analysis of extremely large datasets from telescopes）
  - 天气建模、矿产勘探、洪水预测等在很大程度上依赖于并行计算机（Weather modeling, mineral prospecting, flood prediction, etc., rely heavily on parallel computers）

### 1.2.3 商业应用

- **应用场景**
  - 在交易量大的日子里，华尔街的大型经纪公司会同时处理数十万个用户会话和数百万个订单（on heavy volume days, large brokerage houses on Wall Street handle hundreds of thousands of simultaneous user sessions and millions of orders）
  - 数据的庞大数量和地理分布性质要求使用有效的并行算法来解决关联规则挖掘、聚类、分类和时间序列分析等问题（The sheer volume and geographically distributed nature of this data require the use of effective parallel algorithms for such problems as association rule mining, clustering, classification, and time-series analysis）

### 1.2.4 计算机系统

- **应用场景**
  - 在网络入侵检测中，数据是在分布式站点收集的，必须对入侵信号进行快速分析（In the case of network intrusion detection, data is collected at distributed sites and must be analyzed rapidly for signaling intrusion）
  - 现代汽车由数十个处理器组成，它们通过通信执行复杂的任务，以优化操控性和性能（A modern automobile consists of tens of processors communicating to perform complex tasks for optimizing handling and performance）
