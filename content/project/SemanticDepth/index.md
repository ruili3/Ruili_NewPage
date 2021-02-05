---
title: Semantic-guided Depth Estimation
summary: In this project, we enhance the self-supervised depth estimation via an auxiliary semantic segmentation task.
tags: 
# - Deep Learning
date: "2020-12-01T00:00:00Z"

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
Despite the impressive results of self-supervised depth estimation, most current methods leverage only image representations to model image depth, and seldom consider how the semantic information can be utilized. Image semantics are, however, highly coupled with image preferences and scene depth. Therefore it’s necessary to introduce image semantics to assist in the estimation of depth.

In this project, we enhance the depth estimation by leveraing the advantages of semantic segmentation task. The semantic branch helps to improve the depth estimation in two aspects. First, the semantic segmentation network generates contextual feature representations, which can be utilized to improve depth representation. Meanwhile, the semantic segmentation provides object masks, with which the depth borders can be further refined. In this project, we explore the feature-level representation enhancement as well as the mask-based depth border refinement. 


>**Related Papers**
>1. [Semantic-Guided Representation Enhancement for Self-supervised Monocular Trained Depth Estimation](../../publication/SEEDepth/)
>1. [Learning Depth via Leveraging Semantics: Self-supervised Monocular Depth Estimation with Both Implicit and Explicit Semantic Guidance](../../publication/SemDepth/)