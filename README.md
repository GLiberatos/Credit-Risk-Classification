# Supervised Learning Challenge: Loan Risk Prediction

## Overview

This repository contains files for analyzing loan data using supervised learning techniques in Python. The primary goal is to train and evaluate models to predict loan risk, specifically focusing on the creditworthiness of borrowers. The main components include:

- **lending_data.csv**: A provided dataset containing financial information.
- **credit_risk_classification.ipynb**: Jupyter Notebook file with the analysis code.
- **report-template.md**: Markdown file presenting the analysis report.

## Navigation

### Resources
- **lending_data.csv**: Dataset for analysis.

### Files
- **credit_risk_classification.ipynb**: Jupyter Notebook containing the analysis code.
- **report-template.md**: Markdown file presenting the analysis report.

## Results

The analysis involves training and evaluating two machine learning models on the loan dataset. Here's a summary of the findings:

### Overview of the Analysis

1. **Purpose of the Analysis**: Evaluate machine learning algorithms to forecast loan risk.
2. **Financial Information**: Predict loan repayment statuses.
3. **Variable Information**: Dataset includes 75,036 low-risk loans and 2,500 high-risk loans.
4. **Machine Learning Process**: Data preprocessing, feature selection, model training, and evaluation.
5. **Methods Used**: Logistic Regression and resampling techniques.

### Results

#### Machine Learning Model 1:
- Balanced Accuracy Score: Approximately 0.952
- Precision and Recall Scores:
  - Precision (Class 0: Healthy loans): 1.00, (Class 1: High-risk loans): 0.85
  - Recall (Class 0: Healthy loans): 0.99, (Class 1: High-risk loans): 0.91
  - F1-Score (Class 0: Healthy loans): 1.00, (Class 1: High-risk loans): 0.88

#### Machine Learning Model 2:
- Balanced Accuracy Score: Approximately 0.993
- Precision and Recall Scores:
  - Precision (Class 0: Healthy loans): 1.00, (Class 1: High-risk loans): 0.84
  - Recall (Class 0: Healthy loans): 0.99, (Class 1: High-risk loans): 0.99
  - F1-Score (Class 0: Healthy loans): 1.00, (Class 1: High-risk loans): 0.91

### Summary

1. **Performance Comparison**: Model 2 outperforms Model 1 with higher balanced accuracy, recall, and F1-Score for high-risk loans.
2. **Problem Dependency**: Model choice depends on priorities and costs of false positives versus false negatives.
3. **Recommendation**: Model 2 is recommended for its superior performance in identifying high-risk loans effectively.

## Usage

To analyze the data:

1. Open **credit_risk_classification.ipynb** in Jupyter Notebook.
2. Ensure the resource and analysis directories are correctly set.
3. Run individual cells to view calculations and results.