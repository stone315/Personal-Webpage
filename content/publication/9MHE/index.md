---
abstract: "Adaptive controllers on quadrotors typically rely on estimation of disturbances to ensure robust trajectory tracking. Estimating disturbances across diverse environmental contexts is challenging due to the inherent variability and uncertainty in the real world. Such estimators require extensive fine-tuning for a specific scenario, which makes them inflexible and brittle to changing conditions. Machine-learning approaches, such as training a neural network to tune the estimator’s parameters, are promising. However, collecting data across all possible environmental contexts is impossible. It is also inefficient as the same estimator parameters could work for ``nearby" contexts. In this paper, we present a sequential decision making strategy that decides which environmental contexts, using Bayesian Optimization with a Gaussian Process, to collect data from in order to ensure robust performance across a wide range of contexts. Our method, Contextual NeuroMHE, eliminates the need for exhaustive training across all environments while maintaining robust performance under different conditions. By enabling the neural network to adapt its parameters dynamically, our method improves both efficiency and generalization. Experimental results in various real-world settings demonstrate that our approach outperforms the prior work by 20.3% in terms of maximum absolute position error and can capture the variations in the environment  with a few carefully chosen contexts."
authors:
- admin
- Kasra Torshizi
- Khuzema Habib1
- Guangyao Shi
- Troi Williams1
- Pratap Tokekar
date: "2025-08-01T00:00:00Z"
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
publishDate: "2025-08-01T00:00:00Z"
slides: 
summary: "We present a sequential decision making strategy that decides which environmental contexts, using Bayesian Optimization with a Gaussian Process, to collect data from in order to ensure robust performance across a wide range of contexts."
tags:
- "Submitted to ICRA 2026"
title: "Contextual Neural Moving Horizon Estimation for Robust Quadrotor Control in Varying Conditions"
url_code: ""
url_dataset: ""
url_pdf: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
---
