# Suicidal Ideation Prediction

Curriculum Work / Machine Learning

## Overview

This project demonstrates the application of various Machine Learning techniques to predict suicide rates based on a dataset. The techniques implemented include Linear Regression, Polynomial Regression, Support Vector Machine (SVM) Regression, Decision Trees, and Random Forest Classifier. The dataset used is sourced from data.gov.ie.

## Project Details

The notebook provides a comprehensive analysis and implementation of the following:

- **Data Import**: Loading and exploring the dataset.
- **Correlation Heatmap**: Visualizing correlations between features.
- **Linear Regression**: Applying linear regression and evaluating its performance.
- **Polynomial Regression**: Using polynomial regression for better prediction.
- **Support Vector Machine (SVM) Regression**: Implementing SVM with polynomial kernel.
- **Decision Trees & Random Forest**: Building and visualizing decision trees and random forest classifiers.

## Libraries Used

- **NumPy**: For numerical operations.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For plotting graphs.
- **Seaborn**: For generating heatmaps.
- **SciPy**: For statistical functions.
- **Scikit-learn**: For machine learning models and metrics.

## Data Description

The dataset contains the following columns:
- `YEAR`: Year of the data
- `MALE`: Number of suicides by males
- `FEMALE`: Number of suicides by females
- `TOTAL`: Total number of suicides
- `UNEMPLOYED`: Number of unemployed individuals
- `DRUGS`: Number of individuals with drug-related issues
- `HOMELESS`: Number of homeless individuals

## Analysis and Results

1. **Correlation Heatmap**: Indicates low correlation among features, except for years and the total number of suicides.
2. **Linear Regression**: Shows poor fit due to lack of linear correlation.
3. **Polynomial Regression**: Provides a better fit for predicting future trends.
4. **Support Vector Machine Regression**: Offers reasonably accurate predictions with the given dataset.
5. **Decision Trees & Random Forest Classifier**: Useful for classification and prediction with reasonable accuracy.

## Disclaimer

This project is created as part of the curriculum for the Machine Learning module. Any direct adaptation of the code or dataset should be avoided as it may lead to academic dishonesty.

## Contact

Joshua Peter  
Email: [josh19peter96@gmail.com](mailto:josh19peter96@gmail.com)
