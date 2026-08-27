# EDA Notes

These notes summarize the key content from `exercises/understanding_data`.

## Goal
Explore and validate a dataset before modeling.

## Recommended EDA Flow
1. Overview and metadata
2. Basic questions and sanity checks
3. Univariate analysis
4. Bivariate and multivariate analysis
5. Data quality checks (missing values, duplicates, outliers, data types)
6. Automated profiling (optional)

## Module Mapping (Current Files)
- `exercises/understanding_data/01_asking_basic_questions.ipynb`
- `exercises/understanding_data/02_univariate_analysis.ipynb`
- `exercises/understanding_data/03_bivariate_and_multivariate.ipynb`
- `exercises/understanding_data/04_ydata_profiling.ipynb`
- `exercises/understanding_data/05_sales.ipynb`

## Key Checks To Always Run
- Shape of dataset (`rows`, `columns`)
- Column names and data types
- Missing values per column
- Duplicate rows
- Target column distribution (if supervised task)
- Numerical summary: mean, median, std, min, max, quartiles
- Categorical summary: unique values and frequency
- Outlier detection with IQR or visual plots
- Correlation analysis for numeric features

## Typical Visuals
- Histograms / KDE for numeric features
- Count plots for categorical features
- Box plots for outliers
- Scatter plots and pair plots for relationships
- Heatmap for correlation matrix

## Dataset Locations
- `resources/datasets/understanding_data/train.csv` (Titanic working sample)

## Folder Purpose
Use this folder to keep your quick revision notes and EDA checklists.
