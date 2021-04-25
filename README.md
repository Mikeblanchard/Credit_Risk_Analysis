# Credit_Risk_Analysis

## Overview of the analysis:

The purpose of this analysis is to figure out with model best predicts credit risk. We are loooking at Naive Random Oversampling, SMOTE Oversampling, Undersampling, Combination Sampling, Balanced Random Forest Classifier and Easy Ensemble Classifier. We will evaluate and train each model with the data and compare the results. 

## Results

 &#8595; All dependencies Imported &#8595;
 
![](https://github.com/Mikeblanchard/Credit_Risk_Analysis/blob/main/Resources/Machine_1.png)
***

&#8595; Naive Random Oversampling &#8595;

![](https://github.com/Mikeblanchard/Credit_Risk_Analysis/blob/main/Resources/Machine_NAIVE_RANDOM_OVERSAMPLING_2.png)
* A balanced accuracy score of 66%
* High risk precision, recall and F1 scores of 1%, 62% and 2%. Low risk scores of 100%, 66% and 79%.
* A large difference between the support of high and low risk is dramatic
***

&#8595; SMOTE Oversampling &#8595;

![](https://github.com/Mikeblanchard/Credit_Risk_Analysis/blob/main/Resources/Machine_SMOTE_OVERSAMPLING_3.png)
* A balanced accuracy score of 66% 
* High risk precision, recall and F1 scores of 1%, 63% and 2%. Low risk scores of 100%, 66% and 79%.
* Very similar to the naive random oversampling model 
***

&#8595; Undersampling &#8595;

![](https://github.com/Mikeblanchard/Credit_Risk_Analysis/blob/main/Resources/Machine_UNDERSAMPLING_4.png)
* A balanced accuracy score of 45% 
* High risk precision, recall and F1 scores of 1%, 61% and 1%. Low risk scores of 100%, 45% and 62%.
* High number of false positives are affecting the sensitivity scores.
***

&#8595; Combination Sampling &#8595;

![](https://github.com/Mikeblanchard/Credit_Risk_Analysis/blob/main/Resources/Machine_COMBINATION_SAMPLING_5.png)
* A balanced accuracy score of 54% 
* High risk precision, recall and F1 scores of 1%, 69% and 1%. Low risk scores of 100%, 54% and 70%.
* Slightly higher accuracy score than the previous model, though unconvincing other values. 
***

&#8595; Balanced Random Forest Classifier &#8595;

![](https://github.com/Mikeblanchard/Credit_Risk_Analysis/blob/main/Resources/Machine_BALANCED_RANDOM_FOREST_CLASSIFIER_5.png)
* A balanced accuracy score of 91%
* High risk precision, recall and F1 scores of 4%, 67% and 7%. Low risk scores of 100%, 91% and 95%.
* Much fewer false positives have coalesced the recall and precision scores of the low risk group.
***

&#8595; Easy Ensemble AdaBoost Classifier &#8595;

![](https://github.com/Mikeblanchard/Credit_Risk_Analysis/blob/main/Resources/Machine_EASY_ENSEMBLE_ADABOOST_CLASSIFIER_6.png)
* A balanced accuracy score of 94% 
* High risk precision, recall and F1 scores of 7%, 91% and 14%. Low risk scores of 100%, 94% and 97%.
* All values approaching 100% and high F1 scores. 
***

## Summary

When trying to determine wich model best predicts risk, we want a good balance of recall, precision and accuracy. We can see that each model we used seemed to get better, further refining risk numbers. For this analysis, we have determined the Easy Enselmble Classifier to be best, due to its high accuracy and great balance of precision and recall. Perhaps this isn't surprising as it is a newer model that minimizes bias. 
