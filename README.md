# NASH_CRN_pediatric_metabotypes_R
R code used for NASH CRN analyses_pediatric MASLD

This repository contains the R code and analysis pipeline used in the manuscript: "Clinically Distinct Metabotypes of Pediatric Metabolic Dysfunction-Associated Steatotic Liver Disease: An Unsupervised Machine Learning Analysis of Children Enrolled in NASH CRN Studies" (Submitted to Nature Communications). This analysis was conducted using R version 4.2.3. Required R packages include tidyverse, dplyr, ggplot2, pheatmap, mdatools, pls, and xMWAS. To install the necessary packages, use:
install.packages(c("tidyverse", "dplyr", "ggplot2", "pheatmap", "mdatools", "pls", "xMWAS"))

Ensure you have at least 8GB RAM available for clustering and metabolomics analyses. To clone this repository and set up the environment, run:
git clone https://github.com/HHuneault/NASH_CRN_pediatric_metabotypes_R.git
cd NASH_CRN_pediatric_metabotypes_R

Then, install the required R packages as described above. To reproduce key results, use:
source("scripts/preprocessing.R")   # Preprocessing & Data Cleaning
source("scripts/clustering.R")      # Clustering Analysis
source("scripts/pathway_analysis.R") # Metabolomics Pathway Analysis


