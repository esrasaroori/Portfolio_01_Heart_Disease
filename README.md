# Heart Disease Data Analysis

## Overview

A healthcare-focused exploratory data analysis project using the UCI Heart Disease dataset.

The project explores demographic and clinical variables associated with heart disease presence and demonstrates a complete data analysis workflow using Python.

## Objectives

- Clean and validate a real-world healthcare dataset.
- Explore demographic and clinical patterns.
- Analyze associations between selected variables and heart disease presence.
- Create clear healthcare-focused visualizations.
- Document findings and limitations.

## Project Highlights

- Cleaned and validated 303 clinical records.
- Handled missing values and data type inconsistencies.
- Performed exploratory data analysis using Pandas.
- Created healthcare-focused visualizations using Matplotlib.
- Analyzed patterns across sex, age, chest pain type, and maximum heart rate.
- Documented analytical limitations and avoided causal interpretation.

## Skills Demonstrated

- Python
- Pandas
- NumPy
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Healthcare Data Analysis
- Clinical Data Interpretation

## Dataset

This project uses the Cleveland subset of the UCI Heart Disease dataset.

- **Number of records:** 303
- **Original variables:** 14
- **Analysis variable:** `heart_disease`
- **Dataset type:** Clinical and demographic patient data

### Dataset Source

The dataset is publicly available through the UCI Machine Learning Repository.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- VS Code

## Data Cleaning

The following data cleaning steps were performed:

- Inspected the dataset structure and data types.
- Identified missing values represented by `?`.
- Replaced `?` with `NaN`.
- Converted `ca` and `thal` to numeric data types.
- Imputed missing values using the mode of each variable.
- Checked for duplicate records; no duplicates were identified.
- Performed basic data quality and range checks.
- Created a binary `heart_disease` variable from the original target codes.

## Exploratory Data Analysis

The analysis examined the relationship between heart disease presence and selected demographic and clinical variables:

- Sex
- Age
- Chest pain type
- Maximum heart rate achieved (`thalach`)

Descriptive statistics and visualizations were used to identify patterns and associations within the dataset.

## Key Findings

- Heart disease was present in approximately **55.3% of male patients** and **25.8% of female patients** in this dataset.
- Patients with heart disease had a higher average age than patients without heart disease (**56.6 vs. 52.6 years**).
- Heart disease presence varied across chest pain categories. The highest proportion was observed among patients classified as **asymptomatic (72.9%)**.
- Patients with heart disease had a lower average maximum heart rate than those without heart disease (**139.3 vs. 158.4 bpm**).

These findings describe associations observed within this dataset and should not be interpreted as causal relationships or generalized to the broader population.

## Limitations

- The analysis is based on 303 patient records from the Cleveland subset of the UCI Heart Disease dataset.
- The findings represent associations within this dataset and do not establish causal relationships.
- Missing values in `ca` and `thal` were imputed using the mode.
- The analysis focuses on descriptive statistics and exploratory visualization; no predictive machine learning model was developed.
- The findings should not be generalized to the broader population without further validation.

## Project Structure

```text
Portfolio_01_Heart_Disease/
│
├── data/
│   └── processed.cleveland.data
│
├── heart_disease_analysis.ipynb
├── README.md
└── requirements.txt