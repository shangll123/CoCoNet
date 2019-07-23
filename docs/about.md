---
layout: page
title: About
permalink: /about/
---
Genome-wide association studies (GWASs) have identified many SNPs associated with various common diseases. Understanding the biological functions of these identified SNP associations requires identifying disease/trait relevant tissues or cell types. Here, we develop a network method, CoCoNet, to facilitate the identification of trait-relevant tissues or cell types. 

Different from existing approaches, CoCoNet incorporates tissue-specific gene co-expression networks constructed from either bulk or single cell RNA sequencing (RNAseq) studies with GWAS data for trait-tissue inference. In particular, CoCoNet relies on a covariance regression network model to express gene-level effect sizes for the given GWAS trait as a function of the tissue-specific co-expression adjacency matrix. With a composite likelihood-based inference algorithm, CoCoNet is scalable to tens of thousands of genes. 

Cite `CoCoNet`
-------------------
Lulu Shang,Jennifer A. Smith, and Xiang Zhou. *Leveraging Gene Co-expression Patterns to Infer Trait-Relevant Tissues in Genome-wide Association Studies*, 2019. 

Lab Website
-------------------
[www.xzlab.org](https://www.xzlab.org/)
