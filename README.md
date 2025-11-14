## California Housing Price Prediction
### A Machine Learning Project using Random Forests

#### Overview

This project builds and evaluates machine learning models to predict median house prices in California using the classic California Housing dataset. It includes full data preprocessing, feature engineering, exploratory data analysis (EDA), and model evaluation.

> The goal is to demonstrate:

- How to clean and prepare real-world tabular data

- How to engineer meaningful features

- How to compare linear vs nonlinear models

- How to evaluate predictive performance

- How to interpret Random Forest feature importance

#### Project Workflow
**Data Cleaning**

- Handled missing values

- Removed noise/outliers

- Converted columns to proper types

- Scaled numerical features using StandardScaler

#### Feature Engineering

Created new features for better model performance:

* LogMedInc — log-transformed median income

* LogPopulation — log-transformed population

* RegionBinary — encoded region as 0/1

* Extracted geographical effects (latitude & longitude)