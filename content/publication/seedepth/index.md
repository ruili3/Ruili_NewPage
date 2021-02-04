---
title: Robust and Accurate Hybrid Structure-From-Motion
publication_types:
  - "1"
authors:
  - Rui Li
  - Dong Gong
  - Jinqiu Sun
  - Yu Zhu
  - Ziwei Wei
  - Yanning Zhang
publication: 2019 IEEE International Conference on Image Processing (ICIP)
publication_short: ICIP 2019
abstract: In this paper, we propose a hybrid Structure-from-Motion scheme which
  combines the strength of both global and local incremental SfM methods to get
  a drift-free and accurate estimation with lower time consumption. More
  specifically, we propose to construct a robust maximum leaf spanning tree
  (RMLST) from the initial scene graph and further expand it to a robust graph
  (RG) to grasp the global picture of camera distribution and scene structure.
  Then the views in the robust graph are solved in global manner as an initial
  estimation. After that, the remaining views are estimated with the proposed
  community-based local incremental approach to guarantee local accuracy and
  scalability. Bundle adjustment is conducted to optimize the estimation.
  Experiments show that our method is robust and free from the scene drift as
  global SfM, and shows much better efficiency than incremental approaches.
  Besides, our algorithm achieves higher accuracy compared with the
  state-of-the-art methods.

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/abstract/document/8803814
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

draft: false
featured: false
image:
  # filename: pipeline_icip.png
  focal_point: ""
  preview_only: false
  caption: Pipiline of the method.
date: 2019-10-15T01:41:00.000Z
---
