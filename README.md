# Geeks4LearningBootCamp


## Overview

This repository contains my solution to a Consumer Price Index (CPI) nowcasting challenge. The objective of the challenge is to accurately predict future CPI values using historical CPI data. The project aims to demonstrate a structured data science workflow, from data preparation to model evaluation.

---

## Objective

- Nowcast headline CPI using historical inflation data
- Build a robust and reproducible prediction pipeline
- Evaluate performance using appropriate error-based metrics

---

## Dataset

The dataset includes:
- Historical CPI values
- CPI component categories over time
- Time-indexed data suitable for time-series analysis

The data required preprocessing due to:
- Missing values
- Inconsistencies across periods
- Alignment of CPI components

---

## Methodology

The solution follows the steps below:

1. Data Loading and Cleaning  
   - Inspect missing and anomalous values  
   - Format and align time-series data  

2. Exploratory Data Analysis (EDA)  
   - Identify trends and seasonality  
   - Analyze relationships between CPI components  

3. Feature Engineering  
   - Create lagged variables  
   - Generate aggregated indicators  

4. Modeling  
   - Train baseline and machine learning models  
   - Perform short-term CPI nowcasting  

5. Evaluation  
   - Assess model accuracy using RMSE and related metrics  

---

## Results and Insights

- The model successfully captured short-term CPI movements
- Feature engineering had a strong impact on performance
- There is a balance between model complexity and interpretability

Potential improvements include:
- Incorporating external macroeconomic indicators
- Model ensembling
- Advanced time-series techniques



## Author

Dylan Maharaj  
CPI Nowcasting Challenge Solution
