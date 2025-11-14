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

#### Exploratory Data Analysis (EDA)

* Scatter plots showing income vs median house value

* Visualization of log-transformed features

#### Machine Learning Models

> The Random Forest model was trained and had the following evaluations.

* R²: ~0.80

* Lower RMSE

* Automatically learns interactions between features

* Feature importance analysis

#### Key Insights

- Income is the strongest predictor of housing prices

- Population, house age, and latitude/longitude influence prices in nonlinear ways

- Random Forest captures complex patterns that Linear Regression cannot

- Log-transforming skewed features significantly improves model performance

#### Tools & Technologies

- Python

- Pandas

- NumPy

- Scikit-Learn

- Matplotlib / Seaborn

- Jupyter Notebook

### How to Run the Project
> 1. Clone the repository https://github.com/Emptey/California-Housing-price-prediction.git
> 2. Install dependencies pip install -r requirements.txt
> 3. Run the notebook jupyter notebook

