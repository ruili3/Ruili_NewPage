---
title: Efficient and Robust Structure-from-Motion
summary: This project improves the SFM by proposing efficient robust estimation method as well as a robust and accurate hybrid SFM pipeline.
tags: 
# - Deep Learning
date: "2018-12-15T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: ""
  focal_point: Smart

links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
Structure-from-motion (SFM) is a longstanding problem in 3D computer vision, it aims to recover 3D structure and camera poses given a set of images as input. Estimating 3D infomation from 2D data is a highly ambiguous problem. Due to the unsettled issues of feature matching as well as the complex estimation procedures, SfM may failed in some challenging scenarios due the lack of robustness. Moreover, it also brings computation burdens when more robust estimation modules is involved. 

In this project, we aim to address the challenges of structure-from-motion (SFM) in two aspects. Firstly, we focus on the outlier removal procedure in the SFM pipeline, we propose an efficient variant of RANSAC which adaptively incorporate new samples into estimation to improve the convergence speed of robust estimation. Then, we improve the conventional SFM by integrating the advantages of both incremental and global SFM, leading to a new type of robust and accruate hybrid SFM pipeline. Experimental results show the effectiveness of the proposed methods.

<!-- # Related Papers
1. [ARSAC: Efficient Model Estimation via Adaptively Ranked Sample Consensus](#publication/arsac-efficient-model-estimation-via-adaptively-ranked-sample-consensus)
2. [Robust and Accurate Hybrid Structure-From-Motion](#publication/arsac-efficient-model-estimation-via-adaptively-ranked-sample-consensus) -->