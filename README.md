# Credit Risk Analysis

## Overview of Analysis
Good credit and loans vastly outnumber risky credit and loans. This analysis takes this unbalance into consideration and tests different algorithims to see which method provides an optimal result for determining whether or not a customer should be approved for a loan.

## Results

### Naive Random Oversampling

The stats for Naive Random Oversampling are as follows and can be observed in the following screen shots.
- Balanced Accuracy Score: **0.68**
- Precision
  - High Risk: **0.01**
  - Low Risk: **1.00**
- Recall
  - High Risk: **0.72**
  - Low Risk: **0.60**

#### Naive Random Oversampling Accuracy  Score
![naive_accuracy](https://user-images.githubusercontent.com/102814578/184519917-017844f3-3a58-4c6a-81bf-01d5222c80ab.png)


####  Naive Random Oversampling Classifcation Report
![naive_random_oversampling](https://user-images.githubusercontent.com/102814578/184519918-9ff3f2eb-4c39-4b78-91a4-cbc235168694.png)



### SMOTE OverSampling

The stats for SMOTE OverSampling are as follows and can be observed in the following screen shots.
- Balanced Accuracy Score: **0.66**
- Precision
  - High Risk: **0.01**
  - Low Risk: **1.00**
- Recall
  - High Risk: **0.61**
  - Low Risk: **0.72**
  
#### SMOTE Oversampling Accuracy  Score
![SMOTE_accuracy](https://user-images.githubusercontent.com/102814578/184519921-664bca5c-cd91-40f0-a644-9e63fd66e791.png)


#### SMOTE Oversampling Classifcation Report
![SMOTE](https://user-images.githubusercontent.com/102814578/184519920-191ab447-4294-4983-866b-615f7f5709ad.png)



### Undersampling

The stats for Undersampling are as follows and can be observed in the following screen shots.
- Balanced Accuracy Score: **0.54**
- Precision
  - High Risk: **0.01**
  - Low Risk: **1.00**
- Recall
  - High Risk: **0.69**
  - Low Risk: **0.40**
 
#### Undersampling Accuracy  Score
![undersampling_accuracy](https://user-images.githubusercontent.com/102814578/184519923-df25d468-b3ba-451c-abd1-cbfe23792903.png)


#### Undersampling Classifcation Report
![undersampling](https://user-images.githubusercontent.com/102814578/184519922-90a373c0-ab65-4c43-bbd0-7fa8c3b9a3ad.png)



### Combination (Over and Under) Sampling

The stats for Combination (Over and Under) Sampling are as follows and can be observed in the following screen shots.
- Balanced Accuracy Score: **0.650**
- Precision
  - High Risk: **0.01**
  - Low Risk: **1.00**
- Recall
  - High Risk: **0.72**
  - Low Risk: **0.57**
 
#### Combination (Over and Under) Sampling Accuracy  Score
![combination_accuracy](https://user-images.githubusercontent.com/102814578/184519927-f64e7523-e3ee-422f-b50a-7146c68003cf.png)


#### Combination (Over and Under) Sampling Classifcation Report
![combination_over_undersampling](https://user-images.githubusercontent.com/102814578/184519931-bb103fea-9d57-4797-bcec-b417a07f1c5a.png)



### Balanced Random Forest Classifier

The stats for Balanced Random Forest Classifier are as follows and can be observed in the following screen shots.
- Balanced Accuracy Score: **0.68**
- Precision
  - High Risk: **0.88**
  - Low Risk: **1.00**
- Recall
  - High Risk: **0.37**
  - Low Risk: **1.00**
 
#### Balanced Random Forest Classifier Accuracy  Score
![balanced_random_forest_accuracy](https://user-images.githubusercontent.com/102814578/184519946-8e5b604a-1599-4f49-aaae-cb04678d697b.png)


#### Balanced Random Forest Classifier Classifcation Report
![balanced_random_forest](https://user-images.githubusercontent.com/102814578/184519940-88e7fb40-68e6-4045-ae12-e6854e9f8dd6.png)



### Easy Ensemble AdaBoost Classifier

The stats for Easy Ensemble AdaBoost Classifier are as follows and can be observed in the following screen shots.
- Balanced Accuracy Score: **0.93**
- Precision
  - High Risk: **0.07**
  - Low Risk: **1.00**
- Recall
  - High Risk: **0.91**
  - Low Risk: **0.95**
 
#### Easy Ensemble AdaBoost Classifier Accuracy  Score
![ez_accuracy](https://user-images.githubusercontent.com/102814578/184519949-e6cea24f-c81d-42a2-83a0-80e29524f705.png)


#### Easy Ensemble AdaBoost Classifier Classifcation Report
![ez_ensemble](https://user-images.githubusercontent.com/102814578/184519950-97955ef2-9c63-4bc1-9aaa-7bae8a6a4fba.png)



## Summary

Among the resampling methods, the precision did not change significantly between the 4 models. 
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
