# things-you-need-to-know-on-edge-computing
Publications on edge computing.


# Pre
主要包含一些概念知识普及，以及必要的基础知识点。BigData/Cloud 主要包含大数据、分
布式系统相关的文献或链接。Edge Computing主要包含文献综述，内容涉及当下研究的方向
、现状及挑战，同时会有一些应用案例帮助理解边缘计算给人民生活、工业制造、政府决策
等领域带来的变化以及新的可能。

## BigData/Cloud
1.	杜小勇, 卢卫, 张峰. 大数据管理系统的历史、现状与未来[J]. 软件学报, 2019, 30(01):130-144.

## Edge Computing
1.	施巍松, 王一帆. 边缘计算：现状与展望[J]. 计算机研究与发展, 计算机研究与发展, 
    2019, 56(1): 69.
2.	YU W, LIANG F, HE X等. A survey on the edge computing for the Internet of 
    Things[J]. IEEE Access, IEEE, 2017, 6: 6900–6919.
3.	BONOMI F, MILITO R, ZHU J等. Fog Computing and Its Role in the Internet of 
    Things[C]//Proceedings of the First Edition of the MCC Workshop on Mobile 
    Cloud Computing. Helsinki, Finland: ACM, 2012: 13–16.
4.	PORAMBAGE P, OKWUIBE J, LIYANAGE M等. Survey on Multi-Access Edge Computing
    for Internet of Things Realization[J]. IEEE Communications Surveys &amp; 
    Tutorials, Institute of Electrical and Electronics Engineers (IEEE), 2018, 
    20(4): 2961–2991.
5.	洪学海, 汪洋. 边缘计算技术发展与对策研究[J]. 中国工程科学, 2018, 20: 28–34.

# Special Topics
## Network

1.	VASILAKOS A V, LI Z, SIMON G等. Information centric network: Research 
    challenges and opportunities[J]. Journal of Network and Computer Applications,
    Elsevier BV, 2015, 52: 1–10.
   > 文章对ICN（数据中心网络）进行了解释与总结，ICN目的是解决TCP/IP不够灵活的痛
   > 点，本质思想是通过数据的名称来建立路由，即，将路由表中的IP替换为数据名称。
   > 适合解决异构网络融合的问题，异构网络虽然网络协议不同，但产生的数据却是不同的
   > 处理设备都认可的。同时ICN也存在一些挑战，比如安全问题，可以去文中慢慢挖掘。

2.	NGUYEN C, MEHTA A, KLEIN C等. Why cloud applications are not ready for the 
   edge (yet)[C]//Proceedings of the 4th ACM/IEEE Symposium on Edge Computing – 
   SEC’ 19. ACM Press, 2019.
   > 文章在探讨两个问题：
   > 1，cloud-native 应用利用边缘节点（Data centors）能降低多少端到端时延？
   > 2，cloud-native 应用应当如何开发来适应边缘计算？
   > 论文的实验思想值得借鉴，从网络沟通角度，对服务放在Edge端与Cloud端进行了考察，
   > 实验结果说明，多数情况下可能edge的速度并不如cloud快速。此外，用户对于低时延
   > 的要求，是指能完成处理完一个任务的要求，不是与edge、cloud首次建立会话所花费
   > 的时间。文章会让人思考，什么样的应用才适合边缘计算？读完文章后应该会有一个
   > 初步的答案。如果仅是对边缘的优势有一个粗略的认识，那么本文会给出优势背后的
   > 细节层次的介绍，有助于在以后开发出适合边缘计算的应用。

## Edge Nodes Topology
1.  > Jiang X, Shokri-Ghadikolaei H, Fodor G等. Low-Latency Networking: Where 
      Latency Lurks and How to Tame It[J]. Proceedings of the IEEE, Institute of
      Electrical and Electronics Engineers (IEEE), 2019, 107(2): 280–306.

2. > Xiang C, Wang X, Chen Q等. No-jump-into-latency in China's internet![A]. 
     Proceedings of the International Symposium on Quality of Service - IWQoS'19[C].
    ACM Press, 2019.
    > 文献`1`的列出一些关键领域的应用对时延、丢包率的要求，文献`2`会列出当前中国
    > 路由器与覆盖地理距离的关系（单个路由器覆盖约5km半径)，两篇文章将有助于理解
    > 不同的服务，边缘节点应该按什么样的密度、距离来部署。

