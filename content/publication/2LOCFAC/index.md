---
abstract: "In this work, we present a novel cooperative multi-agent reinforcement learning method called Locality based Factorized Multi-Agent Actor-Critic (Loc-FACMAC). The existing state-of-the-art algorithms, such as FACMAC, rely on the global reward information for critic training. However, in a distributed multi-agent system, the global reward is overgeneralized. The global reward cannot accurately reflect the influence of individual agents' actions, resulting in the mixer's poor performance in assigning credit. We introduce the idea of locality into critic learning to connect the strongly related agents into partitions. Agents in the same partition have a more significant impact retained within the partition itself. Thus, agents learning from the local reward can provide a more precise evaluation of the policy. This technique prevents the agent using information from unrelated agents and also helps to deal with the curse of dimensionality due to multiple agents. Loc-FACMAC further improves the efficiency of learning by introducing locality to the actor update as well. We evaluate the performance of Loc-FACMAC on three environments: Multi-cartpole, the StarCraft Multi-Agent Challenge, and Bounded-Cooperative-Navigation. We explore the impact of partition sizes on the performance and compare the result with baseline MARL algorithms such as LOMAQ, FACMAC, and QMIX. The experiments reveal that, if the locality structure is defined properly, Loc-FACMAC outperforms these baseline algorithms up to 45% , indicating that exploiting the locality structure in the actor-critic framework improves the MARL performance."
authors:
- admin
- Amrit Singh Bedi
- Anjon Basak
- Ellen Novoseller
- Nick Waytowich
- Priya Narayanan
- Dinesh Manocha
- Pratap Tokekar
date: ""
doi: ""
featured: true
image:
  caption: ''
  focal_point: ""
  preview_only: false
links: ""
projects:
- BS
publication: ""
publication_short: ""
publication_types:
- "2"
publishDate: ""
slides: 
summary: We present a novel cooperative multi-agent reinforcement learning method called Locality based Factorized Multi-Agent Actor-Critic (Loc-FACMAC).
tags:
- "Under Review"
title: "Loc-FACMAC : Locality Based Factorized Multi-Agent Actor-Critic Algorithm for Cooperative Tasks"
url_code: ""
url_dataset: ""
url_pdf: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
---
