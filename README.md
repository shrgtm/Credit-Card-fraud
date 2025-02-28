# Credit Card Fraud Detection

## Overview

This project focuses on detecting fraudulent credit card transactions using exploratory data analysis (EDA). The dataset contains anonymized transaction features (V1 to V28) along with `Time`, `Amount`, and a `Class` label (0 for non-fraudulent and 1 for fraudulent transactions). The primary objective is to analyze the data using univariate and multivariate techniques to identify patterns that can help in fraud detection.

## Dataset Information

- **Features V1 to V28**: Transformed using Principal Component Analysis (PCA) to protect user privacy.
- **Time**: Represents the elapsed time in seconds since the first transaction.
- **Amount**: Represents the transaction amount.
- **Class**: The target variable, where 0 indicates non-fraudulent transactions and 1 indicates fraudulent transactions.

## Exploratory Data Analysis (EDA)

### Univariate Analysis

- **Descriptive Statistics**: Summary of key statistics such as mean, median, and standard deviation.
- **Histogram of Amount**: Visualizes the distribution of transaction amounts, highlighting potential fraud-prone ranges.
- **Boxplot of Amount**: Detects outliers that might indicate fraudulent transactions.
- **Class Distribution**: Examines the imbalance in fraudulent and non-fraudulent transactions using a count plot.

### Multivariate Analysis

- **Correlation Heatmap**: Identifies relationships between variables to detect potential fraud-related patterns.
- **Scatter Plot (Time vs. Amount)**: Observes transaction behavior over time.
- **Pairplot**: Visualizes relationships between selected features, helping distinguish fraudulent transactions.

## Key Findings

- The dataset is highly imbalanced, with fraudulent transactions forming a very small percentage.
- Some PCA-transformed features exhibit patterns that differentiate fraud from non-fraud transactions.
- Fraudulent transactions tend to have specific distributions in certain features.

## Next Steps

- Implement machine learning models for fraud detection.
- Balance the dataset using techniques like SMOTE.
- Deploy a real-time fraud detection system.

This project provides valuable insights into financial fraud detection and is a foundational step towards developing AI-driven security solutions. By leveraging data analysis and machine learning, we can enhance fraud detection techniques and make online transactions safer for everyone.

