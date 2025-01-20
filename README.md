# credit-risk-classification

The purpose of this analysis is to evaluate a logistic regression model’s ability to predict loan outcomes, specifically distinguishing between healthy loans (0) and high-risk loans (1). Accurate predictions are critical for minimizing financial risk and optimizing lending decisions. The analysis focuses on key performance metrics, including accuracy, precision, and recall, to determine whether the model is reliable for real-world use. The logistic regression model performs exceptionally well in predicting loan outcomes for both healthy loans (0) and high-risk loans (1), as indicated by the classification report. The machine learning model’s performance is summarized as follows:

- Accuracy Score: 0.99 – The model correctly predicts 99% of loan outcomes.
- Precision Score:
- Healthy Loans (0): 1.00 – All predicted healthy loans are accurate.
- High-Risk Loans (1): 0.84 – 84% of predicted high-risk loans are correct.
- Recall Score:
- Healthy Loans (0): 0.99 – The model correctly identifies 99% of actual healthy loans.
- High-Risk Loans (1): 0.94 – The model captures 94% of actual high-risk loans.


The logistic regression model demonstrates excellent performance, particularly in predicting healthy loans with near-perfect precision and recall. For high-risk loans, the model performs well, achieving strong recall and good precision, though some healthy loans are misclassified as high-risk.

This model is recommended for company use because of its high accuracy and strong ability to identify high-risk loans, which minimizes the likelihood of overlooking problematic cases. Its high precision for healthy loans ensures efficient resource allocation. However, to address the slightly lower precision for high-risk loans, class imbalance mitigation techniques (e.g., oversampling or class weighting) could be applied in future iterations. Despite minor limitations, the model’s robust performance across key metrics justifies its deployment to support data-driven lending decisions.







