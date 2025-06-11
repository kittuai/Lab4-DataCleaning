
# Lab 4 – Data Cleaning and Outlier Detection

## Overview

This repository contains a Jupyter Notebook developed as part of **Lab 4** for the course **PROG8245 – Machine Learning Programming** at Conestoga College. The notebook demonstrates essential data preprocessing workflows, including:

- Tidying data using `pandas.melt()`
- Handling missing values via deletion and imputation
- Detecting and removing outliers using Z-Score and IQR methods
- Creating visualizations with Seaborn and Matplotlib
- Structuring a clean, reproducible notebook

---

## Repository Structure

```
Lab4-DataCleaning/
│
├── week5Lab.ipynb            # Main notebook with all analysis
├── requirements.txt          # Required Python packages
├── .gitignore                # Files/folders excluded from version control
├── README.md                 # Project documentation
└── data/
    ├── pew-raw.csv
    ├── billboard.csv
    └── cars.csv
```

---

## Setup Instructions

Follow the steps below to run the notebook in your local Python environment.

### Step 1 – Clone the Repository

```bash
git clone https://github.com/kittuai/Lab4-DataCleaning.git
cd Lab4-DataCleaning
```

---

### Step 2 – Create and Activate a Virtual Environment

```bash
python -m venv venv
```

- On Windows:
```bash
venv\Scripts\ctivate
```

- On macOS/Linux:

```bash
source venv/bin/activate
```

---

### Step 3 – Install Required Dependencies

```bash
pip install -r requirements.txt
```

---

### Step 4 – Launch the Notebook

```bash
jupyter notebook week5Lab.ipynb
```

---

## Replicability

The notebook has been tested in a clean Python 3.x environment using only the packages listed in `requirements.txt`. All cells execute in order without errors, ensuring full reproducibility.

---

## Concepts Covered

- Data tidying using `melt()` and column reshaping
- Missing value handling (deletion and imputation with `SimpleImputer`)
- Z-Score and IQR-based outlier detection
- Histogram, boxplot, and scatterplot visualizations
- Clean and maintainable Jupyter Notebook structure with markdown documentation

---


**Krishna Reddy**  
Machine Learning Programming – PROG8245  
Conestoga College  
GitHub: [@kittuai](https://github.com/kittuai)
