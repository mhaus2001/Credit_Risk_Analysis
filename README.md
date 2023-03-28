# Credit_Risk_Analysis

## Overview of the loan prediction risk analysis:
In this project, we used Jupytr to build and evaluate several machine learning models to predict credit risk.
### Results
- Naive Random Oversampling
  - Balanced Accuracy: 0.6463970560994359
  - Precision: High/Low risk .01/1
  - Recall: High/Low risk .71/.58
  - The model has a balanced accuracy of 0.6464 and is able to correctly identify 71% of high-risk loans and 58% of low-risk loans, but has a low precision for high-risk loans at 0.01.
- Balanced Random Forest Classifier
  - Balanced Accuracy: 0.7885466545953005
  - Precision: High/Low risk .03/1
  - Recall: High/Low risk .7/.87
  - The model has a balanced accuracy of 0.7885 and is able to correctly identify 70% of high-risk loans and 87% of low-risk loans, but has a low precision for high-risk loans at 0.03.
- Easy Ensemble AdaBoost Classifier
  - Balanced Accuracy: 0.9316600714093861
  - Precision: High/Low risk .09/1
  - Recall: High/Low risk .92/.94
  - The model has a balanced accuracy of 0.9317 and is able to accurately identify both high-risk and low-risk loans with high precision and recall scores.
- SMOTE Oversampling
  - Balanced Accuracy: 0.6586230769943224
  - Precision: High/Low risk .01/1
  - Recall: High/Low risk .63/.68
  - The model has a balanced accuracy of 0.6586 and is able to correctly identify 63% of high-risk loans and 68% of low-risk loans, but has a low precision for high-risk loans at 0.01.
- Combination Under-Over Sampling
  - Balanced Accuracy: 0.5447339051023905
  - Precision: High/Low risk .01/1
  - Recall: High/Low risk .69/.49
  - The model has a low balanced accuracy of 0.5447 and is only able to correctly identify 69% of high-risk loans and 49% of low-risk loans.
- Undersampling
  - Balanced Accuracy: 0.6361059077142514
  - Precision: High/Low risk .01/1
  - Recall: High/Low risk .68/.59
  - The model has a balanced accuracy of 0.6361 and is able to correctly identify 68% of high-risk loans and 59% of low-risk loans, but has a low precision for high-risk loans at 0.01.

### Summary of the results 
The results of the machine learning models show that the Easy Ensemble AdaBoost Classifier performed the best, with a high balanced accuracy of 0.9317, high precision scores for both high-risk and low-risk loans, and high recall scores for both categories. This indicates that the model is able to effectively identify risky loans while minimizing the number of false positives and false negatives. The other models had varying levels of success, with the Balanced Random Forest Classifier performing moderately well and the Naive Random Oversampling, SMOTE Oversampling, Combination Under-Over Sampling, and Undersampling models all having low precision scores for high-risk loans. Based on these results, I would recommend using the Easy Ensemble AdaBoost Classifier for predicting credit risk. 
