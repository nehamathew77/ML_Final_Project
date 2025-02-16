Predicting Health Outcomes Based on Access to Food
****

Overview

This project explores the relationship between access to healthy food options and diabetes prevalence in the U.S. The study uses machine learning models to analyze data from the USDA and CDC to determine if food accessibility correlates with health outcomes.

****

Research Question

Does limited access to healthy food options correlate with higher diabetes prevalence?

****

Data Sources

USDA Food Access Data: Information on food accessibility, including populations without easy access to grocery stores.

CDC Diagnosed Diabetes Data: County-level diabetes rates and the Social Vulnerability Index (SVI).

****

Data Processing

Data cleaning (handling missing values, removing nulls).

Merging datasets using "County" as the key.

Standardizing features for machine learning.

****

Exploratory Data Analysis

Scatter and box plots to analyze trends in diabetes rates.

Correlation matrix to determine relationships between variables.

Findings: Weak correlation (~0.22 at most) between diabetes rates and food access metrics.

****

Machine Learning Models

Best Model: Random Forest (polynomial feature transformation), achieving:
RMSE: 0.4734
R²: 0.9003 (explaining 90% of the variance in diabetes rates)

Other Models: Gradient Boosting models underperformed, with R² between 0.46 and 0.55.

****

Key Findings

Social Vulnerability Index (SVI) was the strongest predictor of diabetes rates.

Food access had minimal direct impact on diabetes outcomes.

Future Work: Incorporating fast food density data for a more comprehensive analysis.

****

Future Improvements

Testing additional polynomial transformations.

Expanding the dataset to include fast food prevalence.
