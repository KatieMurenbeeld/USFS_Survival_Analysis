# US Forest Service Survival Analysis
Welcome to the US Forest Service Survival Analysis, the goal of this repository if to investigate the the time lags of forest management treatments within the US Forest Service (USFS). 

Survival analysis of time lags, i.e. delays in activity or project initiation, will be done using R and Python.

To reproduce this study:
1. Download and subset the desired USFS activities data following the instructions in the Python Jupyter Notebook.
2. Use the R script for Data processing, substituting in the correct sorting directory, file paths, and file names. 
3. Use the R markdown (or use as a template) to complete a survival analysis. See the Reference folder for the R vignette on using the survival package. 

## 1. Download and subset the desired USFS activities data.

In the **PYTHON** folder you will find a Jupyter Notebook *Downlaod_Convert_Subset_Forest_Service_Data-for-Survival-Analysis-v02.ipynb* with instructions for downloading and subsetting USFS data.

## 2. Use an R script for data processing

In the **R** folder you will find a R script for processing the data downloaded in #1. 

## 3. Use the R markdown (or use it as a template) to complete a survival analysis. 

In the **R** you can use the *R_Survival_Analysis.Rmd*, or in the **REVISION** folder you can use the *R_Survival_Analysis_Revisions.Rmd* to complete the survival analysis. I have included useful references in the **REFERENCES** folder which include the R vignette for using the survival package as well as a few of the fundamental papers.
