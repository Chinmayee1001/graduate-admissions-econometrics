# graduate-admissions-econometrics
Econometric analysis of graduate admission probability using CGPA, GRE and SOP from an Indian Perspective
# Graduate Admissions Prediction – Econometric Analysis

## Overview
This project analyzes the determinants of the probability of graduate admission to U.S. universities
from an Indian perspective using econometric regression techniques.

The model estimates admission probability as a function of:
- Undergraduate CGPA
- GRE Scores
- Statement of Purpose (SOP)

## Methodology
- Probability-based regression framework (logit / OLS on transformed probabilities)
- Box–Tidwell test for linearity
- Diagnostic checks for:
  - Linearity
  - Normality (with bootstrap inference)
  - Heteroscedasticity
  - Multicollinearity (VIF, Ridge Regression)
  - Influential observations (Cook’s Distance, DFFITS)

## Key Findings
- CGPA is the strongest and most robust predictor of admission probability
- GRE and SOP exhibit nonlinear (U-shaped) effects
- Model explains ~85% of variation in admission probability
- Diagnostic tests confirm robustness after appropriate econometric remedies

## Tools Used
- R
- Econometrics
- Bootstrap Inference
- Ridge Regression

## Files
- `ECONOMETRICS_PROJECT_WORK.pdf` – Full project report[ECONOMETRICS PROJECT WORK.pdf](https://github.com/user-attachments/files/24633456/ECONOMETRICS.PROJECT.WORK.pdf)

- `Eco.Rproj` – R project file[Eco Script.pdf](https://github.com/user-attachments/files/24633475/Eco.Script.pdf)



## Author
**Chinmayee Panda**
