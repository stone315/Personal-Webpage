---
abstract: "Multi-agent reinforcement learning (MARL) requires coordinated and stable policy updates among interacting agents. Heterogeneous-Agent Trust Region Policy Optimization (HATRPO) enforces per-agent trust region constraints using Kullback–Leibler (KL) divergence to stabilize training. However, assigning each agent the same KL threshold can lead to slow and locally optimal updates, especially in heterogeneous settings. To address this limitation, we propose two approaches for allocating the KL divergence threshold across agents: HATRPO-W, a Karush–Kuhn–Tucker-based (KKT-based) method that optimizes threshold assignment under global KL constraints, and HATRPO-G, a greedy algorithm that prioritizes agents based on improvement-to-divergence ratio. By connecting sequential policy optimization with constrained threshold scheduling, our approach enables more flexible and effective learning in heterogeneous-agent settings. Experimental results demonstrate that our methods significantly boost the performance of HATRPO, achieving faster convergence and higher final rewards across diverse MARL benchmarks. Specifically, HATRPO-W and HATRPO-G achieve comparable improvements in final performance, each exceeding 22.5\%. Notably, HATRPO-W also demonstrates more stable learning dynamics, as reflected by its lower variance."
authors:
- admin
- Guangyao Shi
- Pratap Tokekar
date: "2025-10-01T00:00:00Z"
doi: ""
featured: true
image:
  caption: ''
  focal_point: ""
  preview_only: false
links:
- name: Web
  url: ""
projects:
- BS
publication: ""
publication_short: ""
publication_types:
- "1"
publishDate: "2025-10-01T00:00:00Z"
slides: 
summary: "We propose two approaches for allocating the KL divergence threshold across agents: HATRPO-W, a Karush–Kuhn–Tucker-based (KKT-based) method that optimizes threshold assignment under global KL constraints, and HATRPO-G, a greedy algorithm that prioritizes agents based on improvement-to-divergence ratio."
tags:
- "Submitted to AAMAS 2026"
title: "Multi-Agent Trust Region Policy Optimisation: A Joint Constraint Approach"
url_code: ""
url_dataset: ""
url_pdf: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
---
