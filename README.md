# Credit Risk Classification

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of this analysis is to train and evaluate a model for assessing loan risk.
* Using various techniques, I analyzed a dataset of historical lending activity from a peer-to-peer lending services company.
* The goal is to build a model that can accurately identify the creditworthiness of borrowers.
* The variables I was trying to predict are: 'loan_status', checking the high risk and lower risk loans.
* The stages of machine learning I went through in this supervised learning activity were: Training and Testing Sets, creating a Logistic Regression Model, and writing my Credit Risk Analysis Report.

## Results
* Machine Learning Model:<br />
Accuracy Score: 0.966<br />
Precision Score:<br />
Class 0 (low-risk): 1.00<br />
Class 1 (high-risk): 0.86<br />
Recall Score:<br />
Class 0 (low-risk): 0.99<br />
Class 1 (high-risk): 0.94<br />

## Summary

### Best Performing Model
The Logistic Regression Model performs exceptionally well, with an overall accuracy of 96.6%. It shows perfect precision (1.00) for predicting low-risk loans (Class 0) and strong recall (0.99), indicating it almost always correctly identifies low-risk loans.<br />
For high-risk loans (Class 1), it achieves a precision of 0.86 and a recall of 0.94, indicating a good balance between correctly identifying high-risk loans and minimizing false positives.

### Importance of Performance Metrics
The importance of the model's performance depends on the specific business problem:

If it's more critical to accurately predict high-risk loans (Class 1): The high recall score (0.94) for Class 1 is particularly important, as it means the model correctly identifies 94% of high-risk loans. This reduces the risk of misclassifying high-risk loans as low-risk.
If accurately predicting low-risk loans (Class 0) is more critical: The model performs almost perfectly with a precision and recall close to 1.00, ensuring that low-risk loans are correctly identified with minimal error.

### Recommendation
Based on the balanced performance in both predicting low-risk and high-risk loans, I recommend using this Logistic Regression Model. Its high accuracy, combined with strong precision and recall scores for both classes, ensures reliable identification of both high-risk and low-risk loans. This model strikes a good balance, making it suitable for a variety of lending risk assessment needs.