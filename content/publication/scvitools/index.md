---
title: "A Python library for probabilistic analysis of single-cell omics data"
date: 2022-03-01
publishDate: 2022-06-18T18:56:53.835039Z
authors: ["Adam Gayoso*", "<u>Romain Lopez</u>*", "Galen Xing*", "Pierre Boyeau", "Katherine Wu", "Michael Jayasuriya", "Edouard Mehlman", "Maxime Langevin", "Yining Liu", "Jules Samaran", "Gabriel Misrachi", "Achille Nazaret", "Oscar Clivio", "Chenling Xu", "Tal Ashuach", "Mariano Gabitto", "Mohammad Lotfollahi", "Valentine Svensson", "Eduardo da Veiga Beltrame", "Vitalii Kleshchevnikov", "Carlos Talavera-Lopez", "Lior Pachter", "Fabian J Theis", "Aaron Streets", "Michael I. Jordan", "Jeffrey Regier", "Nir Yosef"]
publication_types: ["2"]
abstract: "Probabilistic models have provided the underpinnings for state-of-the-art performance in many single-cell omics data analysis tasks, including dimensionality reduction, clustering, differential expression, annotation, removal of unwanted variation, and integration across modalities. Many of the models being deployed are amenable to scalable stochastic inference techniques, and accordingly they are able to process single-cell datasets of realistic and growing sizes. However, the community-wide adoption of probabilistic approaches is hindered by a fractured software ecosystem resulting in an array of packages with distinct, and often complex interfaces. To address this issue, we developed scvi-tools (https://scvi-tools.org), a Python package that implements a variety of leading probabilistic methods. These methods, which cover many fundamental analysis tasks, are accessible through a standardized, easy-to-use interface with direct links to Scanpy, Seurat, and Bioconductor workflows. By standardizing the implementations, we were able to develop and reuse novel functionalities across different models, such as support for complex study designs through nonlinear removal of unwanted variation due to multiple covariates and reference-query integration via scArches. The extensible software building blocks that underlie scvi-tools also enable a developer environment in which new probabilistic models for single cell omics can be efficiently developed, benchmarked, and deployed. We demonstrate this through a code-efficient reimplementation of Stereoscope for deconvolution of spatial transcriptomics profiles. By catering to both the end user and developer audiences, we expect scvi-tools to become an essential software dependency and serve to formulate a community standard for probabilistic modeling of single cell omics."
featured: true
publication: "*Nature Biotechnology*"
tags: ["journal", "featured"]
url_pdf: "https://www.nature.com/articles/s41587-021-01206-w"
projects: ["scVI"]
---

