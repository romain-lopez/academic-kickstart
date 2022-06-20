---
title: Structured Counterfactual Inference
summary: Several practical instances of batch learning from bandit feedback with added structure. Collaborations with Ant Financial Services & Amazon.com Inc.
tags:
- Deep Generative Models
- Variational Inference
- scRNA-seq
date: "2020-07-07T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Can we get better trade-offs by incorporating more structure into counterfactual learning algorithms?
  focal_point: Smart

links:
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

In batch learning from bandit feedback, we observe a context (e.g., some covariates describing a patient or a customer), choose an action (e.g., a treatment or a recommendation) and observe an outcome (e.g., treatment effect or a proxy for user experience). However, we may only observe the effects of a logging policy, that we hope to improve over. Dealing with biases and variance for offline policy learning is a challenging setting.

We study two specific scenarios of policy optimization in which additional structure (e.g., monotonicity or reward sparsity) can be exploited to provide better bias-variance trade-offs. 

 
