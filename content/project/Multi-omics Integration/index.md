---
title: Multi-omics Integration for Single-cell Data Analysis
date: "2022-07-25"
weight: 30
summary: Developing computational methods for integrating single-cell multi-omics data, including 3D chromatin structure (scHi-C), transcriptomics (scRNA-seq), and proteomics (CITE-seq) data, to better understand cellular heterogeneity and gene regulation.

tags:
- Multi-omics Integration
- Genomics

authors:
- Ye Zheng

external_link: ""

image:
  caption:
  focal_point: Smart
---

**Overview**: Our project focuses on developing innovative computational methods for integrating various single-cell multi-omics data types. We aim to combine three-dimensional chromatin interaction (scHi-C) data with transcriptomics and proteomics data (scRNA-seq and CITE-seq) to gain comprehensive insights into cellular regulation and function.

**Motivation**: The integration of multiple single-cell data modalities presents unique opportunities and challenges in understanding cellular heterogeneity. Our research addresses these challenges through several key innovations:

1. **scGAD (single-cell Gene Associating Domain) Scores**:
   - A dimension reduction and exploratory analysis tool for scHi-C data
   - Enables gene-level summarization while accounting for genomic biases
   - Facilitates integration with other single-cell modalities
   - Projects 3D genomics data onto reference embeddings

2. **Key Features and Applications**:
   - Captures cell clustering based on 3D chromatin structure
   - Identifies significant chromatin interactions within and between cell types
   - Enables automated and refined cell-type annotation
   - Provides multi-modal data integration framework

3. **ADTnorm Development**:
   - A specialized normalization method for cell surface protein measurements
   - Available as both R package and Python tool
   - Effectively removes batch effects across studies
   - Facilitates cross-study data integration

Our integrative approach enables:
- Comprehensive understanding of cellular states
- Improved cell type identification
- Better characterization of regulatory mechanisms
- Cross-modality validation of biological findings

The project's success has led to robust tools that are being widely adopted by the single-cell research community, contributing to our understanding of cellular heterogeneity and regulation at unprecedented resolution.
