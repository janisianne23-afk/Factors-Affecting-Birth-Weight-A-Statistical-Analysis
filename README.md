# Factors-Affecting-Birth-Weight-A-Statistical-Analysis

## Overview
This project explores demographic, medical, and behavioural factors associated with low birth weight using statistical modelling in R. Particularly, generalised linear models and model diagnostics relating to these factors are applied to idenify significant relationships. 

This project was completed as a part of an academic course: STAT3030 Generalised Linear Models and is presented here as a portfolio piece demonstrating applied data analysis and reproducible reporting. 

## Key skills Demonstrated
- R programming
- Data cleaning and exploratory data analysis (EDA)
- Generalised Linear Models (GLMs)
- Statistical interpretation and reporting
- Data visualisation with ggplot2
- Reproducible analysis using R Markdown

- -

## Repository Contents
- 'bwt_analysis.rmd' - Full reproducible analysis and code
- 'bwt_analysis.html' - Rendered HTML report (recommended for viewing)
- 'bwt_report.pdf' - Formal academic report

## How to View This Project
- Open 'bwt_analysis.html' directly in your browser to view the full analysis with figures and commentary
- **Alternatively** Open the 'bwt_analysis.rmd' in RStudio and knit the document to HTML

## How to run the code
The following packages are required for the analysis (which are already in the rmd file):
- ggplot
- dplyr
- effects

## Reproducibility
To recreate the exact package environment used in this analysis:
```r
install.packages("renv")
renv::restore()
