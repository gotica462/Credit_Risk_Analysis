# Credit_Risk_Analysis

## Overview of the Analysis

  In this project we will apply machine learning to solve a real-world challenge: credit card risk. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, we'll employ different techniques to train and evaluate models with unbalanced classes. We will use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.
  Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, we’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, we’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, we’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. 
 
-Note (Had to do the code in collab becuase Jupyter Notebook was not loading the code ([image](https://github.com/gotica462/Credit_Risk_Analysis/blob/main/problem2.png))

## Results

### Naive Random Oversampling 

See below for the balanced accuracy score and imbalanced classification report

![image](https://github.com/gotica462/Credit_Risk_Analysis/blob/main/Resources/Naive%20Oversampling%201.png)

![image](https://github.com/gotica462/Credit_Risk_Analysis/blob/main/Resources/Naive%20Oversamplin%20precision%20report.png)

The balanced accuracy score is 66%, the recall score is 67% and the F1 score is 80%

### SMOTE Oversampling

See below for the balanced accuracy score and imbalanced classification report

![image](https://github.com/gotica462/Credit_Risk_Analysis/blob/main/Resources/SMOTE%20Oversampling%20Accuracy.png)

![image](https://github.com/gotica462/Credit_Risk_Analysis/blob/main/Resources/SMOTE%20Oversampling%20precision%20report.png)

The balanced accuracy score is 66%, the recall score is 66% and the F1 score is 79%

### Cluster Centroids Undersampling 

See below for the balanced accuracy score and imbalanced classification report

![image](https://github.com/gotica462/Credit_Risk_Analysis/blob/main/Resources/Cluster%20Centroid%20accuracy.png)

![image](https://github.com/gotica462/Credit_Risk_Analysis/blob/main/Resources/cluster%20centroid%20precision%20report.png)


### SMOTEEN (Combination of Over and Under Sampling)

See below for the balanced accuracy score and imbalanced classification report

![image](https://github.com/gotica462/Credit_Risk_Analysis/blob/main/Resources/SMOTEENN%20accuracy%20report.png)

![image](https://github.com/gotica462/Credit_Risk_Analysis/blob/main/Resources/SMOTEENN%20precision%20report.png)

###  Balanced Random Forest Classifier

See below for the balanced accuracy score and imbalanced classification report

![image](https://github.com/gotica462/Credit_Risk_Analysis/blob/main/Resources/Random%20Forest%20Accuracy%20.png)

![image](https://github.com/gotica462/Credit_Risk_Analysis/blob/main/Resources/Random%20Forest%20Precision%20Report.png)

### Easy Ensemble AdaBoost Classifier

See below for the balanced accuracy score and imbalanced classification report

![image](https://github.com/gotica462/Credit_Risk_Analysis/blob/main/Resources/Easy%20Ensemble%20Accuracy.png)
![image](https://github.com/gotica462/Credit_Risk_Analysis/blob/main/Resources/SMOTEENN%20precision%20report.png)















Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.
