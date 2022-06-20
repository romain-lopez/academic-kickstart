---
title: "Reconstructing unobserved cellular states from paired single-cell lineage tracing and transcriptomics data"
date: 2021-11-01
publishDate: 2022-06-18T18:56:53.835329Z
authors: ["Khalil Ouardini", "<u>Romain Lopez</u>", "Matthew G. Jones", "Sebastian Prillo", "Richard Zhang", "Michael I. Jordan", "Nir Yosef"]
publication_types: ["2"]
abstract: "Novel experimental assays now simultaneously measure lineage relationships and transcriptomic states from single cells, thanks to CRISPR/Cas9-based genome engineering. These multimodal measurements allow researchers not only to build comprehensive phylogenetic models relating all cells but also infer transcriptomic determinants of consequential subclonal behavior. The gene expression data, however, is limited to cells that are currently present (\"leaves\" of the phylogeny). As a consequence, researchers cannot form hypotheses about unobserved, or \"ancestral\", states that gave rise to the observed population. To address this, we introduce TreeVAE: a probabilistic framework for estimating ancestral transcriptional states. TreeVAE uses a variational autoencoder (VAE) to model the observed transcriptomic data while accounting for the phylogenetic relationships between cells. Using simulations, we demonstrate that TreeVAE outperforms benchmarks in reconstructing ancestral states on several metrics. TreeVAE also provides a measure of uncertainty, which we demonstrate to correlate well with its prediction accuracy. This estimate therefore potentially provides a data-driven way to estimate how far back in the ancestor chain predictions could be made. Finally, using real data from lung cancer metastasis, we show that accounting for phylogenetic relationship between cells improves goodness of fit. Together, TreeVAE provides a principled framework for reconstructing unobserved cellular states from single cell lineage tracing data."
featured: false
publication: "*ICML Workshop in Computational Biology*"
tags: ["workshop"]
url_pdf: "https://www.biorxiv.org/content/early/2021/05/30/2021.05.28.446021"
projects: ["scVI"]
---

