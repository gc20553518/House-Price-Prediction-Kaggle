# House Price Prediction — Kaggle Project

**UCLA | Regression Modeling & Feature Engineering | Winter 2026**

## Project Overview

This project focuses on predicting residential housing prices using regression modeling in R. The goal is to identify important housing characteristics, compare candidate models, and improve prediction accuracy through feature transformations and interaction terms.

## Dataset

The training dataset contains approximately 7,000 observations and 90 variables, including structural features, property quality, neighborhood information, and sale prices.

## Methods & Tools

- **Language:** R
- **Libraries:** car, caret
- Exploratory Data Analysis (EDA)
- Log transformation of SalePrice
- Multiple linear regression
- Stepwise AIC model selection
- Interaction terms and feature engineering
- 10-fold cross-validation
- Residual diagnostics, VIF, and Cook's Distance

## Model Development

Five candidate regression models were evaluated, starting with a baseline model and progressing to more detailed specifications.

The final selected model incorporates housing characteristics, renovation timing, and interactions between overall quality and structural features.

## Results

The final model was selected using AIC comparisons and 10-fold cross-validation.

The project also achieved a reported Top 15 placement on the Kaggle leaderboard.

## Limitations

The analysis relies on regression assumptions and selected housing features. Model performance may vary on unseen data, and stepwise model selection may introduce selection bias.

## Project Files

- `analysis.Rmd` — Data exploration, model development, and diagnostics
- `HousePriceTrain.csv` — Training data
- `HousePriceTestNoY.csv` — Test data
- `DataDictionary.xlsx` — Variable descriptions
- `submission.csv` — Prediction submission

## Project Attribution

UCLA academic project. Individual contributions and collaborator attribution should match the original project work.
