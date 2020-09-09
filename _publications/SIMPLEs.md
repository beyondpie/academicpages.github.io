---
title: "SIMPLEs: a single-cell RNA sequencing imputation strategy preserving gene modules and cell clusters variation"
collection: publications
permalink: /publications/SIMPLEs
date: 2020-08-31
venue: 'Accepted by NAR Genomics and Bioinformatics'
citation: 'Zhirui Hu*, <b>Songpeng Zu</b>* (equal contribution), Jun S. Liu. <i>bioRxiv 2020</i>'
---

[[PDF]](https://www.biorxiv.org/content/10.1101/2020.01.13.904649v1.full.pdf)

## Abstract
A main challenge in analyzing single-cell RNA sequencing (scRNASeq) data is to reduce technical variations yet retain cell heterogeneity. Due to low mRNAs content per cell and molecule losses during the experiment (called “dropout”), the gene expression matrix has substantial zero read counts. Existing imputation methods either treat each cell or each gene identically and independently, which oversimplifies the gene correlation and cell type structure. We propose a statistical model-based approach, called SIMPLEs, which iteratively identifies correlated gene modules and cell clusters and imputes dropouts customized for individual gene module and cell type. Simultaneously, it quantifies the uncertainty of imputation and cell clustering. Optionally, SIMPLEs can integrate bulk RNASeq data for estimating dropout rates. In simulations, SIMPLEs performed significantly better than prevailing scRNASeq imputation methods by various metrics. By applying SIMPLEs to several real data sets, we discovered gene modules that can further classify subtypes of cells. Our imputations successfully recovered the expression trends of marker genes in stem cell differentiation and can discover putative pathways regulating biological processes.
