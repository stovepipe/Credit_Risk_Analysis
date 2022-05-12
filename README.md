# Credit_Risk_Analysis
Evaluating the performance of various machine learning models to predict credit risk.

## Overview of the Analysis

### Purpose
The purpose of this analysis was to compare 6 different machine learning algorithms and accuracy scores using a credit risk dataset. Resulting analysis reveals model performance and ultimate implementation.

## Results
Using the 6 models, the following metrics were recorded:

Naive Over-Sampling + Logisitic Regression:
Accuracy: 66.7%
Confusion Matrix:
![alt text](https://github.com/stovepipe/Credit_Risk_Analysis/blob/main/Resources/1ml.png)
Precision: 99%
Recall: 67%
____________________________
SMOTE Over-Sampling + Logistic Regression:
Accuracy: 66.4%
Confusion Matrix:
![alt text](https://github.com/stovepipe/Credit_Risk_Analysis/blob/main/Resources/2ml.png)
Precision: 99%
Recall: 66%
___________________________
Centroid Clusters Under-Sampling + Logistic Regression:
Accuracy: 44.6%
Confusion Matrix:
![alt text](https://github.com/stovepipe/Credit_Risk_Analysis/blob/main/Resources/3ml.png)
Precision: 99%
Recall: 45%
__________________________
SMOTEENN Over and Under Sampling + Logistic Regression:
Accuracy: 54%
Confusion Matrix:
![alt text](https://github.com/stovepipe/Credit_Risk_Analysis/blob/main/Resources/4ml.png)
Precision: 99%
Recall: 54%
___________________________
Balanced Random Forest Classifier:
Accuracy: 80.1%
Confusion Matrix:
![alt text](https://github.com/stovepipe/Credit_Risk_Analysis/blob/main/Resources/5ml.png)
Precision: 99%
Recall: 90%
__________________________
Easy Ensemble AdaBoost Classifier:
Accuracy: 92.3%
Confusion Matrix:
![alt text](https://github.com/stovepipe/Credit_Risk_Analysis/blob/main/Resources/6ml.png)
Precision: 99%
Recall: 94%

## Summary

### Conclusion
In reviewing the results of the 6 models, the ensemble learning algorithms appear to have the highest accuracy in regards to their predictions.

The logisitic regression models had accuracy scores significantly less than the ensemble algorithms. However, due to the financial nature of the data and the implications involved in credit card lending, I would still struggle to recommend any of these models as the accuracy levels, because, while good, they still allow for a significant amount of false negatives resulting in credit being issued to high risk loans.