---
title: "A Deep Generative Model for Gene Expression profiles from Single-cell RNA Sequencing with Application to Differential Expression"
date: 2017-12-01
publishDate: 2020-10-01T15:29:16.483953Z
authors: ["<u>Romain Lopez</u>", "Jeffrey Regier", "Michael I. Jordan", "Nir Yosef"]
publication_types: ["2"]
abstract: "We propose a probabilistic model for interpreting gene expression levels that are observed through single-cell RNA sequencing. In the model, each cell has a low-dimensional latent representation. Additional latent variables account for technical effects that may erroneously set some observations of gene expression levels to zero. Conditional distributions are specified by neural networks, giving the proposed model enough flexibility to fit the data well. We use variational inference and stochastic optimization to approximate the posterior distribution. The inference procedure scales to over one million cells, whereas competing algorithms do not. Even for smaller datasets, for several tasks, the proposed procedure outperforms state-of-the-art methods like ZIFA and ZINB-WaVE. We also extend our framework to account for batch effects and other confounding factors, and propose a Bayesian hypothesis test for differential expression that outperforms DESeq2."
featured: false
publication: "*NeurIPS Machine Learning workshop in Computational Biology, <strong>Spotlight talk</strong> and Bay Area Machine Learning Symposium, <strong>Oral presentation</strong>*"
tags: ["workshop"]
url_pdf: "https://arxiv.org/pdf/1709.02082.pdf"
url_code: "https://github.com/YosefLab/scVI"
projects: ["scVI"]
---

