# 102203621_Sampling

## Overview
This repository contains a solution for applying different sampling techniques to balance the class distribution of the **Credit Card Fraud Detection** dataset. Various machine learning models are tested to determine which sampling technique leads to the highest accuracy.

## Dataset
The dataset used is the **Creditcard_data.csv**. It contains features of credit card transactions and labels each one as either fraud or not fraud. The dataset is imbalanced, so sampling techniques are applied to address this issue.

## Sampling Techniques
Five different sampling techniques were applied to balance the dataset:
- **Sampling1** (10% sample size)
- **Sampling2** (20% sample size)
- **Sampling3** (30% sample size)
- **Sampling4** (40% sample size)
- **Sampling5** (50% sample size)

## Machine Learning Models
The following models were tested:
- **M1**: Logistic Regression
- **M2**: Random Forest
- **M3**: Support Vector Classifier (Linear Kernel)
- **M4**: Support Vector Classifier (RBF Kernel)
- **M5**: Random Forest (200 Estimators)

## Accuracy Results

| Model                             | 10%       | 20%       | 30%       | 40%       | 50%       |
|-----------------------------------|-----------|-----------|-----------|-----------|-----------|
| **Logistic Regression**           | 0.9355    | 0.9180    | 0.8696    | 0.8443    | 0.8758    |
| **Random Forest**                 | 0.9032    | 0.9672    | 0.9565    | 1.0000    | 1.0000    |
| **SVC (Linear)**                  | 0.9677    | 0.8852    | 0.8478    | 0.8689    | 0.9216    |
| **SVC (RBF)**                     | 0.5484    | 0.7213    | 0.6739    | 0.6557    | 0.6601    |
| **Random Forest (200 Estimators)**| 0.9677    | 0.9836    | 0.9565    | 0.9918    | 1.0000    |

## Best Results
- **Best Model**: Random Forest
- **Best Sampling Technique**: 40%
- **Best Accuracy**: 1.0000

## Conclusion
- The **Random Forest** model with the **40% sampling** technique gave the highest accuracy of **1.0000**.
