# HousingPricePredictionModel
Exploratory Data Analysis (EDA) on Credit Card Spending Habits using Python, featuring data visualization and insights into spending patterns

# Introduction:
This repository contains a Python-powered project aimed at predicting housing prices using various machine learning techniques. The project explores the relationship between different housing features (e.g., area, bedrooms, bathrooms, and others) and their impact on housing prices. It applies data preprocessing, feature selection, and linear regression modeling to build an accurate predictive model.

## Key Features:
- **Data Exploration**: Visualizes the data using seaborn and matplotlib to identify patterns, relationships, and outliers in key variables.
- **Outlier Removal**: Implements the Interquartile Range (IQR) method to eliminate outliers in 'price' and 'area', improving model robustness.
- **Feature Engineering**: Converts categorical variables into numerical form using binary mapping and one-hot encoding.
- **Model Building**: Uses Recursive Feature Elimination (RFE) and OLS regression for feature selection and model building.
- **Model Evaluation**: Evaluates the model's performance using metrics like R-squared, and visualizes the error terms and residuals.
- **Correlation Analysis**: Includes heatmaps and correlation matrices to identify multicollinearity and relationships among variables.

## Libraries Used:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `statsmodels`

## Visualizations:
- Boxplots, pair plots, and heatmaps for feature exploration.
- Residual and error distribution plots to evaluate model performance.
- Scatter plot comparing actual vs predicted housing prices.

---
