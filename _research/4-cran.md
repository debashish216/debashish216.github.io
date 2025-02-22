---
title: "Cloud-native and virtualized radio access network (RAN)"
excerpt: "This topic presents a cloud-native and virtualized Radio Access network (C-RAN) architecture considering the spatio-temporal traffic heterogeneity exhibited at Remote Radio Units (RRUs)."
collection: research
---

## Overview
Due to spatio-temporal variation of mobile subscriber’s data traffic requirements, traffic load experienced by base stations present at different cell sites exhibit highly dynamic behavior in traditional cellular systems. This non-uniform and dynamic traffic load leads to under utilization of the base station computing resources at cell sites. Cloud Radio Access Network (C-RAN) is an innovative architecture which addresses this issue and keeps the Total Cost of Ownership (TCO) under safe limit for cellular operators. In C-RAN, the baseband processing units (BBUs) are segregated from cell sites and are pooled in a central cloud data center thereby facilitating shared access for a set of Remote Radio Heads (RRHs) present at cell sites. In order to truly exploit the benefits of C-RAN, the BBU pool deployed in the cloud has to efficiently serve clusters of RRHs (i.e., many-to-one mapping between RRHs and BBUs in the BBU pool) and thereby minimizing the required number of active BBUs.

We investigated the dynamic RRH-BBU mapping problem in C-RAN and studied the multiplexing gains achived by pooling BBUs in centralized cloud servers. Furthermore, a real-world testbed has been setup using an open-source implementation of 3GPP compliant cellular stack, OpenAirInterface (OAI) along with USRP-B210 SDR and commercial general purpose processor (GPP) servers. The deployment of the centralized CU on a remote server, and the RRUs, connected over Ethernet fronthaul is demonstrated.

<img src='/images/CRAN3.png'>


### Relevant Publications

* **Load-Aware Dynamic RRH Assignment in Cloud Radio Access Networks**\
Debashisha Mishra, PC Amogh, Arun Ramamurthy, A Antony Franklin, Bheemarjuna Reddy Tamma\
IEEE Wireless Communications and Networking Conference (WCNC), April 2016, Doha, Qatar

* **KORA: A Framework for Dynamic Consolidation & Relocation of Control Units in Virtualized 5G RAN**\
Debashisha Mishra, Himank Gupta, Bheemarjuna Reddy Tamma, A Antony Franklin\
IEEE International Conference on Communications (ICC), Kansas City, MO, USA, 2018

* **FLEXCRAN: Cloud Radio Access Network Prototype using OpenAirInterface**\
S Sandeep Kumar, Raymond Knopp, Navid Nikaein, Debashisha Mishra, Bheemarjuna Reddy Tamma, A Antony Franklin, Kiran Kuchi, Rohit Gupta\
IEEE International Conference on COMmunication Systems & NETworkS (COMSNETS), Demos & Exhibits, January 2017, Bangalore, India

* **A Matching-theoretic Framework for Consolidation of Flexible Cloud-native Central Units in 5G-RAN**\
Debashisha Mishra, Himank Gupta, Mehul Sharma, Bheemarjuna Reddy Tamma\
IEEE International Conference on Advanced Networks and Telecommunications Systems (ANTS), December 2019, Goa, India
