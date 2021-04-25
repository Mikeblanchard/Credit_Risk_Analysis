# Credit_Risk_Analysis

## Overview of the analysis:


Credit risk is very tough to predict. In this project we want to take a look at how all the factors in our loan_stats csv help predict whether someone is low or high risk status. One method that data scientists use for this type of issue is creating a model and then evaluate and train the models that they create. In this specific project we are using imbalanced-learn and scikit-learn libraries to build models and evalute them using a resampling method. In the first couple of models I oversampled the data using randomoversampler and smote algorithms and undersample the data with the clustercentroid algorithm. In the remaining models I used a combination approach to over and undersample the data using smoteenn. Finally, I compared two machine learning models that minimize bias, balancedrandomforestclassifier and easyensembleclassifier.

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
* 
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
*
***

## Summary
