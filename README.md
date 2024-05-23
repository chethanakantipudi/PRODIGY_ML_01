# House Prices Prediction

This repository contains a Jupyter Notebook for predicting house prices using a dataset from Kaggle. The workflow includes data preprocessing, exploratory data analysis, and implementing a Linear Regression model.

## Files

- `train.csv`: Training data containing features and target variable `SalePrice`.
- `test.csv`: Test data for which predictions need to be made.
- `House_Prices_Prediction.ipynb`: Jupyter Notebook with all steps for data preprocessing, EDA, and modeling.
- `README.md`: This file, providing an overview of the repository.

## Requirements

- Python 3.x
- Jupyter Notebook
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

## Usage

1. Clone the repository and navigate to the project directory.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Open the `House_Prices_Prediction.ipynb` notebook in Jupyter Notebook.
4. Run the cells sequentially to preprocess the data, perform exploratory data analysis, train the Linear Regression model, and make predictions on the test set.
5. The predictions for the test set will be saved to `submission.csv`.

## Overview

### Exploratory Data Analysis

- Handle missing values and visualize them.
- Summary statistics of the data.
- Distribution of the target variable (SalePrice).
- Correlation matrix and heatmap.
- Analysis of top 10 features correlated with SalePrice.
- Pairplot of top correlated features.
- Count plots and boxplots of categorical features against SalePrice.

### Data Preprocessing

- Handle missing values.
- Encode categorical features.
- Standardize numerical features.

### Model Training and Evaluation

- Train a Linear Regression model.
- Evaluate the model using RMSE.
- Plot predictions vs actual values.

### Making Predictions

- Generate predictions for the test data.
- Save the predictions to `submission.csv`.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
