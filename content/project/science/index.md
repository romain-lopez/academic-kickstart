---
title: Approximate Bayesian Inference for Science
summary: Opportunities and barriers at the interface between machine learning and science. Disentanglement, decision-making, interpretability, etc.
tags:
- Deep Generative Models
- Scientific Discoveries
- Molecular Biology
date: "2020-07-07T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Three practical examples of latent variable model design for science
  focal_point: Smart

links:
# - icon: github
#  icon_pack: fab
#  name: Contribute
#  link: https://github.com/YosefLab/scVI
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: 
---

Linear models and all their extensions (linear mixed models, GLMs, matrix factorization) have many advantages. First, reliable inference procedures, sometimes with guarantee of convergence and associated code are often widely available for those models. Second, these simple models are interpretable in the sense that it is possible to know which covariate is most associated with a certain target. Often, there are also direct connections to hypothesis testing.

To go beyond conjugacy and linearity, users of deep generative models sometimes sacrifice part of those benefits. In these manuscripts, we study two practical problems that emerged with the use of variational autoencoders: disentanglement of latent variables as well as hypothesis testing (in the more general context of decision-making). We also review recent advances and challenges of applying deep generative models for scientific discoveries in molecular biology applications. 

