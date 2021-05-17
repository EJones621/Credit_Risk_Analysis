# Credit_Risk_Analysis
Supervised Machine Learning and Credit Risk

## Overview 
In this project we used a credit card dataset from LendingClub which is a peer-to-peer lending services company, and used a supervised machine learning model to review the credit risk. RandomOverSampler & SMOTE were used to oversample the data. The undersampled data we used ClusterCentroids. SMOTEENN was a combinatorial approach of over and under sampling. We compared two new machine learning models that are used to reduce bias which are BalancedRandomForest & EasyEnsembleClassifer. 

## Results
The following results show a summary of the different models.

![BalancedRandomForest](https://github.com/EJones621/Credit_Risk_Analysis/blob/main/Resources/BalancedRandomForest.png)

![ClusterCentroids](https://github.com/EJones621/Credit_Risk_Analysis/blob/main/Resources/ClusterCentroids.png)

![EasyEnsembleClassifer](https://github.com/EJones621/Credit_Risk_Analysis/blob/main/Resources/EasyEnsembleClassifier.png)

![RandomOverSample](https://github.com/EJones621/Credit_Risk_Analysis/blob/main/Resources/RandomOverSample.png)

![SMOTE](https://github.com/EJones621/Credit_Risk_Analysis/blob/main/Resources/SMOTE.png)

![SMOTEENN](https://github.com/EJones621/Credit_Risk_Analysis/blob/main/Resources/SMOTEENN.png)

And then finally the summary table:

![SummaryTable](https://github.com/EJones621/Credit_Risk_Analysis/blob/main/Resources/SummaryTable.png)


## Summmary
Overall, the the results show that EasyEnsembleClassifier is the best model to test the credit risk. It has good predictions as seen in the recall score. Since there is a high-risk profile with smaller proportion of the overall dataset, precision is necessary for model to e of use. None of these models should be recommneded to predict credit worthless. 
