# BoomBikes-Demand-Prediction
## Problem Statement

BoomBikes, a US-based bike-sharing provider, has experienced significant revenue drops due to the COVID-19 pandemic. With the challenging market environment, BoomBikes is strategizing to boost revenue post-lockdown by understanding and predicting the demand for shared bikes. The company has enlisted a consulting firm to analyze factors influencing bike demand in the American market, aiming to optimize their service offerings and outperform competitors once normalcy returns.

## Exploratory Data Analysis (EDA)
The initial phase of the project involved conducting comprehensive exploratory data analysis (EDA) to understand the underlying patterns and relationships within the data. This included examining correlations between variables to identify potential predictors for bike rental demand.

## Data Preprocessing
After identifying relevant variables through EDA, I proceeded to preprocess the data by creating dummy variables for categorical features to ensure they were properly included in the model. This step was crucial for handling non-numeric data effectively.

## Model Selection and Refinement
The dataset was then split into training and testing sets to facilitate model training and evaluation. Using Recursive Feature Elimination (RFE), I systematically reduced the number of variables to focus only on those that significantly impacted the demand for bike rentals. This step helped refine the model by eliminating redundant or irrelevant predictors.

## Model Validation
Once the model was finalized, I conducted various diagnostic tests to validate its assumptions, including checking for normality, linearity, and homoscedasticity. These tests ensured that the model met the necessary statistical criteria for a valid regression analysis.

## Prediction and Evaluation
Finally, I used the model to make predictions on the test set. The model's performance was assessed using the R-squared statistic to quantify its effectiveness in explaining the variance in bike rental demand.
