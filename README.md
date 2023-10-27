# RNAseq analysis

This repository is to replicate analyses from the manuscript titled "Antiviral responses induced by Tdap-IPV vaccination are associated with persistent humoral immunity to pertussis".

R software is needed to run the code.

All data is available through GEO (data generated in this study: GSE195627. Data generated Antunes et al.:  GSE152683), or are available in the Source Data file that is provided with the manuscript.

Starting from the processed RNAseq data available on GEO and the antibody and single-cell RNA sequencing data available in the source data file, the R pipeline “RNAseq analysis.rmd” contains code to reproduce the figures and analyses below.

Figure 1C: Antibody log-10 fold change comparisons\
Figure S1: Raw antibody values pre- and post-vaccination comparisons\
Figure S6: Cross-correlation of antibody LFC and baseline values\
Figure 2B & Figure S16: Differential gene expression analyses and gene set enrichment analyses of NL, UK cohorts and Antunes et al. cohort\
Figure 3: gene set enrichment analyses of gene expression data correlated with Adjusted antibody responses (includes calculation of adjusted antibody responses)\
Figure 5E: cross-correlation of whole blood gene expression signatures with single-cell gene expression signatures\
Figure 7B: comparison of differential gene expression signatures of TdapIPV (NL and UK cohorts) with Tdap (Antunes et al. cohort)
