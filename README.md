# Titanic Dataset — Exploratory Data Analysis

## Overview
This project explores the Titanic passenger dataset to understand survival patterns using Python.

## Objectives
- Inspect dataset structure and summary statistics.
- Identify missing values and duplicate records.
- Clean selected columns.
- Analyze survival rates by sex, passenger class, age group, and fare range.
- Visualize distributions and survival patterns.

## Tools and Libraries
- Python
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

## Key Findings
- Approximately 38.38% of passengers in the analyzed training dataset survived.
- Female passengers had a higher survival rate than male passengers.
- First-class passengers had a higher survival rate than second- and third-class passengers.
- Children had a higher survival rate than the older age groups defined in this analysis.
- Survivors paid a higher average fare than non-survivors.

These are associations observed in the dataset and do not establish causation.

## Data Cleaning
- Filled missing ages with the median.
- Filled missing embarkation ports with the mode.
- Replaced missing cabin values with `"Unknown"`.
- Checked for duplicate records.

## How to Run
1. Clone or download this repository.
2. Install the required Python libraries.
3. Place `train.csv` in the notebook's working directory, or update the data-loading path.
4. Open the notebook in Jupyter and run all cells.


## Dataset
Titanic training dataset from Kaggle:
https://www.kaggle.com/competitions/titanic/data
