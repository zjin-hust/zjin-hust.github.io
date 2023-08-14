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

之江实验室图计算研究中心/华中科技大学计算机科学与技术学院助理研究员，2022年9月在华中科技大学获得计算机系统结构博士学位，入选2023年度“CCF体系结构优秀博士学位论文激励计划”。主要研究面向图计算的高性能体系结构和系统软件，相关成果在ISCA、SC、DAC、ACM TOS/TACO、IEEE TC/TKDE/TBD等会议和期刊上发表或录用学术论文10余篇，入选CCF A类期刊IEEE TC的Featured Paper of the Month等，研发的图计算引擎在图计算性能权威榜单Green Graph 500和Graph 500排名中多次位列第一，相关技术将华为鲲鹏并发图计算性能提升了2300余倍，获第七届“互联网+”产业命题赛道全国金奖，入选第八届“长江学子”大学生就业创业人物“开拓创新类”，目前正在主持CCF-蚂蚁科研基金、之江实验室青年基金和第5批博士后特别资助（站前）等。

My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).

# 📝 发表论文 
- **[DAC]** **<ins>Jin Zhao</ins>**, Yu Zhang, Jian Cheng, Yiyang Wu, Chuyue Ye, Hui Yu, Zhiying Huang, Hai Jin, Xiaofei Liao, Lin Gu, Haikun Liu. SaGraph: A Similarity-aware Hardware Accelerator for Temporal Graph Processing. In ***Proceedings of the 60th Design Automation Conference***, 2023.
- **[TACO]** **<ins>Jin Zhao</ins>**, Yu Zhang, Ligang He, Qikun Li, Xiang Zhang, Hui Yu, Xiaofei Liao, Hai Jin, Lin Gu, Haikun Liu, Bingsheng He, Ji Zhang, Xianzheng Song, Lin Wang, Jun Zhuo. GraphTune: An Efficient Dependency-Aware Substrate to Alleviate Irregularity in Concurrent Graph Processing.  ***ACM Transactions on Architecture and Code Optimization***, 2023.
- **[ISCA]** **<ins>Jin Zhao</ins>**, Yun Yang, Yu Zhang, Xiaofei Liao, Lin Gu, Ligang He, Bingsheng He, Hai Jin, Haikun Liu, Xinyu Jiang, Hui Yu. TDGraph: A Topology-Driven Accelerator for High-Performance Streaming Graph Processing. In ***Proceedings of the 2022 IEEE/ACM International Symposium on Computer Architecture***, 2022.
- **[TC]** Xiaofei Liao, **<ins>Jin Zhao</ins>**, Yu Zhang, Bingsheng He, Ligang He, Hai Jin, Lin Gu. A Structure-aware Storage Optimization for Out-of-Core Concurrent Graph Processing. ***IEEE Transactions on Computer*** ```Featured Paper of the Month```, 2022.
- **[SC]** **<ins>Jin Zhao</ins>**, Yu Zhang, Xiaofei Liao, Ligang He, Bingsheng He, Hai Jin, Haikun Liu. LCCG: A Locality-centric Hardware Accelerator for High Throughput of Concurrent Graph Processing. In ***Proceedings of the 2021 International Conference for High Performance Computing, Networking, Storage, and Analysis***, 2021.
- **[SC]** **<ins>Jin Zhao</ins>**, Yu Zhang, Xiaofei Liao, Ligang He, Bingsheng He, Hai Jin, Haikun Liu, Yicheng Chen. GraphM: An Efficient Storage System for High Throughput of Concurrent Graph Analytics.  In ***Proceedings of the 2019 International Conference for High Performance Computing, Networking, Storage, and Analysis***, 2019.
- **[DAC]** Hao Qi, Yu Zhang, Ligang He, Kang Luo, Jun Huang, Haoyu Lu, **<ins>Jin Zhao</ins>**, Hai Jin. PSMiner: A Pattern-Aware Accelerator for High-Performance Streaming Graph Pattern Mining. In ***Proceedings of the 60th Design Automation Conference***, 2023.
- **[TACO]** Hui Yu, Yu Zhang, **<ins>Jin Zhao</ins>**, Yujian Liao, Zhiying Huang, Donghao He, Lin Gu,Hai Jin, Xiaofei Liao, Haikun Liu. RACE: An Efficient Redundancy-aware Accelerator for Dynamic Graph Neural Network. ***ACM Transactions on Architecture and Code Optimization***, 2023.
- **[TC]** Hai Jin, Dan Chen, Long Zheng, Yu Huang, Pengcheng Yao, **<ins>Jin Zhao</ins>**, Xiaofei Liao, Wenbin Jiang. Accelerating Graph Convolutional Networks Through a PIM-Accelerated Approach. ***IEEE Transactions on Computers***, 2023.
- **[TKDE]** Yu Zhang, Yuxuan Liang, **<ins>Jin Zhao</ins>**, Fubing Mao, Lin Gu, Xiaofei Liao, Hai Jin, Haikun Liu, Song Guo, Yangqing Zeng, Hang Hu. EGraph: efficient concurrent GPU-based dynamic graph processing. ***IEEE Transactions on Knowledge and Data Engineering***, 2023.
- **[JCST]** Hui Yu, Xinyu Jiang, **<ins>Jin Zhao</ins>**, Hao Qi, Yu Zhang, Xiaofei Liao, Haikun Liu, Fubing Mao, Hai Jin. Toward High-Performance Delta-Based Iterative Processing with a Group-Based Approach. ***Journal of Computer Science and Technology***, 2022.
- **[TBD]** Beibei Si, Yuxuan Liang,  **<ins>Jin Zhao</ins>**, Yu Zhang, Xiaofei Liao, Hai Jin, Haikun Liu, Lin Gu. GGraph: An Efficient Structure-aware Approach for Iterative Graph Processing.  ***IEEE Transactions on Big Data***, 2022.
- **[TOS]** Yu Zhang, **<ins>Jin Zhao</ins>**, Xiaofei Liao, Hai Jin, Lin Gu, Haikun Liu, Bingsheng He, Ligang He. CGraph: A Distributed Storage and Processing System for Concurrent Iterative Graph Analysis Jobs. ***ACM Transactions on Storage***, 2019.
- **[中国科学: 信息科学]** **<ins>赵进</ins>**, 姜新宇, 张宇, 廖小飞, 金海, 刘海坤, 杨赟, 张吉, 王彪, 余婷. 一种高效的面向高并发图分析任务的存储系统. ***中国科学: 信息科学***, 2022.
- **[中国科学:信息科学]** 毛伏兵, 彭达, 张宇, 廖小飞, 姜新宇,杨赟, 金海, **<ins>赵进</ins>**, 刘海坤, 王柳峥. 图计算在ATPG中的应用探究. ***中国科学: 信息科学***, 2023.
- **[中国科学:信息科学]** 廖小飞, 陈意诚, 张宇, 金海, 刘海坤, **<ins>赵进</ins>**. 一种高效的面向动态有向图的增量强连通分量算法. ***中国科学:信息科学***, 2019.

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
