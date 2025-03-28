---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# Welcome to Jin Zhao’s Homepage

Jin Zhao is an associate professor at [School of Computer Science and Technology](https://cs.hust.edu.cn/) in [Huazhong University of Science and Technology (HUST)](https://www.hust.edu.cn/). He obtained the PhD degree at September 2022 from the __Huazhong University of Science and Technology__ under the supervision of [Prof. Xiaofei Liao](http://faculty.hust.edu.cn/xfliao/zh_CN/index.htm). He has published about 30 research papers in top-tier conferences and journals, including ISCA, MICRO, SC, DAC, ACM TACO, IEEE TC, and IEEE TKDE. His research interests mainly focus on High Performance Computing, Computer Architecture, and Graph Processing.

# 🔥 News
- *2025.02*: &nbsp;🎉🎉 Our papers "A Data-Centric Hardware Accelerator for Efficient Adaptive Radix Tree" and "PairGraph: An Efficient Search-space-aware Accelerator for High-performance Concurrent Pairwise Queries" are accepted by DAC 2025!
- *2025.01*: &nbsp;🎉🎉 Our paper "OHMiner: An Overlap-centric System for Efficient Hypergraph Pattern Mining" is accepted by EuroSys 2025!
- *2024.07*: &nbsp;🎉🎉 Our paper "An Efficient ReRAM-based Accelerator for Asynchronous Iterative Graph Processing" is accepted by ACM TACO!
- *2024.07*: &nbsp;🎉🎉 Our paper "RAHP: A Redundancy-aware Accelerator for High-performance Hypergraph Neural Network" is accepted by MICRO 2024!
- *2024.02*: &nbsp;🎉🎉 Our papers "CDA-GNN: A Chain-driven Accelerator for Efficient Asynchronous Graph Neural Network" and "RTGA: A Redundancy-free Accelerator for High-Performance Temporal Graph Neural Network Inference" are accepted by DAC 2024!
- *2024.02*: &nbsp;🎉🎉 Our paper "LSGraph: A Locality-centric High-performance Streaming Graph Engine" is accepted by EuroSys 2024!

# 📝 Publications 
## 2025
- **[DAC 2025]** [A Data-Centric Hardware Accelerator for Efficient Adaptive Radix Tree]()  <br /> **<ins>Jin Zhao</ins>**, Yu Zhang, Jun Huang, weihang yin, Hui Yu, Hao Qi, Zixiao Wang, longlong lin, Xiaofei Liao, Hai Jin <br />  ***Proceedings of the 62nd IEEE/ACM Design Automation Conference***, 2025
- **[DAC 2025]** [PairGraph: An Efficient Search-space-aware Accelerator for High-performance Concurrent Pairwise Queries]() <br /> Yutao Fu, Zhongtian Long, Yu Zhang, Zirui He, **<ins>Jin Zhao</ins>**, Qiyuan Niu, Zixiao Wang, Hai Jin <br /> ***Proceedings of the 62nd IEEE/ACM Design Automation Conference***, 2025
- **[Eurosys 2025]** [OHMiner: An Overlap-centric System for Efficient Hypergraph Pattern Mining](https://dl.acm.org/doi/10.1145/3689031.3717474) <br />  Hao Qi, Kang Luo, Ligang He, Yu Zhang, Minzhi Cai, Jingxin Dai, Bingsheng He, Hai Jin, Zhan Zhang, **<ins>Jin Zhao</ins>**, Hengshan Yue, Hui Yu, Xiaofei Liao <br /> ***Proceedings of the 20th European Conference on Computer Systems***, 2025
- **[ACM TACO]** [An Efficient ReRAM-based Accelerator for Asynchronous Iterative Graph Processing](https://dl.acm.org/doi/pdf/10.1145/3689335) <br /> **<ins>Jin Zhao</ins>**, Yu Zhang, Donghao He, Qikun Li, Weihang Yin, Hui Yu, Hao Qi, Xiaofei Liao, Hai Jin, Haikun Liu, Linchen Yu, Zhang Zhan <br /> ***ACM Transactions on Architecture and Code Optimization***, 2025

## 2024
- **[MICRO 2024]** 	[RAHP: A Redundancy-aware Accelerator for High-performance Hypergraph Neural Network](https://ieeexplore.ieee.org/document/10764461) <br />  Hui Yu, Yu Zhang, Ligang He, Yingqi Zhao, Xintao Li, Ruida Xin, **<ins>Jin Zhao</ins>**, Xiaofei Liao, Haikun Liu, Bingsheng He, Hai Jin <br /> ***Proceedings of the 57th IEEE/ACM International Symposium on Microarchitecture***, 2024
- **[Eurosys 2024]** [LSGraph: A Locality-centric High-performance Streaming Graph Engine](https://dl.acm.org/doi/10.1145/3627703.3650076) <br /> Hao Qi, Yiyang Wu, Ligang He, Yu Zhang, Kang Luo, Minzhi Cai, Hai Jin, Zhan Zhang, **<ins>Jin Zhao</ins>** <br /> ***Proceedings of the 19th European Conference on Computer Systems***, 2024
- **[DAC 2024]**	[CDA-GNN: A Chain-driven Accelerator for Efficient Asynchronous Graph Neural Network](https://dl.acm.org/doi/10.1145/3649329.3656240) <br /> Hui Yu, Yu Zhang, Ligang He, Donghao He, Qikun Li, **<ins>Jin Zhao</ins>**, Xiaofei Liao, Hai Jin, Lin Gu and Haikun Liu <br /> ***Proceedings of the 61st ACM/IEEE Design Automation Conference***, 2024
- **[DAC 2024]**	[RTGA: A Redundancy-free Accelerator for High-Performance Temporal Graph Neural Network Inference](https://doi.org/10.1145/3649329.3656241) <br /> Hui Yu, Yu Zhang, Andong Tan, Chenze Lu, **<ins>Jin Zhao</ins>**, Xiaofei Liao, Hai Jin and Haikun Liu <br /> ***Proceedings of the 61st ACM/IEEE Design Automation Conference***, 2024
- **[KDD 2024]** [PSMC: Provable and Scalable Algorithms for Motif Conductance Based Graph Clustering](https://dl.acm.org/doi/10.1145/3637528.3671666) <br /> Longlong Lin, Tao Jia, Zeli Wang, **<ins>Jin Zhao</ins>**, Rong-Hua Li <br /> ***Proceedings of the 30th ACM SIGKDD Conference on Knowledge Discovery and Data Mining***, 2024
- **[CIKM 2024]** [PSNE: Efficient Spectral Sparsification Algorithms for Scaling Network Embedding](https://dl.acm.org/doi/10.1145/3627673.3679540) <br /> Longlong Lin, Yunfeng Yu, Zihao Wang, Zeli Wang, Yuying Zhao, **<ins>Jin Zhao</ins>**, Tao Jia <br /> ***Proceedings of the 33rd ACM International Conference on Information and Knowledge Management***, 2024
- **[JCST]** [Towards High-Performance Graph Processing: From a Hardware/Software Co-Design Perspective](https://link.springer.com/article/10.1007/s11390-024-4150-0) <br /> Xiaofei Liao, Wen-Ju Zhao, Hai Jin, Pengcheng Yao, Yu Huang, Qinggang Wang, **<ins>Jin Zhao</ins>**, Long Zheng, Yu Zhang, Zhiyuan Shao <br /> ***Journal of Computer Science and Technology***, 2024
- **[IEEE IoT]** [Computing Power Networking Meets Blockchain: A Reputation-enhanced Trading Framework for Decentralized IoT Cloud Services](https://ieeexplore.ieee.org/document/10414371) <br /> Li Lin, Jiapeng Wu, Zhi Zhou,  **<ins>Jin Zhao (Corresponding author)</ins>**, Peng Li, Jinbo Xiong <br /> ***IEEE Internet of Things Journal***, 2024
- **[CRAD]** [Review of Key Technologies in Graph Processing Architectures and Systems Software](https://crad.ict.ac.cn/cn/article/pdf/preview/10.7544/issn1000-1239.202220778.pdf) <br /> Yu Zhang, Xinyu Jiang, Hui Yu, **<ins>Jin Zhao (Corresponding author)</ins>**, Hao Qi, Xiaofei Liao, Hai Jin, Biao Wang, Ting Yu <br /> ***Journal of Computer Research and Development***, 2024


## 2023
- **[DAC 2023]** [SaGraph: A Similarity-aware Hardware Accelerator for Temporal Graph Processing](https://ieeexplore.ieee.org/document/10247966/)  <br /> **<ins>Jin Zhao</ins>**, Yu Zhang, Jian Cheng, Yiyang Wu, Chuyue Ye, Hui Yu, Zhiying Huang, Hai Jin, Xiaofei Liao, Lin Gu, Haikun Liu<br /> ***Proceedings of the 60th Design Automation Conference***, 2023
- **[DAC 2023]** [PSMiner: A Pattern-Aware Accelerator for High-Performance Streaming Graph Pattern Mining](https://ieeexplore.ieee.org/document/10247902)  <br /> Hao Qi, Yu Zhang, Ligang He, Kang Luo, Jun Huang, Haoyu Lu, **<ins>Jin Zhao</ins>**, Hai Jin<br /> ***Proceedings of the 60th Design Automation Conference***, 2023
- **[ACM TACO]** [GraphTune: An Efficient Dependency-Aware Substrate to Alleviate Irregularity in Concurrent Graph Processing](https://dl.acm.org/doi/pdf/10.1145/3600091) <br /> **<ins>Jin Zhao</ins>**, Yu Zhang, Ligang He, Qikun Li, Xiang Zhang, Hui Yu, Xiaofei Liao, Hai Jin, Lin Gu, Haikun Liu, Bingsheng He, Ji Zhang, Xianzheng Song, Lin Wang, Jun Zhuo  <br /> ***ACM Transactions on Architecture and Code Optimization***, 2023
- **[ACM TACO]** [RACE: An Efficient Redundancy-aware Accelerator for Dynamic Graph Neural Network](https://dl.acm.org/doi/pdf/10.1145/3617685) <br /> Hui Yu, Yu Zhang, **<ins>Jin Zhao</ins>**, Yujian Liao, Zhiying Huang, Donghao He, Lin Gu, Hai Jin, Xiaofei Liao, Haikun Liu <br /> ***ACM Transactions on Architecture and Code Optimization***, 2023
- **[IEEE TKDE]** [EGraph: Efficient Concurrent GPU-based Dynamic Graph Processing](https://dl.acm.org/doi/pdf/10.1145/3617685) <br /> Yu Zhang, Yuxuan Liang, **<ins>Jin Zhao</ins>**, Fubing Mao, Lin Gu, Xiaofei Liao, Hai Jin, Haikun Liu, Song Guo, Yangqing Zeng, Hang Hu <br /> ***IEEE Transactions on Knowledge and Data Engineering***, 2023
- **[IEEE TC]** [Accelerating Graph Convolutional Networks Through a PIM-Accelerated Approach](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10070790) <br /> Hai Jin, Dan Chen, Long Zheng, Yu Huang, Pengcheng Yao, **<ins>Jin Zhao</ins>**, Xiaofei Liao, Wenbin Jiang <br /> ***IEEE Transactions on Computers***, 2023
- **[SSI]** [An Efficient Hardware Accelerator for Monotonic Graph Algorithms on Dynamic Directed Graphs](https://www.sciengine.com/SSI/doi/10.1360/SSI-2022-0191) (in Chinese) <br /> Yun Yang, Hui Yu, **<ins>Jin Zhao</ins>**, Yu Zhang, Xiaofei Liao, Xinyu Jiang, Haikun Liu, Fubing Mao, Ji Zhang, Biao Wang <br /> ***SCIENTIA SINICA Informationis***, 2023
- **[SSI]** [Research on the Application of Graph Processing in ATPG](https://www.sciengine.com/SSI/doi/10.1360/SSI-2021-0267) (in Chinese) <br /> Fubing Mao, Da Peng, Yu Zhang, Xiaofei Liao, Xinyu Jiang, Yun Yang, Hai Jin, **<ins>Jin Zhao</ins>**, Haikun Liu, Liuzheng Wang <br /> ***SCIENTIA SINICA Informationis***, 2023


## 2022
- **[ISCA 2022]** [TDGraph: A Topology-Driven Accelerator for High-Performance Streaming Graph Processing](https://dl.acm.org/doi/10.1145/3470496.3527409) <br /> **<ins>Jin Zhao</ins>**, Yun Yang, Yu Zhang, Xiaofei Liao, Lin Gu, Ligang He, Bingsheng He, Hai Jin, Haikun Liu, Xinyu Jiang, Hui Yu <br /> ***Proceedings of the 2022 IEEE/ACM International Symposium on Computer Architecture***, 2022
- **[IEEE TC]** [A Structure-aware Storage Optimization for Out-of-Core Concurrent Graph Processing](https://ieeexplore.ieee.org/document/9495260) <br /> Xiaofei Liao, **<ins>Jin Zhao</ins>**, Yu Zhang, Bingsheng He, Ligang He, Hai Jin, Lin Gu <br /> ***IEEE Transactions on Computer*** ```Featured Paper of the Month```, 2022
- **[JCST]** [Toward High-Performance Delta-Based Iterative Processing with a Group-Based Approach](https://link.springer.com/article/10.1007/s11390-022-2101-1) <br /> Hui Yu, Xinyu Jiang, **<ins>Jin Zhao</ins>**, Hao Qi, Yu Zhang, Xiaofei Liao, Haikun Liu, Fubing Mao, Hai Jin <br /> ***Journal of Computer Science and Technology***, 2022
- **[IEEE TBD]** [GGraph: An Efficient Structure-aware Approach for Iterative Graph Processing](https://ieeexplore.ieee.org/document/9178464/) <br /> Beibei Si, Yuxuan Liang,  **<ins>Jin Zhao</ins>**, Yu Zhang, Xiaofei Liao, Hai Jin, Haikun Liu, Lin Gu <br /> ***IEEE Transactions on Big Data***, 2022
- **[Intelligent Computing]** [Software Systems Implementation and Domain-Specific Architectures towards Graph Analytics](https://spj.science.org/doi/10.34133/2022/9806758) <br /> Hai Jin, Hao Qi, **<ins>Jin Zhao</ins>**, Xinyu Jiang, Yu Huang, Chuangyi Gui, Qinggang Wang, Xinyang Shen, Yi Zhang, Ao Hu, Dan Chen, Chaoqiang Liu, Haifeng Liu, Haiheng He, Xiangyu Ye, Runze Wang, Jingrui Yuan, Pengcheng Yao, Yu Zhang, Long Zheng, Xiaofei Liao <br /> ***Intelligent Computing***, 2022
- **[SSI]** [An Efficient Storage System Towards High Throughput of Concurrent Graph Processing Jobs](https://www.sciengine.com/SSI/doi/10.1360/SSI-2021-0020) (in Chinese) <br /> **<ins>Jin Zhao</ins>**, Xinyu Jiang, Yu Zhang, Xiaofei Liao, Hai Jin, Haikun Liu, Yun Yang, Ji Zhang, Biao Wang, Ting Yu  <br /> ***SCIENTIA SINICA Informationis***, 2022

## Before 2022
- **[SC 2021]** [LCCG: A Locality-centric Hardware Accelerator for High Throughput of Concurrent Graph Processing](https://dl.acm.org/doi/10.1145/3458817.3480854) <br /> **<ins>Jin Zhao</ins>**, Yu Zhang, Xiaofei Liao, Ligang He, Bingsheng He, Hai Jin, Haikun Liu <br /> ***Proceedings of the 2021 International Conference for High Performance Computing, Networking, Storage, and Analysis***, 2021
- **[SC 2019]** [GraphM: An Efficient Storage System for High Throughput of Concurrent Graph Analytics](https://dl.acm.org/doi/10.1145/3295500.3356143) <br /> **<ins>Jin Zhao</ins>**, Yu Zhang, Xiaofei Liao, Ligang He, Bingsheng He, Hai Jin, Haikun Liu, Yicheng Chen  <br />  ***Proceedings of the 2019 International Conference for High Performance Computing, Networking, Storage, and Analysis***, 2019
- **[ACM TOS]** [CGraph: A Distributed Storage and Processing System for Concurrent Iterative Graph Analysis Jobs](https://dl.acm.org/doi/10.1145/3319406) <br /> Yu Zhang, **<ins>Jin Zhao</ins>**, Xiaofei Liao, Hai Jin, Lin Gu, Haikun Liu, Bingsheng He, Ligang He <br /> ***ACM Transactions on Storage***, 2019
- **[SSI]** [An Efficient Incremental Strongly Connected Components Algorithm for Evolving Directed Graph](https://www.sciengine.com/SSI/doi/10.1360/N112018-00125) (in Chinese) <br /> Xiaofei Liao, Yicheng Chen, Yu Zhang, Hai Jin, Haikun Liu, **<ins>Jin Zhao</ins>** <br /> ***SCIENTIA SINICA Informationis***, 2019

# 🎖 Honors and Awards
- Selected for Young Elite Scientists Sponsorship Program by CAST (2023)
- Outstanding Doctoral Dissertation Award of China Computer Federation (2023)
- Outstanding Doctoral Dissertation Award of CCF TCARCH (2023)
- IEEE TC Featured Paper of the Month (2022)
- 2022/2023年在第24、25和26届Graph 500排名中，SSSP性能蝉联全球第一、BFS性能全球第二
- 2021年在第18届Green Graph 500排名中，性能功耗比全球第一

# 📖 Educations
- 2017.09-2022.09, Ph.D Candidate in the School of Computer Science and Technology in Huazhong University of Science and Technology, China.
- 2013.09-2017.06, Bachelor in the School of Computer Science, China University of Geosciences (Wuhan), China.

# 💬 Invited Talks
- 2023.09, A Joint Workshop on Hot Topics on Big data and AI，“High-performance Graph Processing over Streaming Graphs”.
- 2023.08, HPC China 2023 “第二届高性能图计算优化技术” 论坛，报告：动态图计算优化技术研究.
- 2023.08, CCFSys 2023 “高性能图计算体系结构和系统软件” 论坛，论坛主席.
- 2022.12, CNCC 2022 “面向复杂图计算应用的新型高能效体系结构” 论坛，报告：拓扑驱动的动态图计算硬件加速机制研究.
- 2022.06, 鲲鹏开发者峰会 2022，报告：基于鲲鹏BoostKit，打造全球领先的图计算系统.
- 2019.08, HPC China 2019 “ 第五届HPC Plus论坛”，报告：面向并发图计算任务的存储系统.

# 💻 Internships
- 2019.05-2019.09, National University of Singapore (Advisor: [Prof. Bingsheng He](https://www.comp.nus.edu.sg/~hebs/research.html)), Singapore.

# 📝 Projects
- **CCF-蚂蚁科研基金**（主持） 高性能分布式图神经网络系统优化技术研究（No.RF20220211） 
- **之江实验室青年基金** （主持）图结构感知的高性能图处理优化技术研究（No.K2023PI0AA01）
- **博士后特别资助（站前）**（主持）高性能动态图处理系统关键技术研究（No.2023TQ0325）
- **国家重点研发计划项目**（核心骨干）面向图计算的通用计算机技术与系统（No.2018YFB1003500）
- **国家自然科学基金重点项目** （核心骨干） 面向大数据高效处理的体系结构与关键技术（No. 61832006）
- **国家自然科学基金** （核心骨干） 关联性感知的并发图计算系统优化机制研究 (No.6170050426)
- **国家自然科学基金** （核心骨干） 面向高并发图分析服务的运行时系统关键技术研究 (No.6207050010)
- **之江实验室开放课题** （核心骨干） 面向高并发图分析服务的运行时系统关键技术研究（No.2021KD0AB01）
- **之江实验室重大项目** （核心骨干） 高并发分布式图计算系统（No.2022PI0AC03）
- **华为联合实验室项目** （核心骨干） 异步动态图计算加速器设计（No.YBN2021035018A5）
- **华为联合实验室项目** （核心骨干）  面向大规模图分析和图神经网络的高性能统一计算框架（No.YBN2021035018A6）
- **华为海思项目** （核心骨干） 图计算在ATPG中的应用探索（No.YBN2020115040）
