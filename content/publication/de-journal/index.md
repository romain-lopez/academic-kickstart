---
title: "An empirical Bayes method for differential expression analysis of single cells with deep generative models"
date: 2023-01-01
publishDate: 2024-01-30T02:25:59.510885Z
authors: ["Pierre Boyeau", "Jeffrey Regier", "Adam Gayoso", "Michael I. Jordan", "<u>Romain Lopez</u>*", "Nir Yosef*"]
publication_types: ["2"]
abstract: "Detecting differentially expressed genes is important for characterizing subpopulations of cells. In scRNA-seq data, however, nuisance variation due to technical factors like sequencing depth and RNA capture efficiency obscures the underlying biological signal. Deep generative models have been extensively applied to scRNA-seq data, with a special focus on embedding cells into a low-dimensional latent space and correcting for batch effects. However, little attention has been given to the problem of utilizing the uncertainty from the deep generative model for differential expression. Furthermore, the existing approaches do not allow controlling for the effect size or the false discovery rate. Here, we present lvm-DE, a generic Bayesian approach for performing differential expression from using a fitted deep generative model, while controlling the false discovery rate. We apply the lvm-DE framework to scVI and scSphere, two deep generative models. The resulting approaches outperform the state-of-the-art methods at estimating the log fold change in gene expression levels, as well as detecting differentially expressed genes between subpopulations of cells."
featured: false
publication: "*Proceedings of the National Academy of Sciences*"
tags: ["journal"]
url_pdf: "https://www.pnas.org/doi/10.1073/pnas.2209124120"
projects: ["scVI"]
---

