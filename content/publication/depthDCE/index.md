---
title: "Enhancing Self-supervised Monocular Depth Estimation via Incorporating Robust Constraints"
publication_types:
  - "1"
authors:
  - Rui Li
  - Xiantuo He
  - Yu Zhu
  - Xianjun Li
  - Jinqiu Sun
  - Yanning Zhang
publication: Proceedings of the 28th ACM International Conference on Multimedia 2020  
publication_short: ACM Multimedia 2020
abstract: Self-supervised depth estimation has shown great prospects in inferring 3D structures using purely unannotated images. However, its performance usually drops when trained on the images with changing brightness and moving objects. In this paper, we address this issue by enhancing the robustness of the self-supervised paradigm using a set of image-based and geometry-based constraints. Our contributions are threefold, 1) we propose a gradient-based robust photometric loss which restrains the false supervisory signals caused by brightness changes, 2) we propose to filter out the unreliable areas that violate the rigid assumption by a novel combined selective mask, which is computed on the forward pass of the network by leveraging the inter-loss consistency and the loss-gradient consistency, and 3) we constrain the motion estimation network to generate across-frame consistent motions via proposing a triplet-based cycle consistency constraint. Extensive experiments conducted on KITTI, Cityscape and Make3D datasets demonstrate the superiority of our method, that the proposed method can effectively handle complex scenes with changing brightness and object motions. Both qualitative and quantitative results show that the proposed method outperforms the state-of-the-art methods.
# links:
# - name: ""
#   url: ""
url_pdf: https://dl.acm.org/doi/abs/10.1145/3394171.3413706
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
  filename: featured.jpg
  focal_point: ""
  preview_only: false
date: 2020-10-12T12:00:00.000Z
---
