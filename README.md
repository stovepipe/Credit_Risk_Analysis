# Credit_Risk_Analysis
Evaluating the performance of various machine learning models to predict credit risk.

## Overview of the Analysis

### Purpose
The purpose of this analysis was to compare 6 different machine learning algorithms and accuracy scores using a credit risk dataset. Resulting analysis reveals model performance and ultimate implementation.

## Results
Using the 6 models, the following metrics were recorded:

Naive Over-Sampling + Logisitic Regression:<br>
Accuracy: 66.7%<br>
Confusion Matrix:<br>
![alt text](https://github.com/stovepipe/Credit_Risk_Analysis/blob/main/Resources/1ml.png)<br>
Precision: 99%<br>
Recall: 67%<br>
____________________________
SMOTE Over-Sampling + Logistic Regression:<br>
Accuracy: 66.4%<br>
Confusion Matrix:<br>
![alt text](https://github.com/stovepipe/Credit_Risk_Analysis/blob/main/Resources/2ml.png)<br>
Precision: 99%<br>
Recall: 66%<br>
___________________________
Centroid Clusters Under-Sampling + Logistic Regression:<br>
Accuracy: 44.6%<br>
Confusion Matrix:<br>
![alt text](https://github.com/stovepipe/Credit_Risk_Analysis/blob/main/Resources/3ml.png)<br>
Precision: 99%<br>
Recall: 45%<br>
__________________________
SMOTEENN Over and Under Sampling + Logistic Regression:<br>
Accuracy: 54%<br>
Confusion Matrix:<br>
![alt text](https://github.com/stovepipe/Credit_Risk_Analysis/blob/main/Resources/4ml.png)<br>
Precision: 99%<br>
Recall: 54%<br>
___________________________
Balanced Random Forest Classifier:<br>
Accuracy: 80.1%<br>
Confusion Matrix:<br>
![alt text](https://github.com/stovepipe/Credit_Risk_Analysis/blob/main/Resources/5ml.png)<br>
Precision: 99%<br>
Recall: 90%<br>
__________________________
Easy Ensemble AdaBoost Classifier:<br>
Accuracy: 92.3%<br>
Confusion Matrix:<br>
![alt text](https://github.com/stovepipe/Credit_Risk_Analysis/blob/main/Resources/6ml.png)<br>
Precision: 99%<br>
Recall: 94%<br>

## Summary

### Conclusion
In reviewing the results of the 6 models, the ensemble learning algorithms appear to have the highest accuracy in regards to their predictions.

The logisitic regression models had accuracy scores significantly less than the ensemble algorithms. However, due to the financial nature of the data and the implications involved in credit card lending, I would still struggle to recommend any of these models, because, while good, they still allow for a significant amount of false negatives resulting in credit being issued to high risk loans.
