---
title: ADTnorm
summary: A robust normalization and integration method for CITE-seq protein data analysis

tags:
- Single-cell
- Software Development
- Data Integration
- CITE-seq

date: "2025-01-09"
authors: 
  - Ye Zheng

external_link: ""

image:
  caption: 'ADTnorm workflow'
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  name: GitHub
  url: https://github.com/yezhengSTAT/ADTnorm
- icon: book
  icon_pack: fas
  name: Documentation
  url: https://yezhengstat.github.io/ADTnorm/articles/ADTnorm-tutorial.html
---

**Overview**: ADTnorm is a specialized normalization and integration method designed for analyzing CITE-seq (Cellular Indexing of Transcriptomes and Epitopes by Sequencing) data. CITE-seq technology enables simultaneous measurement of surface protein and mRNA expression in single cells through antibodies conjugated to oligonucleotide tags.

**Key Features**:

1. **Robust Protein Detection**:
   - Leverages high copy numbers of surface protein molecules
   - Utilizes antibody-derived tags (ADTs) for accurate protein measurement
   - Improves cell-type identification accuracy

2. **Batch Effect Correction**:
   - Addresses variability in antibody staining
   - Removes technical variation across batches
   - Preserves biological variation
   - Enhances data interpretability

3. **Cross-study Integration**:
   - Enables integration of multiple CITE-seq datasets
   - Handles diverse experimental designs
   - Facilitates atlas-level analyses
   - Improves reproducibility across studies

4. **Advanced Analysis Tools**:
   - Automated threshold-gating
   - Antibody staining quality assessment
   - Titration optimization support
   - Antibody panel selection guidance

**Validation**: ADTnorm has been extensively benchmarked against 14 existing scaling and normalization methods across 13 public datasets, demonstrating superior performance in aligning cell populations and preserving biological signals.

The software is available as both an R package and a Python wrapper, making it accessible to a broad range of researchers in the single-cell community.

[Visit our GitHub repository](https://github.com/yezhengSTAT/ADTnorm) for installation instructions and documentation. 