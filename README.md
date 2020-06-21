# Credit Risk Machine Learning Challenge using Supervised Machine Learning
##Objective
The goal of this Challenge was to build and compare multiple machine learning models to assess credit risk.  Data was pulled from Lending Club.
* Data Preparation required that I resample the data as the number of high risk loans was proportionally very small, a mere .5%  
* Specifically, different Oversampling and Undersampling Algorithms were utilized and then evaluated.  
    * Naive Random Oversampling Algorithm
    * SMOTE Oversampling Algorithm
    * Cluster Centroids Undersampling Algorithm
    * SMOTEENN Combination Algorithm
* A Logistic Regression Model was run on both datasets.

##Results
Naive Random Oversampling achieved the best results.

###Naive Random Oversampling Algorithm 
    <ul>
    <li>68.9% Balanced Accuracy</li>
    <li> 99% Precision</li>
    <li>66% Sensitivity</li>
###SMOTE Oversampling Algorithm
    * 65.6% Accuracy
    * 99% Precision
    * 68% Sensitivity
###Cluster Centroids Undersampling Algorithm
    * 65.6% Accuracy
    * 99% Precision
    * 41% Sensitivity
###SMOTEENN Combination Algorithm
    * 53.4% Accuracy
    * 99% Precision
    * 58% Sensitivity