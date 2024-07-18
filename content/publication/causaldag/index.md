---
title: "Large-scale differentiable causal discovery of factor graphs"
date: 2022-11-01
publishDate: 2024-01-30T02:25:59.512786Z
authors: ["<u>Romain Lopez</u>", "Jan-Christian Huetter", "Jonathan K. Pritchard", "Aviv Regev"]
publication_types: ["2"]
abstract: "A common theme in causal inference is learning causal relationships between observed variables, also known as causal discovery. This is usually a daunting task, given the large number of candidate causal graphs and the combinatorial nature of the search space. Perhaps for this reason, most research has so far focused on relatively small causal graphs, with up to hundreds of nodes. However, recent advances in fields like biology enable generating experimental data sets with thousands of interventions followed by rich profiling of thousands of variables, raising the opportunity and urgent need for large causal graph models. Here, we introduce the notion of factor directed acyclic graphs (f-DAGs) as a way to restrict the search space to non-linear low-rank causal interaction models. Combining this novel structural assumption with recent advances that bridge the gap between causal discovery and continuous optimization, we achieve causal discovery on thousands of variables. Additionally, as a model for the impact of statistical noise on this estimation procedure, we study a model of edge perturbations of the f-DAG skeleton based on random graphs and quantify the effect of such perturbations on the f-DAG rank. This theoretical analysis suggests that the set of candidate f-DAGs is much smaller than the whole DAG space and thus more statistically robust in the high-dimensional regime where the underlying skeleton is hard to assess. We propose Differentiable Causal Discovery of Factor Graphs (DCD-FG), a scalable implementation of f-DAG constrained causal discovery for high-dimensional interventional data. DCD-FG uses a Gaussian non-linear low-rank structural equation model and shows significant improvements compared to state-of-the-art methods in both simulations as well as a recent large-scale single-cell RNA sequencing data set with hundreds of genetic interventions."
featured: true
publication: "*Advances in Neural Information Processing Systems*"
tags: ["conference", "featured"]
url_pdf: "https://proceedings.neurips.cc/paper_files/paper/2022/hash/7a8fa1382ea068f3f402b72081df16be-Abstract-Conference.html"
url_code: "https://github.com/Genentech/dcdfg"
projects: ["science"]
---

