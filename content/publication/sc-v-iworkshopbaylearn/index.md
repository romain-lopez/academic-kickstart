---
title: "A deep generative model for gene expression profiles from single-cell RNA sequencing"
date: 2017-09-01
publishDate: 2024-01-30T02:25:59.519073Z
authors: ["<u>Romain Lopez</u>", "Jeffrey Regier", "Michael I. Jordan", "Nir Yosef"]
publication_types: ["2"]
abstract: "We propose a probabilistic model for interpreting gene expression levels that are observed through single-cell RNA sequencing. In the model, each cell has a low-dimensional latent representation. Additional latent variables account for technical effects that may erroneously set some observations of gene expression levels to zero. Conditional distributions are specified by neural networks, giving the proposed model enough flexibility to fit the data well. We use variational inference and stochastic optimization to approximate the posterior distribution. The inference procedure scales to over one million cells, whereas competing algorithms do not. Even for smaller datasets, for several tasks, the proposed procedure outperforms state-of-the-art methods like ZIFA and ZINB-WaVE."
featured: false
publication: "*Bay Area Machine Learning Symposium*"
tags: ["workshop"]
url_pdf: "https://arxiv.org/pdf/1709.02082.pdf"
url_code: "https://github.com/YosefLab/scvi-tools"
projects: ["scVI"]
---

