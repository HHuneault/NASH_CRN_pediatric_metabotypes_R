# NASH_CRN_pediatric_metabotypes_R
R code used for NASH CRN analyses_pediatric MASLD
This repository contains the R code and analysis pipeline used in the manuscript: **"Clinically Distinct Metabotypes of Pediatric Metabolic Dysfunction-Associated Steatotic Liver Disease: An Unsupervised Machine Learning Analysis of Children Enrolled in NASH CRN Studies"** (Submitted to Nature Communications). This analysis was conducted using **R version 4.2.3**. Required R packages include `tidyverse`, `dplyr`, `ggplot2`, `pheatmap`, `mdatools`, and `pls`. To install the necessary packages, use:
install.packages(c("tidyverse", "dplyr", "ggplot2", "pheatmap", "mdatools", "pls"))
Ensure you have at least 8GB RAM available for clustering and metabolomics preprocessing. To clone this repository and set up the environment, run:
git clone https://github.com/HHuneault/NASH_CRN_pediatric_metabotypes_R.git
cd NASH_CRN_pediatric_metabotypes_R
Then, install the required R packages as described above. This repository includes R Markdown (.Rmd) files for different parts of the data preprocessing and statistical analysis prior to running xMWAS. The key files are:
Metabotypes clustering.Rmd – Unsupervised clustering analysis of pediatric MASLD subtypes
Metabolomics PCA.Rmd – Principal component analysis of metabolomic profiles
Pathway analysis bar plots_metabotypes.Rmd – Pathway enrichment and visualization of significant metabolites
Metabotypes metabolomics figures.Rmd – Figures illustrating metabolomic differences across subtypes
Fibrosis correlations R code.Rmd – Analysis of fibrosis markers and correlation with metabolic features
xMWAS Analysis: This repository does not include R-based xMWAS scripts. Instead, xMWAS analysis was conducted using the online Shiny app at: https://kuppal.shinyapps.io/xmwas/
Due to data-sharing agreements, the full dataset is not publicly available. However, some clinical and metabolomics data can be accessed at:
https://www.metabolomicsworkbench.org/ (Study ID: ST001428) 
https://repository.niddk.nih.gov/home
