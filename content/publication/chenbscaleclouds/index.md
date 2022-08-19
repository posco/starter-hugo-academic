---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'B-Scale: Bottleneck-aware VNF scaling and flow routing in edge clouds'
subtitle: ''
summary: ''
authors:
- C Chen
- L Nagel
- L Cui
- FP Tso
tags: []
categories: []
date: -01-01
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
publishDate: '2022-08-19T19:28:23.098192Z'
publication_types:
- '1'
abstract: With the ever-growing demand for low-latency network applications, edge
  computing emerges as a new paradigm that provides computation and storage resources
  in close proximity to end-users. Many research efforts have resorted to network
  function virtualization, wherein network applications are provisioned as service
  function chains at edge clouds. However, due to the traffic dynamics and limited
  resource capacity at the network edge, how to efficiently embed service chains with
  latency optimization and resource efficiency remains as a challenging problem. As
  most existing research efforts largely overlook the bottlenecked resources of VNFs
  in the VNF scaling, we seek a more realistic approach to provisioning VNF instances
  across multiple edge clouds. Also, given the limited resources at the edge, it is
  of significant importance to improve the VNF utilization rate. Specifically, we
  formulate the VNF scaling problem as an integer linear programming (ILP) problem,
  aiming to minimize the endto-end latency for service function chains. To solve this
  problem, we devise a novel bottleneck-aware algorithm that manages the number and
  deployment of newly created instances. After that, we propose an online algorithm
  for traffic steering to improve the utilization rates of VNF instances and avoid
  congestion on hotspot links. The proposed algorithm is shown to provide good performance
  by trace-driven simulation in real-world topologies.
publication: '**'
links:
- name: URL
  url: https://ieeexplore.ieee.org/Xplore/home.jsp
---
