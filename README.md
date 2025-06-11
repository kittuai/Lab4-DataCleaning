# Lab 4 – Data Cleaning and Outlier Detection

## Overview

This repository contains a Jupyter Notebook developed as part of Lab 4 for the course PROG8245 – Machine Learning Programming. The objective is to apply key data preprocessing techniques, including data tidying, missing value handling, and outlier detection using multiple real-world datasets.

The notebook demonstrates:
- Reshaping untidy data using `pandas.melt()`
- Handling missing data through deletion and imputation
- Visualizing and removing outliers using Z-Score and IQR methods
- Structuring code and markdown for clarity and reproducibility

## Repository Contents

- `week5Lab.ipynb` – Main notebook containing all code, markdown explanations, and visualizations
- `requirements.txt` – List of Python packages required to run the notebook
- `.gitignore` – Git exclusions for cache files and virtual environments
- `data/` – Folder containing the datasets used:
  - `pew-raw.csv`
  - `billboard.csv`
  - `cars.csv`

## Setup Instructions

## Setup Instructions

Follow the steps below to set up and run the notebook:

```bash
git clone https://github.com/kittuai/Lab4-DataCleaning.git


cd Lab4-DataCleaning


## Replicability

The notebook was tested in a clean Python 3.x environment using only the packages listed in `requirements.txt`. All cells were executed in order and ran without errors, confirming full reproducibility.

## Topics Covered

- Data tidying using `melt()` and column transformations
- Missing value strategies: row/column removal and mean imputation via `SimpleImputer`
- Outlier detection using both Z-Score and IQR approaches
- Visualizations using `seaborn` and `matplotlib`
- Structured markdown documentation for clarity and code readability

## Author

Krishna Reddy  
Conestoga College  
GitHub: https://github.com/kittuai
