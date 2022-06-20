---
title: "Deep generative models for detecting differential expression in single cells"
date: 2019-10-01
publishDate: 2022-06-18T18:56:53.842570Z
authors: ["Pierre Boyeau", "<u>Romain Lopez</u>", "Jeffrey Regier", "Adam Gayoso", "Michael I. Jordan", "Nir Yosef"]
publication_types: ["2"]
abstract: "Detecting differentially expressed genes is important for characterizing subpopulations of cells. However, in scRNA-seq data, nuisance variation due to technical factors like sequencing depth and RNA capture efficiency obscures the underlying biological signal. First, we show that deep generative models, which combined Bayesian statistics and deep neural networks, better estimate the log-fold-change in gene expression levels between subpopulations of cells. Second, we use Bayesian decision theory to detect differentially expressed genes while controlling the false discovery rate. Our experiments on simulated and real datasets show that our approach out-performs state-of-the-art DE frameworks. Finally, we introduce a technique for improving the posterior approximation, and show that it also improves differential expression performance."
featured: false
publication: "*Machine Learning in Computational Biology (MLCB)*"
tags: ["workshop"]
url_pdf: "https://www.biorxiv.org/content/10.1101/794289v1"
url_code: "https://github.com/PierreBoyeau/lfc_estimation"
projects: ["scVI"]
---

