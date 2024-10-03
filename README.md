# Car Insurance Claims Analysis & Model

## Overview
This repository contains an analysis of a car insurance claims dataset aimed at understanding the factors influencing whether a customer will file a claim. The project includes data preprocessing, exploratory data analysis (EDA), and modeling using logistic regression.

## Project Objectives
- Identify the best predictor feature for insurance claims.
- Analyze various demographic, financial, and behavioral factors that influence claim likelihood.
- Provide insights for risk assessment and customer engagement strategies.

## Key Findings
- **Age**: Younger drivers (ages 16-25) are more likely to make claims.
- **Gender**: Males have a higher likelihood of claims compared to females.
- **Driving Experience**: Less experienced drivers (0-9 years) tend to file more claims.
- **Credit Score**: No significant difference in credit scores between claimants and non-claimants.
- **Annual Mileage**: Higher annual mileage correlates with increased claim likelihood.
- **Marital Status**: Unmarried individuals are more likely to file claims.
- **Children**: Families with children tend to make fewer claims.
- **Best Predictor**: The analysis identifies a specific feature that serves as the best predictor of claims.

## Technologies Used
- Python
- pandas
- statsmodels
- seaborn
- matplotlib

## Dataset
The dataset used for this analysis includes various features related to car insurance and customer demographics. It is included in the repository.

## Installation
To run this project, clone the repository and install the necessary packages:
```bash
git clone https://github.com/mgalal07/car-insurance-claims-analysis.git
cd car-insurance-claims-analysis
pip install -r requirements.txt
