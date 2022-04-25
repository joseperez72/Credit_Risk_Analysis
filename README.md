# Credit_Risk_Analysis

## Overview

In this analysis, we use six different machine learning models to see which ones best predicts credit risk using a dataset from LendingClub, a peer-to-peer lending services company. We look at diffent metrics, including balanced accuracy, recall, and precision scores, to infer the performance of these machine lerarning models. In this analysis, we use Python and Jupyter Notebook.

## Results

### Naive Random Oversampling

Balanced Accuracy Score: 64.975%\
Low Risk Precision Score: 100%\
High Risk Precision Score: 1%\
Low Risk Recall Socre: 68%\
High Risk Recall Socre: 62%

![oversampling](images/naive_random_oversampling.png)
![oversampling_report](images/oversampling_report.png)

### SMOTE Oversampling

Balanced Accuracy Score: 64.437%\
Low Risk Precision Score: 100%\
High Risk Precision Score: 1%\
Low Risk Recall Socre: 66%\
High Risk Recall Socre: 63%


![smote](images/smote_oversampling.png)
![smote_report](images/smote_report.png)

### Undersampling

Balanced Accuracy Score: 51.608%\
Low Risk Precision Score: 100%\
High Risk Precision Score: 1%\
Low Risk Recall Socre: 43%\
High Risk Recall Socre: 60%

![undersampling](images/undersampling.png)
![undersampling_report](images/undersampling_report.png)

### Combination Sampling

Balanced Accuracy Score: 63.761%\
Low Risk Precision Score: 1%\
High Risk Precision Score: 1%\
Low Risk Recall Socre: 57%\
High Risk Recall Socre: 70%

![combination](images/combination.png)
![combination_report](images/combination_report.png)

### Balanced Random Forest Sampling

Balanced Accuracy Score: 78.777%\
Low Risk Precision Score: 100%\
High Risk Precision Score: 4%\
Low Risk Recall Socre: 91%\
High Risk Recall Socre: 67%

![random_forest](images/random_forest.png)
![random_forest_report](images/forest_report.png)

### Easy Ensemble Classifier

Balanced Accuracy Score: 92.543%\
Low Risk Precision Score: 100%\
High Risk Precision Score: 7%\
Low Risk Recall Socre: 94%\
High Risk Recall Socre: 91%

![easy_ensemble](images/easy_ensemble.png)
![easy_ensemble_report](images/easy_report.png)

## Summary

After looking at all the metrics, the Easy Ensemble Classifier machine learning model produced the best metrics out of the other 5 machine learning models. Over and undersampling did not perform as well, as the balanced accuracy scores were all below 65%, and the recall scores were well under 70%. The ensemble methods did a lot better compared to the resampling models as these models do a good job of removing biases. The easy ensemble classifier machine learning model had a balanced accuracy score of 93% and recall scores of 94% and 91% for low and high risk loans, respectfully.