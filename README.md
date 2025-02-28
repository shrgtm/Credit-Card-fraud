# Credit Card Fraud Detection

## Overview
Credit card fraud is a critical issue in the financial industry, and detecting fraudulent transactions is a key challenge. This project analyzes a dataset of credit card transactions to uncover patterns in fraudulent activities using statistical analysis and visualizations. The dataset consists of over 284,000 transactions, with only 0.17% classified as fraudulent.

## Dataset Information
The dataset contains anonymized features (V1 to V28) transformed using Principal Component Analysis (PCA) for privacy reasons. It also includes transaction amount and time, with a label indicating whether the transaction was fraudulent (1) or legitimate (0).

## Analysis and Visualization

### Univariate Analysis
- The distribution of transaction amounts is visualized using a histogram, showing that most transactions have small amounts, with a few high-value transactions standing out as potential risks.
- A box plot helps in detecting outliers in transaction amounts, highlighting potential fraud cases.
- A count plot of the fraud class reveals a highly imbalanced dataset, where fraudulent transactions are rare.

### Multivariate Analysis
- A heatmap of feature correlations provides insights into how different variables relate to each other.
- A scatter plot of transaction time vs. amount reveals no clear trend in fraud occurrence over time.
- A pair plot compares different features across fraud and non-fraud transactions, identifying patterns in PCA-transformed variables.

## Key Findings
Fraudulent transactions exhibit distinct patterns in some PCA-transformed features, making it possible to train machine learning models for automated fraud detection. However, due to the severe class imbalance, data balancing techniques such as SMOTE may be required to improve model performance.

## Next Steps
- Implement machine learning models for fraud detection.
- Use feature engineering to improve fraud detection accuracy.
- Deploy a real-time fraud detection system to enhance financial security.

This project serves as a strong foundation for understanding fraud detection in finance and cybersecurity, providing valuable insights into data-driven decision-making.

