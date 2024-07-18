---
title: "A Supervised Contrastive Framework for Learning Disentangled Representations of Cell Perturbation Data"
date: 2023-12-01
publishDate: 2024-01-30T02:25:59.509152Z
authors: ["Xinming Tu", "Jan-Christian Hutter", "Zitong Jerry Wang", "Takamasa Kudo", "Aviv Regev", "<u>Romain Lopez</u>"]
publication_types: ["2"]
abstract: "CRISPR technology, combined with single-cell RNA-Seq, has opened the way to large scale pooled perturbation screens, allowing more systematic interrogations of gene functions in cells at scale. However, such Perturb-seq data poses many analysis challenges, due to its high-dimensionality, high level of technical noise, and variable Cas9 efficiency. The single-cell nature of the data also poses its own challenges, as we observe the heterogeneity of phenotypes in the unperturbed cells, along with the effect of the perturbations. All in all, these characteristics make it difficult to discern subtler effects. Existing tools, like mixscape and ContrastiveVI, provide partial solutions, but may oversimplify biological dynamics, or have low power to characterize perturbations with a smaller effect size. Here, we address these limitations by introducing the Supervised Contrastive Variational Autoencoder (SC- VAE). SC-VAE integrates guide RNA identity with gene expression data, ensuring a more discriminative analysis, and adopts the Hilbert-Schmidt Independence Criterion as a way to achieve disentangled representations, separating the heterogeneity in the control population from the effect of the perturbations. Evaluation on large-scale data sets highlights SC-VAEtextquoterights superior sensitivity in identifying perturbation effects compared to ContrastiveVI, scVI and PCA. The perturbation embeddings better reflect known protein complexes (evaluated on CORUM), while its classifier offers promise in identifying assignment errors and cells escap- ing the perturbation phenotype. SC-VAE is readily applicable across diverse perturbation data sets."
featured: false
publication: "*Machine Learning in Computational Biology (MLCB)*"
tags: ["workshop"]
url_pdf: "https://www.biorxiv.org/content/early/2024/01/08/2024.01.05.574421"
---

