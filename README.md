# Credit Risk Analysis

## Challenge Overview
You are to oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Finally, you’ll evaluate the performance of these models.

## Resources
- LoanStats_2019Q1.csv
- Software: Jupyter Notebook 6.0.3, Python 3.7.7, Visual Studio Code 1.47.2

## Challenge Results

| **Oversampling** | **Smote** |
|:----------------:|:---------:|
| ![oversampling](images/oversampling.png) | ![smote](images/smote.png) |
| ![over_score](images/over_score.png) | ![smote_score](images/smote_score.png) |
| **Undersampling** | **Smoteenn** |
| ![undersampling](images/undersampling.png) | ![smoteenn](images/smoteenn.png) |
| ![under_score](images/under_score.png) | ![smoteenn_score](images/smoteenn_score.png) |
| **Random Forest** | **Adaboost** |
| ![random_forest](images/random_forest.png) | ![adaboost](images/adaboost.png) |
| ![forest_score](images/forest_score.png) | ![adaboost_score](images/adaboost_score.png) |

- Oversampling has a balanced accuracy score of **.6466**, precision of **.99**, and a recall score of **.55**
- Undersampling has a balanced accuracy score of **.5442**, precision of **.99**, and a recall score of **.44**
- Smote has a balanced accuracy score of **.6624**, precision of **.99**, and a recall score of **..69**
- Smoteenn has a balanced accuracy score of **.6401**, precision of **.99**, and a recall score of **.58**
- Random_forest has a balanced accuracy score of **.7885**, precision of **.99**, and a recall score of **.87**
- Adaboost has a balanced accuracy score of **.9317**, precision of **.99**, and a recall score of **.94**

## Challenge Summary
All 6 machine learning models are great to use with varying degrees of accuracy and efficiency. A recommendation would be the Adaboost model as it has the highest accuracy, precision, and recall score out of the 6 models shown here.
