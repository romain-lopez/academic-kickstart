---
title: "A joint model of RNA expression and surface protein abundance in single cells"
date: 2019-10-01
publishDate: 2024-01-30T02:25:59.517002Z
authors: ["Adam Gayoso", "<u>Romain Lopez</u>", "Zoë Steier", "Jeffrey Regier", "Aaron Streets", "Nir Yosef"]
publication_types: ["2"]
abstract: "Cellular indexing of transcriptomes and epitopes by sequencing (CITE-seq) combines unbiased single-cell transcriptome measurements with surface protein quantification comparable to flow cytometry, the gold standard for cell type identification. However, current analysis pipelines cannot address the two primary challenges of CITE-seq data: combining both modalities in a shared latent space that harnesses the power of the paired measurements, and handling the technical artifacts of the protein measurement, which is obscured by non-negligible background noise. Here we present Total Variational Inference (totalVI), a fully probabilistic end-to-end framework for normalizing and analyzing CITE-seq data, based on a hierarchical Bayesian model. In totalVI, the mRNA and protein measurements for each cell are generated from a low-dimensional latent random variable unique to that cell, representing its cellular state. totalVI uses deep neural networks to specify conditional distributions. By leveraging advances in stochastic variational inference, it scales easily to millions of cells. Explicit modeling of nuisance factors enables totalVI to produce denoised data in both domains, as well as a batch-corrected latent representation of cells for downstream analysis tasks."
featured: false
publication: "*Machine Learning in Computational Biology (MLCB)*"
tags: ["workshop"]
url_pdf: "https://www.biorxiv.org/content/10.1101/791947v1"
url_code: "https://github.com/adamgayoso/totalVI_reproducibility"
projects: ["scVI"]
---

