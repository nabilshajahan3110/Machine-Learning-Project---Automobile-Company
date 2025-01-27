# Project Overview: Predicting Car Prices for a Chinese Automobile Company

## Background

A Chinese automobile company aims to penetrate the U.S. market by manufacturing and selling cars locally. To ensure competitive pricing, the company engaged a consulting firm to analyze factors that influence car prices in the American market, which may differ significantly from the Chinese market. The goal of this analysis is to understand these factors and build a predictive model that helps determine car prices based on the identified variables.

## Business Objectives

1. Identify significant variables that influence car prices.
2. Understand how these variables contribute to pricing dynamics.
3. Provide actionable insights for optimizing car design and business strategies to meet target price levels.
4. Run 5 different linear regression models and evaluate their performances.

## Dataset
The dataset contains details of various cars in the U.S. market, including attributes such as make, model, engine type, and pricing. [Dataset link provided in the notebook.]

## Key Tasks Completed

**1. Data Preprocessing**

Loaded and inspected the dataset to understand its structure.

Checked for missing values and duplicates.

Performed feature engineering.

Standardized column names for consistency.

**2. Exploratory Data Analysis (EDA)**

**Univariate Analysis**: Examined individual variables to understand their distributions and detect outliers.

**Bivariate Analysis**: Explored relationships between the target variable (price) and key predictors.

**Multivariate Analysis**: Assessed interactions among variables to uncover complex dependencies.

**3. Feature Engineering**

Encoded categorical variables using techniques like one-hot encoding and label encoding.

Scaled numerical variables to standardize ranges using the StandardScaler.

**4. Modeling**

Implemented and compared five linear regression algorithms:

Linear, Decision Tree, Gradient Boosting, Random Forest, and Supprt Vector

**5. Model Evaluation**

Split the data into training and test sets using an 80-20 split.

Evaluated model performance using metrics such as R², Mean Absolute Error (MAE), and Mean Squared Error (MSE).

## Findings and Insights

**Significant Variables**: Identified key predictors of car prices, including engine size, horsepower, and manufacturer reputation.

**Model Findings**: Gradient Boosting performed the best across all metrices.

**Regularization Benefits**: After implementing Hyperparameter tuning, Support Vector Regressor's performance improved significantly. However, Gradient Boosting and Random Forest are still the superior models.

**Impactful Features**: Luxury brands and advanced engine specifications were major contributors to higher prices.

**Market Trends**: Fuel efficiency and compact designs were valued among mid-range vehicles, reflecting U.S. consumer preferences.
