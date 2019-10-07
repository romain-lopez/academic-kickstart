---
title: "A joint model of unpaired data from scRNA-seq and spatial transcriptomics for imputing missing gene expression measurements"
date: 2019-06-01
publishDate: 2019-10-07T20:56:52.539058Z
authors: ["<u>Romain Lopez</u>", "Achille Nazaret*", "Maxime Langevin*", "Jules Samaran*", "Jeffrey Regier*", "Michael I Jordan", "Nir Yosef"]
publication_types: ["2"]
abstract: "Spatial studies of transcriptome provide biologists with gene expression maps of heterogeneous and complex tissues. However, most experimental protocols for spatial transcriptomics suffer from the need to select beforehand a small fraction of genes to be quantified over the entire transcriptome. Standard single-cell RNA sequencing (scRNA-seq) is more prevalent, easier to implement and can in principle capture any gene but cannot recover the spatial location of the cells. In this manuscript, we focus on the problem of imputation of missing genes in spatial transcriptomic data based on (unpaired) standard scRNA-seq data from the same biological tissue. Building upon domain adaptation work, we propose gimVI, a deep generative model for the integration of spatial transcriptomic data and scRNA-seq data that can be used to impute missing genes. After describing our generative model and an inference procedure for it, we compare gimVI to alternative methods from computational biology or domain adaptation on real datasets and outperform Seurat Anchors, Liger and CORAL to impute held-out genes."
featured: false
publication: "*ICML Workshop in Computational Biology, <strong>Spotlight talk</strong>, <strong>Best student poster award</strong>*"
tags: ["workshop"]
url_pdf: "https://arxiv.org/pdf/1905.02269.pdf"
url_code: "https://github.com/YosefLab/scVI"
---

