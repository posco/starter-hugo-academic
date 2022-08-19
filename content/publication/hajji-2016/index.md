---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Understanding the Performance of Low Power Raspberry Pi Cloud for Big Data
subtitle: ''
summary: ''
authors:
- Wajdi Hajji
- Fung Po Tso
tags:
- publications
categories: []
date: '2016-06-06'
lastmod: 2022-08-19T20:20:59+01:00
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
publishDate: '2022-08-19T19:28:45.850250Z'
publication_types:
- '2'
abstract: Nowadays, Internet-of-Things (IoT) devices generate data at high speed and
  large volume. Often the data require real-time processing to support high system
  responsiveness which can be supported by localised Cloud and/or Fog computing paradigms.
  However, there are considerably large deployments of IoT such as sensor networks
  in remote areas where Internet connectivity is sparse, challenging the localised
  Cloud and/or Fog computing paradigms. With the advent of the Raspberry Pi, a credit
  card-sized single board computer, there is a great opportunity to construct low-cost,
  low-power portable cloud to support real-time data processing next to IoT deployments.
  In this paper, we extend our previous work on constructing Raspberry Pi Cloud to
  study its feasibility for real-time big data analytics under realistic application-level
  workload in both native and virtualised environments. We have extensively tested
  the performance of a single node Raspberry Pi 2 Model B with httperf and a cluster
  of 12 nodes with Apache Spark and HDFS (Hadoop Distributed File System). Our results
  have demonstrated that our portable cloud is useful for supporting real-time big
  data analytics. On the other hand, our results have also unveiled that overhead
  for CPU-bound workload in virtualised environment is surprisingly high, at 67.2%.
  We have found that, for big data applications, the virtualisation overhead is fractional
  for small jobs but becomes more significant for large jobs, up to 28.6%.
publication: '*Electronics*'
doi: 10.3390/electronics5020029
url_pdf: https://www.poscotso.com/wp-content/uploads/2016/06/electronics-05-00029.pdf
---
