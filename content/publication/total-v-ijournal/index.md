---
title: "Joint probabilistic modeling of single-cell multi-omic data with totalVI"
date: 2021-02-01
publishDate: 2024-01-30T02:25:59.514882Z
authors: ["Adam Gayoso*", "Zoë Steier*", "<u>Romain Lopez</u>", "Jeffrey Regier", "Kristopher L. Nazor", "Aaron Streets", "Nir Yosef"]
publication_types: ["2"]
abstract: "The paired measurement of RNA and surface protein abundance in single cells with CITE-seq is a promising approach to connect transcriptional variation with cell phenotypes and functions. However, each data modality exhibits unique technical biases, making it challenging to conduct a joint analysis and combine these two views into a unified representation of cell state. Here we present Total Variational Inference (totalVI), a framework for the joint probabilistic analysis of paired RNA and protein data from single cells. totalVI probabilistically represents the data as a composite of biological and technical factors such as limited sensitivity of the RNA data, background in the protein data, and batch effects. To evaluate totalVI, we performed CITE-seq on immune cells from murine spleen and lymph nodes with biological replicates and with different antibody panels measuring over 100 surface proteins. With this dataset we demonstrate that totalVI provides a cohesive solution for common analysis tasks like the integration of datasets with matched or unmatched protein panels, dimensionality reduction, clustering, evaluation of correlations between molecules, and differential expression testing. totalVI enables scalable, end-to-end analysis of paired RNA and protein data from single cells and is available as open-source software."
featured: false
publication: "*Nature Methods*"
tags: ["journal"]
url_pdf: "https://www.nature.com/articles/s41592-020-01050-x"
url_code: "https://github.com/YosefLab/scVI"
projects: ["scVI"]
---

