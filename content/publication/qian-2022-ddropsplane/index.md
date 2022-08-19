---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'dDrops: Detecting silent packet drops on programmable data plane'
subtitle: ''
summary: ''
authors:
- M Qian
- L Cui
- X Zhang
- FP Tso
- Y Deng
tags: []
categories: []
date: '2022-07-01'
lastmod: 2022-08-19T20:28:22+01:00
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
publishDate: '2022-08-19T19:28:22.435529Z'
publication_types:
- '2'
abstract: Silent packet drops are common in data center networks, and are a major
  cause of network performance anomalies (NPAs) that have significant impacts on application
  performance and network management. However, existing solutions using coarse-grained
  statistics and flow-level telemetry either fail to provide precise location of packet
  drops or incur large overhead. This paper presents dDrops, a packet-level telemetry
  based on programmable data plane to detect and retrieve details of silent packet
  drops immediately when they happen. dDrops can dynamically adapt to varying ratios
  of silent packet drops for different ports on a switch to improve performance of
  silent packet drops detection. Moreover, a dynamic memory management scheme is also
  designed to efficiently use the limited memory on the data plane of switch. dDrops
  has been implemented on both P4 hardware programmable switches (based on Intel Tofino
  ASIC) and BMv2. Extensive experiment results show that dDrops is able to detect
  and locate the silent packet drops within 5 ms (including detailed information of
  dropped packets), and reduce the memory consumption by up to 50%.
publication: '*Computer Networks*'
doi: 10.1016/j.comnet.2022.109171
links:
- name: URL
  url: https://doi.org/10.1016/j.comnet.2022.109171
---
