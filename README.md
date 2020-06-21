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
    <li>1% High-Risk Precision</li>
    <li>72% High-Risk Recall</li>
    <li>The recall score may not be high enough to accurately predict high risk borrowers.</li>
    </ul>
<h3>SMOTE Oversampling Algorithm</h3>
    <ul>
    <li>65.6% Accuracy</li>
    <li>1% High-Risk Precision</li>
    <li>63% High-Risk Recall</li>
    <li>The SMOTE Algorithm has the lowest accuracy and recall rate and should not be utilized to predict high risk borrowers.</li>
    </ul>
<h3>Cluster Centroids Undersampling Algorithm</h3>
    <ul>
    <li>65.6% Accuracy</li>
    <li>1% High-Risk Precision</li>
    <li>66% High-Risk Recall</li>
    <li>The Cluster Centroids Undersampling Algorithm has a lower accuracy and recall rate than the Naive Random Oversampling Algorithm.</li>
    </ul>
<h3>SMOTEENN Combination Algorithm</h3>
    <ul>
    <li>53.4% Accuracy</li>
    <li>1% High-Risk Precision</li>
    <li>70% High-Risk Recall</li>
    </ul>