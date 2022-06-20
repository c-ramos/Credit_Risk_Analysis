# Credit Risk Analysis
*Applying machine learning models to analyze credit card risk* 

## Overview of the Analysis
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Financial insitutions want to identify good candidates for loans and evaluate customer credit risk.

The objective of this project is to build and evaluate machine learning modules to provide a predictable, reliable loan experience. Imbalanced-learn and scikit-learn libraries were utilized to build models using resampling. Then, the data was oversampled using RandomOverSampler and SMOTE, and the data was undersampled using ClusterCentroids. The over and undersampling methods were combined using SMOTEENN. Lastly, two machine learning models, BalancedRandomForestClassifies and Easy EnsembleClassifier, were compared to predict credit risk.

## Results
1. Naive Random Oversampling

![Imgs/1.png](https://github.com/c-ramos/Credit_Risk_Analysis/blob/afbcb11dc8c0dcb208ef7dd0e264fdeb7be2d2bf/Imgs/1.png)

2. SMOTE Oversampling   

![Imgs/02_SMOTE.png](https://github.com/c-ramos/Credit_Risk_Analysis/blob/afbcb11dc8c0dcb208ef7dd0e264fdeb7be2d2bf/Imgs/02_SMOTE.png)

3. Cluster Centroid Undersampling

![Imgs/03_CLUSTERCENTROID.png](https://github.com/c-ramos/Credit_Risk_Analysis/blob/afbcb11dc8c0dcb208ef7dd0e264fdeb7be2d2bf/Imgs/03_CLUSTERCENTROID.png)

4. SMOTEENN Combination Sampling

![Imgs/04_SMOTEENN.png](https://github.com/c-ramos/Credit_Risk_Analysis/blob/afbcb11dc8c0dcb208ef7dd0e264fdeb7be2d2bf/Imgs/04_SMOTEENN.png)

5. Balanced Random Forest Classifier 

![Imgs/05_BRF.png](https://github.com/c-ramos/Credit_Risk_Analysis/blob/afbcb11dc8c0dcb208ef7dd0e264fdeb7be2d2bf/Imgs/05_BRF.png)

6. Easy Ensemble AdaBoost Classifier

![Imgs/06_EEC.png](https://github.com/c-ramos/Credit_Risk_Analysis/blob/afbcb11dc8c0dcb208ef7dd0e264fdeb7be2d2bf/Imgs/06_EEC.png)

## Summary 
All six models had a low precision rate for high risk . Easy Ensemble AdaBoost Classifier was the highest with 7% 
summary of results
recommendation of which nodel to use, or ther eis ino recommendation with a justification 
