---
title: Blind Image Deblurring by Promoting Group Sparsity
publication_types:
  - "2"
authors:
  - Dong Gong
  - Rui Li
  - Yu Zhu
  - Haisen Li
  - Jinqiu Sun
  - Yanning Zhang
publication: Neurocomputing
publication_short: Neurocomputing
abstract: Blind image deblurring aims to recover the sharp image from a blurred
  observation, which is an ill-posed inverse problem. Proper image priors for
  the unknown variables (i.e. latent sharp image and blur kernel) are crucial.
  Abundant previous methods have shown the effectiveness of the sparsity-based
  priors on both image gradients and the blur kernel. The correlation among the
  elements of the sparse variables is paid less attention, however. In this
  paper, we propose to handle the blind image deblurring problem by promoting
  group sparsity. The proposed group sparsity priors are based on the fact that
  the nonzero elements of natural image gradients and blur kernels tend to
  cluster in structured group pattern. Based on the proposed priors, we
  introduce proper algorithms to iteratively update latent image gradients and
  blur kernel, respectively. The proposed algorithms preserve the salient
  structures and smooth the minor components in image gradients and restrict the
  blur kernel in a domain of dynamic group sparse vector. To illustrate the
  reliability of the proposed algorithm, we conduct experiments to analyze the
  properties of the regularizers and the convergence property of the proposed
  algorithm. Experiments with both quantitative and visual comparison further
  prove the effectiveness of the proposed method.
draft: false
featured: false
image:
  filename: gsdeblur.png
  focal_point: Smart
  preview_only: false
  caption: Visualization of the locally clustering group pattern for image gradients
date: 2018-06-01T12:57:00.000Z
---
