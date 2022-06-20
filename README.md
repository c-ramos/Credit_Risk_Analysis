# Credit Risk Analysis
*Applying machine learning models to analyze credit card risk* 

## Overview of the Analysis
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Financial insitutions want to identify good candidates for loans and evaluate customer credit risk.

The objective of this project is to build and evaluate machine learning modules to provide a predictable, reliable loan experience. Imbalanced-learn and scikit-learn libraries were utilized to build models using resampling. Then, the data was oversampled using RandomOverSampler and SMOTE, and the data was undersampled using ClusterCentroids. The over and undersampling methods were combined using SMOTEENN. Lastly, two machine learning models, BalancedRandomForestClassifies and Easy EnsembleClassifier, were compared to predict credit risk.

## Results
1. Naive Random Oversampling
    * Text

![Imgs/2.png](https://github.com/c-ramos/MechaCar_Statistical_Analysis/blob/cd156b340c72ef6d126412176590dbe812b2adbb/Imgs/2.png)

2. SMOTE Oversampling
    * Text
    
![Imgs/2.png](https://github.com/c-ramos/MechaCar_Statistical_Analysis/blob/cd156b340c72ef6d126412176590dbe812b2adbb/Imgs/2.png)

3. Cluster Centroid Undersampling
    * Text
    
![Imgs/2.png](https://github.com/c-ramos/MechaCar_Statistical_Analysis/blob/cd156b340c72ef6d126412176590dbe812b2adbb/Imgs/2.png)

4. SMOTEENN Combination Sampling
    * Text
    
![Imgs/2.png](https://github.com/c-ramos/MechaCar_Statistical_Analysis/blob/cd156b340c72ef6d126412176590dbe812b2adbb/Imgs/2.png)

5. Balanced Random Forest Classifier
    * Text
    
![Imgs/2.png](https://github.com/c-ramos/MechaCar_Statistical_Analysis/blob/cd156b340c72ef6d126412176590dbe812b2adbb/Imgs/2.png)

6. Easy Ensemble AdaBoost Classifier
    * Text
    
![Imgs/2.png](https://github.com/c-ramos/MechaCar_Statistical_Analysis/blob/cd156b340c72ef6d126412176590dbe812b2adbb/Imgs/2.png)


## Summary 
All six models had a low precision rate for high risk . Easy Ensemble AdaBoost Classifier was the highest with 7% 
summary of results
recommendation of which nodel to use, or ther eis ino recommendation with a justification 