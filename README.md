# Credit_Risk_Analysis

## Overview of the analysis:


Credit risk is very tough to predict. In this project we want to take a look at how all the factors in our loan_stats csv help predict whether someone is low or high risk status. One method that data scientists use for this type of issue is creating a model and then evaluate and train the models that they create. In this specific project we are using imbalanced-learn and scikit-learn libraries to build models and evalute them using a resampling method. In the first couple of models I oversampled the data using randomoversampler and smote algorithms and undersample the data with the clustercentroid algorithm. In the remaining models I used a combination approach to over and undersample the data using smoteenn. Finally, I compared two machine learning models that minimize bias, balancedrandomforestclassifier and easyensembleclassifier.

## Results

 &#8595; All dependencies Imported &#8595;
 
![](https://github.com/Mikeblanchard/Credit_Risk_Analysis/blob/main/Resources/Machine_1.png)
***

&#8595; Naive Random Oversampling &#8595;

![](https://github.com/Mikeblanchard/Credit_Risk_Analysis/blob/main/Resources/Machine_NAIVE_RANDOM_OVERSAMPLING_2.png)
* wer
* dsf
* dfs
***

&#8595; SMOTE Oversampling &#8595;

![](https://github.com/Mikeblanchard/Credit_Risk_Analysis/blob/main/Resources/Machine_SMOTE_OVERSAMPLING_3.png)
*
*
*
***

&#8595; Undersampling &#8595;

![](https://github.com/Mikeblanchard/Credit_Risk_Analysis/blob/main/Resources/Machine_UNDERSAMPLING_4.png)
*
*
*
***

&#8595; Combination Sampling &#8595;

![](https://github.com/Mikeblanchard/Credit_Risk_Analysis/blob/main/Resources/Machine_COMBINATION_SAMPLING_5.png)
*
*
*
***

&#8595; Balanced Random Forest Classifier &#8595;

![](https://github.com/Mikeblanchard/Credit_Risk_Analysis/blob/main/Resources/Machine_BALANCED_RANDOM_FOREST_CLASSIFIER_5.png)
*
*
*
***

&#8595; Easy Ensemble AdaBoost Classifier &#8595;

![](https://github.com/Mikeblanchard/Credit_Risk_Analysis/blob/main/Resources/Machine_EASY_ENSEMBLE_ADABOOST_CLASSIFIER_6.png)
*
*
*
***

## Summary
