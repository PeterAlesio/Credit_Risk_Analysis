# Credit_Risk_Analysis
## Overview
The overview of this project was to build prediciton model for the 2019 loan stats csv to determine the likelihood of someone being denied a loan.
To do this I will be creating a couple of models using a oversampling method and used a smote algorithm. I also undersampled the data using a clustercentroid algorithm.Afterwards I compared the models to minimize the bias within them.

## Results of the Algorithms
- Naive Random Oversampling results: Our balanced accuracy test it 64%, the precision for the high_risk has a very low positivity at 1% and the recall is 61%

- SMOTE oversampling results: the accuracy score is 62%, the precision for the high_risk loans has a low positvity again at 1% and recall is 66% overall

- Undersampling results: balanced accuracy score is 51% overall, the precision is at 99% and the recall is 44%

- Combination(over and undersampling) results: balanced accuracy score is 54.7% the precision is 99% and the recall is 58% overall

- Balanced Random Forest Classifier results: the accuracy score is 78% the precision is 99% and the recall is 89%

- Easy Ensemble AdaBoost Classifier results: the accuracy score is 92% the precision is 99% and the recall is 94%

## Summary

The easy ensemble adaboost is the best model to use as it has the highest accuracy compared to the other models at 92%. 
