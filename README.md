# Data-Transformations-and-Symmetry
This repository contains R scripts for analyzing and transforming skewed datasets to achieve symmetry. It includes Hinkley's method for measuring skewness, various transformations (log, square root), and visualization tools such as histograms and symmetry plots to assess transformation effectiveness


# Data Transformations and Symmetry Analysis

## Overview
This repository provides R code and methods for analyzing and transforming skewed datasets to achieve symmetry. The main focus is on:
- Detecting skewness in datasets using visual tools (e.g., histograms, boxplots, symmetry plots).
- Applying transformations (log, square root) to reduce asymmetry.
- Measuring the effectiveness of transformations using **Hinkley's method**, which quantitatively evaluates skewness before and after transformations.

## Key Datasets
The following datasets are analyzed in this project:
1. **Lake Dataset**: Includes variables such as lake area, depth, acidity, and hydrogen ion concentration.


## Features
- **Symmetry Inspection**: Using histograms, boxplots, and symmetry plots to visually inspect skewness.
- **Transformations**: Applying log and square root transformations to reduce skewness in right-skewed data.
- **Hinkley's Method**: A statistical method used to measure skewness and assess transformation effectiveness.
  

## How to Use This Repository
1. **Clone the Repository**:
2. **Run the R Scripts**:
Use any R environment (e.g., RStudio or Google Colab) to execute the R scripts available in the `analysis` folder. The main script is `symmetry_analysis.R`, which walks through the transformation process for each dataset.
3. **Install Dependencies**:
Ensure the following R packages are installed:

```r
install.packages(c("ggplot2", "LearnEDAfunctions", "aplpack", "dplyr"))
```
