# Credit_Risk_Analysis

## Project Overview
The purpose of this analysis is to use Resampling Models, a SMOTEEN Algorithm and Ensemble Classifiers to predict credit risk for loans.

## Resources
- Data Source: cLoanStats_2019Q1.csv
- Software: Pyton 3.7, scikit-learn 1.0.1, scipy 1.7.1, numpy 1.20.3

## Results
###Naive Random Oversampling
- Balanced Accuracy Score: 0.6497536370265621
- Confusion Matrix:
![image_name](Resources/1.png)
- Imbalanced Classification Report
![image_name](Resources/2.png)

###SMOTE Oversampling
- Balanced Accuracy Score: 0.6443721269403855
- Confusion Matrix:
![image_name](Resources/3.png)
- Imbalanced Classification Report
![image_name](Resources/4.png)

###Cluster Centroids Undersampling
- Balanced Accuracy Score: 0.5292150629907619
- Confusion Matrix:
![image_name](Resources/5.png)
- Imbalanced Classification Report
![image_name](Resources/6.png)

###Combination Sampling SMOTEENN
- Balanced Accuracy Score: 0.6376117496807152
- Confusion Matrix:
![image_name](Resources/7.png)
- Imbalanced Classification Report
![image_name](Resources/8.png)SMOTEENN

###Balanced Random Forest Classifier
- Balanced Accuracy Score: 0.7877672625306695
- Confusion Matrix:
![image_name](Resources/9.png)
- Imbalanced Classification Report
![image_name](Resources/10.png)SMOTEENN

###Easy Ensemble AdaBoost Classifier
- Balanced Accuracy Score: 0.9316600714093861
- Confusion Matrix:
![image_name](Resources/11.png)
- Imbalanced Classification Report
![image_name](Resources/12.png)SMOTEENN


## Summary
