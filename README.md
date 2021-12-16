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
![image_name](https://github.com/zackzydonik/PyBer_Analysis/blob/f6894564f19d6fedf82ada604c65cb84ace959ca/analysis/Summary%20Table.png)
- Imbalanced Classification Report
![image_name](https://github.com/zackzydonik/PyBer_Analysis/blob/c41f0e475a23d605e8d5e7257c21816221167db7/analysis/PyBer_fare_summary.png)

###SMOTE Oversampling
- Balanced Accuracy Score: 0.6443721269403855
- Confusion Matrix:
![image_name](https://github.com/zackzydonik/PyBer_Analysis/blob/f6894564f19d6fedf82ada604c65cb84ace959ca/analysis/Summary%20Table.png)
- Imbalanced Classification Report
![image_name](https://github.com/zackzydonik/PyBer_Analysis/blob/c41f0e475a23d605e8d5e7257c21816221167db7/analysis/PyBer_fare_summary.png)

###Cluster Centroids Undersampling
- Balanced Accuracy Score: 0.5292150629907619
- Confusion Matrix:
![image_name](https://github.com/zackzydonik/PyBer_Analysis/blob/f6894564f19d6fedf82ada604c65cb84ace959ca/analysis/Summary%20Table.png)
- Imbalanced Classification Report
![image_name](https://github.com/zackzydonik/PyBer_Analysis/blob/c41f0e475a23d605e8d5e7257c21816221167db7/analysis/PyBer_fare_summary.png)

###Combination Sampling SMOTEENN
- Balanced Accuracy Score: 0.6376117496807152
- Confusion Matrix:
![image_name](https://github.com/zackzydonik/PyBer_Analysis/blob/f6894564f19d6fedf82ada604c65cb84ace959ca/analysis/Summary%20Table.png)
- Imbalanced Classification Report
![image_name](https://github.com/zackzydonik/PyBer_Analysis/blob/c41f0e475a23d605e8d5e7257c21816221167db7/analysis/PyBer_fare_summary.png)SMOTEENN

###Balanced Random Forest Classifier
- Balanced Accuracy Score: 0.7877672625306695
- Confusion Matrix:
![image_name](https://github.com/zackzydonik/PyBer_Analysis/blob/f6894564f19d6fedf82ada604c65cb84ace959ca/analysis/Summary%20Table.png)
- Imbalanced Classification Report
![image_name](https://github.com/zackzydonik/PyBer_Analysis/blob/c41f0e475a23d605e8d5e7257c21816221167db7/analysis/PyBer_fare_summary.png)SMOTEENN

###Easy Ensemble AdaBoost Classifier
- Balanced Accuracy Score: 0.9316600714093861
- Confusion Matrix:
![image_name](https://github.com/zackzydonik/PyBer_Analysis/blob/f6894564f19d6fedf82ada604c65cb84ace959ca/analysis/Summary%20Table.png)
- Imbalanced Classification Report
![image_name](https://github.com/zackzydonik/PyBer_Analysis/blob/c41f0e475a23d605e8d5e7257c21816221167db7/analysis/PyBer_fare_summary.png)SMOTEENN


## Summary
