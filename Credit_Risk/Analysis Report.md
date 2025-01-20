# Module 12 Report 

## Overview of the Analysis
The goal of this analysis was to evaluate machine learning models for predicting loan outcomes, focusing on identifying healthy loans (0) and high-risk loans (1). This analysis aimed to help the company mitigate financial risks by accurately classifying high-risk loans.

The goal of this analysis was to evaluate machine learning models for predicting loan outcomes, focusing on identifying healthy loans (0) and high-risk loans (1). This analysis aimed to help the company mitigate financial risks by accurately classifying high-risk loans.

### Dataset Overview
- Financial Information: The dataset contained information about loan applicants, including loan features and risk status.
- Prediction Goal: Predict whether a loan is high-risk (1) or healthy (0).
- Target Variable: loan_status
- Distribution:
   - 0 (Healthy Loans): Majority class.
   - 1 (High-Risk Loans): Minority class.

### Stages of Machine Learning Process
- Data Preparation:
Cleaned and preprocessed data to handle missing values and imbalances.
Split data into training and testing sets using an 80/20 split.

- Model Training:
Applied Logistic Regression as the primary classification algorithm.

- Model Evaluation:
Assessed the model’s performance using accuracy, precision, and recall metrics to determine how well it predicts both loan categories.


## Results

- Logistic Regression Model Performance
     -Accuracy Score: 0.99

- Precision Scores:
   - Healthy Loans (0): 1.00
   - High-Risk Loans (1): 0.84
     
- Recall Scores:
   - Healthy Loans (0): 0.99
   - High-Risk Loans (1): 0.94

## Summary

The logistic regression model performs exceptionally well for healthy loans (0), achieving perfect precision and near-perfect recall. This ensures that the model confidently and accurately identifies healthy loans. For high-risk loans (1), the model achieves strong recall, successfully identifying 94% of actual high-risk loans. However, its precision for high-risk loans is slightly lower at 0.84, indicating that some healthy loans are misclassified as high-risk.
If you do not recommend any of the models, please justify your reasoning.

## Recommendation
This model is recommended for deployment due to its overall strong performance and high accuracy. Its ability to correctly classify most high-risk loans is particularly valuable for minimizing financial losses. While slightly lower precision for high-risk loans means some false positives, this trade-off is acceptable given the model’s high recall, ensuring the majority of high-risk loans are flagged. Further enhancements, such as addressing class imbalance with oversampling or class weighting, could improve precision for high-risk loans in future iterations.

By effectively predicting loan outcomes, this model can support data-driven decision-making and risk management within the company.
