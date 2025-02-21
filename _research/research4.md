---
title: "Cloud-native radio access network (RAN) design"
excerpt: "Due to spatio-temporal variation of mobile subscriber’s data traffic requirements, traffic load experienced by ground base stations present at different cell sites exhibit highly dynamic behavior in traditional cellular systems. This non-uniform and dynamic traffic load leads to under utilization of the base station computing resources at cell sites. Cloud Radio Access Network (C-RAN) is an innovative architecture which addresses this issue and keeps the Total Cost of Ownership (TCO) under safe limit for cellular operators."
collection: research
---

## Overview
Due to spatio-temporal variation of mobile subscriber’s data traffic requirements, traffic load experienced by base stations present at different cell sites exhibit highly dynamic behavior in traditional cellular systems. This non-uniform and dynamic traffic load leads to under utilization of the base station computing resources at cell sites. Cloud Radio Access Network (C-RAN) is an innovative architecture which addresses this issue and keeps the Total Cost of Ownership (TCO) under safe limit for cellular operators. In C-RAN, the baseband processing units (BBUs) are segregated from cell sites and are pooled in a central cloud data center thereby facilitating shared access for a set of Remote Radio Heads (RRHs) present at cell sites. In order to truly exploit the benefits of C-RAN, the BBU pool deployed in the cloud has to efficiently serve clusters of RRHs (i.e., many-to-one mapping between RRHs and BBUs in the BBU pool) and thereby minimizing the required number of active BBUs.

<!-- <br/><img src='/images/UAV-BS-Prototype.png'><br/>
<img src='/images/UAV-BS-Arch.png'> -->

<p align="center">
  <img alt="Light" src="/images/CRAN1.png" width="45%">
&nbsp; &nbsp; &nbsp; &nbsp;
  <img alt="Dark" src="/images/CRAN2.png" width="45%">
</p>

## Relevant Publications

Debashisha Mishra, PC Amogh, Arun Ramamurthy, A Antony Franklin, Bheemarjuna Reddy Tamma, Load-Aware Dynamic RRH Assignment in Cloud Radio Access Networks, IEEE Wireless Communications and Networking Conference (WCNC), April 2016, Doha, Qatar

Debashisha Mishra, Himank Gupta, Bheemarjuna Reddy Tamma, A Antony Franklin, KORA: A Framework for Dynamic Consolidation & Relocation of Control Units in Virtualized 5G RAN, IEEE International Conference on Communications (ICC), Kansas City, MO, USA, 2018

S Sandeep Kumar, Raymond Knopp, Navid Nikaein, Debashisha Mishra, Bheemarjuna Reddy Tamma, A Antony Franklin, Kiran Kuchi, Rohit Gupta,FLEXCRAN: Cloud Radio Access Network Prototype using OpenAirInterface}, IEEE International Conference on COMmunication Systems & NETworkS (COMSNETS), Demos & Exhibits, January 2017, Bangalore, India

Debashisha Mishra, Himank Gupta, Mehul Sharma, Bheemarjuna Reddy Tamma, A Matching-theoretic Framework for Consolidation of Flexible Cloud-native Central Units in 5G-RAN, IEEE International Conference on Advanced Networks and Telecommunications Systems (ANTS), December 2019, Goa, India