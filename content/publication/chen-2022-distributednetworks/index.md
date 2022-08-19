---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Distributed federated service chaining: A scalable and cost-aware approach
  for multi-domain networks'
subtitle: ''
summary: ''
authors:
- C Chen
- L Nagel
- L Cui
- FP Tso
tags: []
categories: []
date: '2022-05-01'
lastmod: 2022-08-19T20:20:46+01:00
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
publishDate: '2022-08-19T19:28:22.577190Z'
publication_types:
- '2'
abstract: Future networks are expected to support cross-domain, cost-aware and fine-grained
  services in an efficient and flexible manner. Service Function Chaining (SFC) has
  been introduced as a promising approach to deliver these services. In the literature,
  centralized resource orchestration is usually employed to process SFC requests and
  manage computing and network resources. However, centralized approaches inhibit
  the scalability and domain autonomy in multi-domain networks. They also neglect
  location and hardware dependencies of service chains. In this paper, we propose
  Distributed Federated Service Chaining (DFSC), a framework for orchestrating and
  maintaining SFC placement in a distributed fashion while sharing only a minimal
  amount of domain information and control. First, a deployment cost minimization
  problem is formulated as an Integer Linear Programming (ILP) problem with fine-grained
  constraints for location and hardware dependencies. We show that this problem is
  NP-hard. Then, a placement algorithm is devised to use information only on inter-domain
  paths and border nodes. Our extensive experimental results demonstrate that DFSC
  efficiently optimizes the deployment cost, supports domain autonomy and enables
  faster decision-making. The results also show that DFSC finds solutions within a
  factor 1.15 of the optimal solution on average. Compared to a centralized approach
  in the literature, DFSC reduces the deployment cost by up to 20% and uses 70% less
  decision-making time.
publication: '*Computer Networks*'
doi: 10.1016/j.comnet.2022.109044
links:
- name: URL
  url: https://doi.org/10.1016/j.comnet.2022.109044
---
