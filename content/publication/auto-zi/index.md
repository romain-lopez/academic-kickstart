---
title: "Detecting zero-inflated genes in single-cell transcriptomics data"
date: 2019-10-01
publishDate: 2024-01-30T02:25:59.516662Z
authors: ["Oscar Clivio", "<u>Romain Lopez</u>", "Jeffrey Regier", "Adam Gayoso", "Michael I. Jordan", "Nir Yosef"]
publication_types: ["2"]
abstract: "In single-cell RNA sequencing data, biological processes or technical factors may induce an overabundance of zero measurements. Existing probabilistic approaches to interpreting these data either model all genes as zero-inflated, or none. But the overabundance of zeros might be gene-specific. Hence, we propose the AutoZI model, which, for each gene, places a spike-and-slab prior on a mixture assignment between a negative binomial (NB) component and a zero-inflated negative binomial (ZINB) component. We approximate the posterior distribution under this model using variational inference, and employ Bayesian decision theory to decide whether each gene is zero-inflated. On simulated data, AutoZI outperforms the alternatives. On negative control data, AutoZI retrieves predictions consistent to a previous study on ERCC spike-ins and recovers similar results on control RNAs. Applied to several datasets and instances of the 10x Chromium protocol, AutoZI allows both biological and technical interpretations of zero-inflation. Finally, AutoZI's decisions on mouse embyronic stem-cells suggest that zero-inflation might be due to transcriptional bursting."
featured: false
publication: "*Machine Learning in Computational Biology (MLCB)*"
tags: ["workshop"]
url_pdf: "https://www.biorxiv.org/content/10.1101/794875v1"
url_code: "https://github.com/oscarclivio/AutoZI_reproducibility"
projects: ["scVI"]
---

