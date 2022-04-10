# Credit Risk Analysis

## Overview
This project uses a credit card credit dataset to predict credit risk using the RandomOverSampler, SMOTE, ClusterCentroids, SMOTEENN, BalancedRandomForestClassifier and EasyEnsembleClassifier algorithms. 

## Results
- RandomOverSampler has a balanced accuracy score of 0.57. For the high credit risk group, precision is 0.01, and recall is 0.52. For the low credit risk group, precision is 1.00, and recall is 0.62.
- SMOTE has a balanced accuracy score of 0.66. For the high credit risk group, precision is 0.01, and recall is 0.63. For the low credit risk group, precision is 1.00, and recall is 0.69.
- ClusterCentroids has a balanced accuracy score of 0.54. For the high credit risk group, precision is 0.01, and recall is 0.69. For the low credit risk group, precision is 1.00, and recall is 0.4.
- SMOTEENN has a balanced accuracy score of 0.65. For the high credit risk group, precision is 0.01, and recall is 0.72. For the low credit risk group, precision is 1.00, and recall is 0.57.
- BalancedRandomForestClassifier has a balanced accuracy score of 0.79. For the high credit risk group, precision is 0.03, and recall is 0.70. For the low credit risk group, precision is 1.00, and recall is 0.88.
- EasyEnsembleClassifier has a balanced accuracy score of 0.93. For the high credit risk group, precision is 0.09, and recall is 0.92. For the low credit risk group, precision is 1.00, and recall is 0.94.

## Summary
While assessing credit risk, the most important thing is to successfully identify as many individuals in the high-risk group as possible. This means that the best model for this purpose would have the highest recall value for the high-risk group. Therefore, the EasyEnsembleClassifier would be most effective, as 94% of the individuals identified as high-risk are correctly identified as such. 
