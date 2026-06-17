# Mobile Price Prediction

## Overview

This project presents a complete data mining workflow for predicting mobile phone prices using machine learning techniques.

The project starts with collecting mobile phone data through web scraping, followed by data cleaning, preprocessing, feature engineering, exploratory data analysis, and predictive modeling.

The goal is to identify the most important factors affecting mobile phone prices and build accurate regression models for price prediction.

## Google Colab Notebook

You can explore and run the project directly in Google Colab:

[[Open in Google Colab](PUT_YOUR_COLAB_LINK_HERE)](https://colab.research.google.com/drive/1mxjtPo2WsMcCBZVaZJfyvPKs9q4WiFLG?usp=sharing)

## Project Report

The complete project report, including Weka experiments, preprocessing steps, and model evaluation results, is available in the `reports` folder.

## Project Pipeline

1. Data Collection using Web Scraping
2. Data Cleaning and Preprocessing
3. Feature Engineering
4. Missing Value Handling
5. Outlier Detection and Treatment
6. Feature Scaling and Encoding
7. Model Training and Evaluation
8. Feature Selection
9. Dimensionality Reduction using PCA
10. Performance Comparison

## Dataset Features

The dataset contains information about mobile phones, including:

- Mobile Name
- Brand
- Price
- RAM
- Storage Capacity
- Color
- Additional Specifications

## Machine Learning Models

### Linear Regression
Used as a baseline regression model for mobile price prediction.

### Random Forest Regressor
Provided the best overall performance with the lowest prediction error.

### Support Vector Regressor (SVR)
Used to compare performance with other regression approaches.

## Results

| Model | MAE | RMSE |
|---------|---------|---------|
| Linear Regression | 1080.81 | 1901.11 |
| Random Forest | 39.78 | 355.79 |
| SVR | 25059.64 | 33345.78 |

## Best Model

The Random Forest Regressor achieved the best predictive performance and was selected as the final model for mobile price prediction.

## Feature Selection

Correlation analysis was applied to identify the most relevant features and reduce redundancy in the dataset.

## PCA Analysis

Principal Component Analysis (PCA) was used to reduce dimensionality while preserving the most important information in the dataset.

## Weka Experiments

Weka was used to perform additional data mining experiments, model evaluation, and result comparison. The complete analysis and screenshots are included in the project report.

## Technologies Used

- Python
- Selenium
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Weka

## Author

**Nagham Zidiah**

Data Science & Artificial Intelligence Student
