# Credit_Risk_Analysis
Supervised machine Learning : scikit-learn,imbalanced-learn 

## Overview of the analysis:

Use machine learning to solve real-world challenge - Credit card risk.

As good loans easily outnumber risky loans, Credit risk dataset is an inherently unbalanced. In this project is to employ different techniques to train and evaluate models with unbalanced classes, to predict whether someone is low or high risk status. 

 In this specific project steps 
 
* oversample the data using the RandomOverSampler and SMOTE algorithms
* undersample the data using the ClusterCentroids algorithm.
* use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. 
* Compare two new machine learning models that reduce bias        BalancedRandomForestClassifier and EasyEnsembleClassifier to predict credit risk.
## Resources

Software: Visual Studio Code, Jupyter Lab
Languages: Python
Libraries: numpy, pandas,scikit-learn,imbalanced-learn 
Data Sources: LoanStats_2019Q1.csv


## Results:

Naive Random Oversampling

* Accuracy Score: 67.42%
* Precision High Risk: 1%
* Precision Low Risk: 100%
* Recall High Risk: 74%
* Recall Low Risk: 61%



SMOTE Oversampling

* Accuracy Score: 66.23%
* Precision High Risk: 1%
* Precision Low Risk: 100%
* Recall High Risk: 63%
* Recall Low Risk: 69%

CLUSTER_CENTROID undersampling

* Accuracy Score: 54.42%
* Precision High Risk: 1%
* Precision Low Risk: 100%
* Recall High Risk: 69%
* Recall Low Risk: 40%

SMOTEENN under&over sampling

* Accuracy Score: 54.42%
* Precision High Risk: 1%
* Precision Low Risk: 100%
* Recall High Risk: 72%
* Recall Low Risk: 57%


Balanced Random Forest Classifier

* Accuracy Score: 75.58%
* Precision High Risk: 3%
* Precision Low Risk: 100%
* Recall High Risk: 62%
* Recall Low Risk: 89%
  
  
Easy Ensemble AdaBoost classifier

* Accuracy Score: 93.16%
* Precision High Risk: 9%
* Precision Low Risk: 100%
* Recall High Risk: 92%
* Recall Low Risk: 94%





## Summary:

High risk loan require higher sensitivite rate in order to let least amount of high risk loans underdected.
Here is the Top 3 sensitivity/recall rate for high risk. 

1. Easy Ensemble AdaBoost classifier 92%
2. Naive Random Oversampling 74%
3. SMOTEENN under&over sampling 72%
   
Top 3 sensitivity/recall rate for low risk.
1. Easy Ensemble AdaBoost classifier 94%
2. Balanced Random Forest Classifier 89%
3. SMOTE Oversampling 69%

Top 3 Accuracy Score models.
1. Easy Ensemble AdaBoost classifier 93.16%
2. Balanced Random Forest Classifier 75.58%
3. Naive Random Oversampling 67.42%

Based on the ranking on those three main sector, I think the Easy Ensemble AdaBoost classifier perfom the best to predict the credit risk.


   







