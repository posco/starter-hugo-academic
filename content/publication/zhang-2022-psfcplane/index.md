---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'pSFC: Fine-grained composition of service function chains in the programmable
  data plane'
subtitle: ''
summary: ''
authors:
- X Zhang
- L Cui
- FP Tso
tags: []
categories: []
date: '2022-07-01'
lastmod: 2022-08-19T20:20:47+01:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-08-19T19:28:23.387677Z'
publication_types:
- '1'
abstract: Dynamic service function chains (SFC) are enabled by network function virtualization
  on general purpose servers. The emergence of programmable data planes (PDP) has
  offered a new way for the deployment of SFC. However, the implementation of network
  functions is constrained by resource limitations in PDPs (e.g., compute and memory
  resource). Moreover, most of existing works do not consider the optimization of
  state information (e.g., registers), which is essential for stateful network functions.
  In this paper, we propose pSFC which provides a fine-grained SFC deployment scheme
  in the PDP to tackle the problem. We first model network functions as control flow
  graphs (CFG) and the process of deployment as a one big switch (OBS) problem, and
  then propose an ILP (Integer Linear Programming) model for resource optimization
  for the OBS problem, which is NP-hard. To solve this problem efficiently, pSFC first
  composes multiple SFCs for eliminating redundant resources, decomposes the compound
  CFG based on the resource limitation per stage, and finally maps OBS into the substrate
  network. We have implemented pSFC in both bmv2 software switch and P4 hardware switch
  (i.e., Intel Tofino). Evaluation shows that pSFC reduces switch costs 45.7% and
  average latency 15% while providing the correctness of the process of SFC.
publication: '**'
doi: 10.1109/CCGrid54584.2022.00058
links:
- name: URL
  url: https://doi.org/10.1109/CCGrid54584.2022.00058
---
