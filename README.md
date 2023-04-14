# clustering_resource
##Setup: You will need to install following:
###1. R: R is a programming language very useful single cell analysis. Install from here:https://www.r-project.org/
###To interact with R, we use RStudio. Install from here : https://posit.co/download/rstudio-desktop/

##Other Packages after installing R and R-studio:
###Install Seurat: Run install.packages('Seurat') on R studio
###Install Bioconductor : Run if (!require("BiocManager", quietly = TRUE))
    install.packages("BiocManager")
BiocManager::install(version = "3.16")
###Install scRNAseq library that is used as input dataset in this tutorial: Run BiocManager::install("scRNAseq")
### To use refernce annotation from Azimuth, you can install Azimuth :https://satijalab.github.io/azimuth/index.html
