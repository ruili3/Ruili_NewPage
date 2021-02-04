---
title: "Semantic-Guided Representation Enhancement for Self-supervised Monocular Trained Depth Estimation"
publication_types:
  - "1"
authors:
  - Rui Li
  - Qing Mao
  - Pei Wang
  - Xiantuo He
  - Yu Zhu
  - Jinqiu Sun
  - Yanning Zhang
publication: arXiv preprint arXiv:2012.08048
publication_short: arXiv:2012.08048
abstract: Self-supervised depth estimation has shown its great effectiveness in producing high quality depth maps given only image sequences as input. However, its performance usually drops when estimating on border areas or objects with thin structures due to the limited depth representation ability. In this paper, we address this problem by proposing a semantic-guided depth representation enhancement method, which promotes both local and global depth feature representations by leveraging rich contextual information. In stead of a single depth network as used in conventional paradigms, we propose an extra semantic segmentation branch to offer extra contextual features for depth estimation. Based on this framework, we enhance the local feature representation by sampling and feeding the point-based features that locate on the semantic edges to an individual Semantic-guided Edge Enhancement module (SEEM), which is specifically designed for promoting depth estimation on the challenging semantic borders. Then, we improve the global feature representation by proposing a semantic-guided multi-level attention mechanism, which enhances the semantic and depth features by exploring pixel-wise correlations in the multi-level depth decoding scheme. Extensive experiments validate the distinct superiority of our method in capturing highly accurate depth on the challenging image areas such as semantic category borders and thin objects. Both quantitative and qualitative experiments on KITTI show that our method outperforms the state-of-the-art methods.
# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/pdf/2012.08048.pdf
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
date: 2020-12-15T12:00:00.000Z
---
