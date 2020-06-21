<h1>Credit Risk Machine Learning Challenge using Supervised Machine Learning</h1>
<h2>Objective</h2>
The goal of this Challenge was to build and compare multiple machine learning models to assess credit risk.  Data was pulled from Lending Club.
<ul>
<li>Data Preparation required that I resample the data as the number of high risk loans was proportionally very small, a mere .5%  </li>
<li>Specifically, different Oversampling and Undersampling Algorithms were utilized and then evaluated. </li> 
    <ul>
    <li> Naive Random Oversampling Algorithm</li>
    <li> SMOTE Oversampling Algorithm </li>
    <li> Cluster Centroids Undersampling Algorithm </li>
    <li> SMOTEENN Combination Algorithm </li>
    </ul>
<li> A Logistic Regression Model was run on both datasets.</li>
</ul>

<h2>Results</h2>
Naive Random Oversampling achieved the best results.

<h3>Naive Random Oversampling Algorithm</h3>
    <ul>
    <li>68.9% Balanced Accuracy</li>
    <li> 99% Precision</li>
    <li>66% Sensitivity</li>
    </ul>
    <img src="https://github.com/ljkirchman/MachineLearning/blob/master/Naive_Oversampling_CF_Matrix.png" alt="Naive Oversampling Confusion Matrix">
<h3>SMOTE Oversampling Algorithm</h3>
    <ul>
    <li>65.6% Accuracy</li>
    <li>99% Precision</li>
    <li>68% Sensitivity</li>
    </ul>
<h3>Cluster Centroids Undersampling Algorithm</h3>
    <ul>
    <li>65.6% Accuracy</li>
    <li>99% Precision</li>
    <li>41% Sensitivity</li>
    </ul>
<h3>SMOTEENN Combination Algorithm</h3>
    <ul>
    <li>53.4% Accuracy</li>
    <li>99% Precision</li>
    <li>58% Sensitivity</li>
    </ul>