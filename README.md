# Credit Risk Analysis

## Overview
This project uses a credit card credit dataset to predict credit risk using the RandomOverSampler, SMOTE, ClusterCentroids, SMOTEENN, BalancedRandomForestClassifier and EasyEnsembleClassifier algorithms. 

## Results
- RandomOverSampler has a balanced accuracy score of 0.57. For the high credit risk group, precision is 0.01, and recall is 0.52. For the low credit risk group, precision is 1.00, and recall is 0.62.

![image](https://user-images.githubusercontent.com/93882635/163021052-59e7fe48-fa4e-4c24-9364-95f0db7938a5.png)

- SMOTE has a balanced accuracy score of 0.66. For the high credit risk group, precision is 0.01, and recall is 0.63. For the low credit risk group, precision is 1.00, and recall is 0.69.

![image](https://user-images.githubusercontent.com/93882635/163021622-ce6add06-fc1f-4b0f-b911-7d19436e0097.png)

- ClusterCentroids has a balanced accuracy score of 0.54. For the high credit risk group, precision is 0.01, and recall is 0.69. For the low credit risk group, precision is 1.00, and recall is 0.4.

![image](https://user-images.githubusercontent.com/93882635/163021276-48a0dbad-9e31-402a-b519-dc3455e303e5.png)

- SMOTEENN has a balanced accuracy score of 0.65. For the high credit risk group, precision is 0.01, and recall is 0.72. For the low credit risk group, precision is 1.00, and recall is 0.57.

![image](https://user-images.githubusercontent.com/93882635/163021779-10e70c4b-2813-4673-9c61-3a13e6cd187d.png)

- BalancedRandomForestClassifier has a balanced accuracy score of 0.79. For the high credit risk group, precision is 0.03, and recall is 0.70. For the low credit risk group, precision is 1.00, and recall is 0.88.

![image](https://user-images.githubusercontent.com/93882635/163021942-163cd0d8-58c8-4927-b434-bb6f2ab1ec33.png)

- EasyEnsembleClassifier has a balanced accuracy score of 0.93. For the high credit risk group, precision is 0.09, and recall is 0.92. For the low credit risk group, precision is 1.00, and recall is 0.94.

![image](https://user-images.githubusercontent.com/93882635/163022099-bce647a3-6a7e-453a-b5be-ab1f00ca0d77.png)


## Summary
While assessing credit risk, the most important thing is to successfully identify as many individuals in the high-risk group as possible. This means that the best model for this purpose would have the highest recall value for the high-risk group. Therefore, the EasyEnsembleClassifier would be most effective, as 94% of the individuals identified as high-risk are correctly identified as such. 
