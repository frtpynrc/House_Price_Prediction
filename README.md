# House Price Prediction

This repository contains the code for a house price prediction project. The goal is to develop a regression model to predict house prices based on various features.

## Overview

- `HousePricePrediction.ipynb`: Jupyter Notebook containing the main code for data analysis, preprocessing, model training, and evaluation.
- `HousePricePrediction.xlsx`: Dataset used for training and testing the models.

## Project Structure

- **Data Exploration and Preprocessing**: The notebook begins with an exploration of the dataset, identifying and handling categorical variables, and cleaning missing values.

- **Exploratory Data Analysis (EDA)**: Various aspects of the dataset are analyzed, including correlations between numeric features and the distribution of categorical features.

- **Data Cleaning**: The 'Id' column is dropped, and missing values in the 'SalePrice' column are filled with the mean. Rows with missing values are removed to create a clean dataset.

- **One-Hot Encoding**: Categorical variables are one-hot encoded using the `OneHotEncoder` from scikit-learn.

- **Splitting Dataset**: The dataset is split into training and validation sets for model training and evaluation.

- **Modeling and Evaluation**:
  - Support Vector Machine (SVM)
  - Random Forest Regressor
  - Linear Regression
  - CatBoost Regressor

## Dependencies

- Python 3
- Jupyter Notebooks
- Required Python packages: pandas, matplotlib, seaborn, scikit-learn, catboost

## Usage

1. Clone the repository:

```bash
git clone https://github.com/frtpynrc/House_Price_Prediction.git
