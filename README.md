# clustering_resource

## Setup: You will need to install following:

### 1. R: R is a programming language very useful for single cell analysis. Install from here:https://www.r-project.org/
### 2. In order to interact with R and write our codes, we use RStudio. Install from here : https://posit.co/download/rstudio-desktop/

## Other Packages after installing R and R-studio:
### Install Seurat: Run following on R studio
``` r
install.packages('Seurat') 
```
### Install Bioconductor : Run following on R studio
``` r
if (!require("BiocManager", quietly = TRUE))
    install.packages("BiocManager")
BiocManager::install(version = "3.16")
```
### Install scRNAseq library that is used as input dataset in this tutorial: Run BiocManager::install("scRNAseq")
### To use reference annotation from Azimuth, you can install Azimuth : https://satijalab.github.io/azimuth/index.html
