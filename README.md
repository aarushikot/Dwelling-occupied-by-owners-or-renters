## Exploring Factors Influencing Homeownership Using Support Vector Models
## Overview
This project investigates the factors influencing homeownership in Washington State using Support Vector Machine (SVM) models. The analysis aims to classify whether a dwelling is owner-occupied or rented based on demographic and housing-related variables.

## Objectives
Analyze the impact of various demographic and housing factors on homeownership.
Predict homeownership status using different SVM kernels (Linear, Polynomial, and Radial).
Provide insights for policymakers to ensure equitable access to homeownership.
## Key Findings
Critical Determinants: Age, income, and housing size significantly affect homeownership.
## SVM Model Results:
Linear SVM: 86.40% accuracy.
Polynomial SVM: 88.11% accuracy.
Radial SVM: 87.65% accuracy.
## Dataset
The dataset was sourced from the U.S. Census via IPUMS USA and contained 75,388 observations with 24 variables. After filtering and preprocessing, the final dataset included:

Variables: AGE, ROOMS, COSTELEC, COSTGAS, COSTWATR, COSTFUEL, HHINCOME, BUILTYR2, VEHICLES, OWNERSHP.
Observations: 33,428 married individuals with spouses present.
## Methodology
Data Preparation:
Filtered dataset for individuals aged 16+ and married couples.
Selected 10 predictor variables for analysis.
## Modeling:
Split data into training (70%) and testing (30%) sets.
Applied Linear, Polynomial, and Radial SVM kernels.
Hyperparameter tuning for each kernel.
## Feature Selection:
Used RandomForestClassifier to rank features by importance.
Reduced dataset to top features for better model performance.
## Evaluation:
Accuracy scores recorded for each model.
Feature importance and decision boundaries visualized.
## Technologies Used
Python: Data processing and model training.
Libraries: scikit-learn, pandas, matplotlib, seaborn.
## Results
Linear SVM: Highlighted AGE as the most significant predictor.
Polynomial SVM: Showed COSTWATR and AGE as critical features.
Radial SVM: Identified ROOMS and AGE as key factors.
## Policy Implications
Focus on affordable housing programs.
Financial assistance for down payments and mortgages.
Encourage sustainable homeownership practices.
## How to Run the Project
Prerequisites:
Python 3.x
Required libraries: scikit-learn, pandas, matplotlib, seaborn
## Steps:
Clone the repository.
Install dependencies using pip install -r requirements.txt.
Run the Jupyter Notebook or Python scripts for data preprocessing and model training.
## References
U.S. Census data via IPUMS USA.
Gareth James, Daniela Witten, Trevor Hastie, Robert Tibshirani - An Introduction to Statistical Learning.
GeeksforGeeks: Support Vector Machine Algorithm.
