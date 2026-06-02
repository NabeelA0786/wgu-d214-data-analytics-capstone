# D214 – Data Analytics Capstone

**WGU Master of Science in Data Analytics**

## Overview
End-to-end analytics project investigating how vehicle characteristics affect Manufacturer's Suggested Retail Price (MSRP). Demonstrates the full analytics lifecycle from raw data to executive presentation.

## Research Question
*How do vehicle characteristics (engine HP, cylinders, fuel type, transmission type, vehicle size) affect MSRP?*

## Dataset
Car Features and MSRP dataset (Kaggle) — 11,914 vehicle records

## What Was Done

### Data Preparation
- Cleaned 11,914 records: removed inconsistencies, handled missing values
- Encoded categorical variables (fuel type, transmission, vehicle size)
- Created analysis-ready dataset

### Statistical Modeling
- Built a **Multiple Linear Regression** model to predict MSRP
- Performed **ANOVA** to test significance of categorical variables
- Ran **VIF testing** to check for multicollinearity
- Evaluated model with R², coefficient interpretation, and hypothesis testing

### Deliverables
- Full written research report
- Executive summary for non-technical stakeholders
- Data visualizations supporting findings
- PowerPoint presentation (recorded via Panopto)

## Key Finding
Engine horsepower and vehicle size were the strongest predictors of MSRP, with the model explaining a significant portion of price variance across vehicle classes.

## Tools & Libraries
`Python` · `Pandas` · `Statsmodels` · `Scikit-learn` · `Matplotlib` · `Seaborn` · `Jupyter Notebook`

## Files
| File | Description |
|------|-------------|
| `D214.ipynb` | Main analysis notebook |
| `data.csv` | Raw dataset |
| `cars_cleaned.csv` | Cleaned dataset |
| `Task 3/D214 Presentation.pptx` | Final capstone presentation |
| `D214 Task 1 Performance Assessment.docx` | Written report |
