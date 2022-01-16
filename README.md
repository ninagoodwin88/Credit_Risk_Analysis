# Credit Risk Analysis
Jupyter Notebook, Python

## Overview of Project
 This project will use `imbalanced-learn` and `scikit-learn` libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, the data will be oversampled using `RandomOverSampler` and `SMOTE` algorithms, and undersampled using the `ClusterCentroids` algorithm. 
The combinatorial approach of over and undersampling will be used by performing the `SMOTEENN` algorithm. Next, the data will be compared using two new machine learning models that reduce bias, `BalancedRandomForestClassifier` and `EasyEnsembleClassifier`, to predict credit risk. Please see below for performance evaluation and written recommendations on whether the models should be used to pedict credit.




### DELIVERABLE RESULTS:
Below are the results from the various techniques used to predictive model for High-Risk loans.  


**SMOTEENN:**  

![d1](https://github.com/ninagoodwin88/Credit_Risk_Analysis/blob/main/Resources/Images/r4.png)

**SMOTE:**  

![d1](https://github.com/ninagoodwin88/Credit_Risk_Analysis/blob/main/Resources/Images/r2.png)

**RandomOverSample:**  

![d1](https://github.com/ninagoodwin88/Credit_Risk_Analysis/blob/main/Resources/Images/r1.png)

**ClusterCentroids:**  

![d1](https://github.com/ninagoodwin88/Credit_Risk_Analysis/blob/main/Resources/Images/r3.png)


**EasyEnsembleClassifier:**  

![d1](https://github.com/ninagoodwin88/Credit_Risk_Analysis/blob/main/Resources/Images/r6.png)

**BalancedRandomForestClassifier:**

![d1](https://github.com/ninagoodwin88/Credit_Risk_Analysis/blob/main/Resources/Images/r5.png)



## SUMMARY

For all models, utlizing **EasyEnsembleClassifier** is the most effective. Provides a highest Score for all Risk loans.
The precision is low or none for all the models. In General, above the 90% of the current analysis, utlizing **EasyEnsembleClassifier** will perform a High-Risk loan precision as a great value for the overall analysis. 



