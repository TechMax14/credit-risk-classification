# credit-risk-classification
* HW15
* See credit_risk_classification.ipynb in the Credit_Risk file

  
# Machine Learning Model Performance Report (Module 12)

## Overview of the Analysis

The purpose of this analysis was to develop and evaluate machine learning models to predict loan risk based on financial information. The dataset included variables related to loans, and the goal was to predict whether a loan is healthy (0) or high-risk (1). The analysis involved stages such as data preprocessing, model training, and evaluation. Logistic Regression and oversampling techniques were employed to address the imbalanced nature of the dataset.

## Results

### Logistic Regression Model (Without Oversampled Data)

- **Accuracy Score:** 99%
- **Precision Scores:**
  - Label 0 (Healthy Loan): 100%
  - Label 1 (High-Risk Loan): 85%
- **Recall Scores:**
  - Label 0: 99%
  - Label 1: 91%

### Logistic Regression Model (With Oversampled Data)

- **Accuracy Score:** 99%
- **Precision Scores:**
  - Label 0 (Healthy Loan): 100%
  - Label 1 (High-Risk Loan): 84%
- **Recall Scores:**
  - Label 0: 99%
  - Label 1: 99%

## Summary

Both Logistic Regression models demonstrate excellent performance in predicting loan risk. The model with oversampled data achieves higher recall for the high-risk loans, addressing the imbalanced nature of the dataset. The choice between the two models depends on the specific business context and the importance of minimizing false positives or false negatives.

### Recommendation

- If balanced precision and recall are crucial, the Logistic Regression model without oversampled data may be suitable.
- If addressing the imbalanced nature of the dataset and achieving high recall for high-risk loans are top priorities, the Logistic Regression model with oversampled data is recommended.

In conclusion, both models provide reliable predictions, and the choice depends on the business objectives and tolerance for false positives or false negatives.

