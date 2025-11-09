---
abstract: "In a standard navigation pipeline, a robot localizes at every time step to lower navigational errors. However, in some scenarios, a robot needs to selectively localize when it is expensive to obtain observations. For example, an underwater robot surfacing to localize too often hinders it from searching for critical items underwater, such as black boxes from crashed aircraft. On the other hand, if the robot never localizes, poor state estimates cause failure to find the items due to inadvertently leaving the search area or entering hazardous, restricted areas. Motivated by these scenarios, we investigate approaches to help a robot determine ``when to localize?'' We formulate this as a bi-criteria optimization problem: minimize the number of localization actions while ensuring the probability of failure (due to collision or not reaching a desired goal) remains bounded. In recent work, we showed how to formulate this active localization problem as a constrained Partially Observable Markov Decision Process (POMDP), which was solved using an online POMDP solver. However, this approach is too slow and requires full knowledge of the robot transition and observation models. In this paper, we present RiskRL, a constrained Reinforcement Learning (RL) framework that overcomes these limitations. RiskRL uses particle filtering and recurrent Soft Actor-Critic network to learn a policy that minimizes the number of localizations while ensuring the probability of failure constraint is met. Our numerical experiments show that RiskRL learns a robust policy that leads to at least a 26% increase in success rates when traversing unseen test environments."
authors:
- admin
- Kasra Torshizi
- Troi Williams
- Pratap Tokekar
date: "2024-10-01T00:00:00Z"
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
publishDate: "2024-10-01T00:00:00Z"
slides: 
summary: "We present RiskRL, a constrained Reinforcement Learning (RL) framework that overcomes these limitations. RiskRL uses particle filtering and recurrent Soft Actor-Critic network to learn a policy that minimizes the number of localizations while ensuring the probability of failure constraint is met."
tags:
- "ACC 2026"
title: "When to Localize? A Risk-Constrained  Reinforcement Learning Approach"
url_code: ""
url_dataset: ""
url_pdf: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
---
