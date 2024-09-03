# scTCR repo

Welcome to this repository where we will explore the code used to reproduce the scTCR-seq analysis to obtain all the R objects necessary to create the plots for our paper *"Integrative single-cell multi-omic analysis of clonal composition and transcriptional programs of CARneg and CD19 CARpos T cells reveals key drivers of immunotherapy response".*

## Background
In our article, we investigate the link between the phenotypic, clonal, and functional heterogeneity of the infused CARpos T cells and their potential impact on clinical outcomes. We examine how the clonal kinetics and diversity of CAR-T cells translates into different functional T cell subsets, which will be crucial to identify the specific CAR-T cell clones responsible for short-term effectiveness and long-term persistence. 


## Methodology
To achieve our objective, we will follow a step-by-step process:

1. Data Preparation: scRNA-seq data is analysed in https://github.com/Merguerrero and load it in here (referred as *seurat.rds*).
2. TCR Integration: We will incorporate TCR information into our data (*01_TCR_Data.Rmd*).
3. Analysis of clonal dynamics (*02_CARpos_Clonal_Dynamics.Rmd*)
4. Plotting: We have an R notebook to reproduce all figures I have done in the paper.





**Now, let's dive into the code and start incorporating TCR information into our data!**
