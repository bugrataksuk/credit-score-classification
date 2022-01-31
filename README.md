# User Classification based on Credit Score

- In this project, I am going to classify users who request loans from the bank as good or default based on their information encodded in bank's database. For the evaluation based, I will also evalueate our models on a cost matrix appraoch where we lose %15 our money if we missclassify a good user and all the money if we missclassify a default user. For descriptive analysis purposes, statistics of sample, missing value  analysis, adding dummy columns and checking unique values are steps I followed in this step. To attack the problem, I performed Repeated Cross Validation on different classifiers by tuning their parameters and check their results via error function I pass the classifiers. 

![image](https://user-images.githubusercontent.com/73999139/151794503-811401eb-518c-4077-9e66-c8340a288fd4.png)

## Models and Data Used 

- The data is provided by an anonymous bank . The relevant columns are hidden because of confidentialty. 
- The models used are: 
Random Forest : https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html
Penalized Logistic Regression : https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html#sklearn.linear_model.LogisticRegression
XGBoost with GridSearch : https://xgboost.readthedocs.io/en/stable/python/python_api.html

## Files

- "train.csv" includes the train and test datasets to test the pipeline 
- credit-score-classification.jpynb is the interactive python notebook inculidng codes
- Requirements.txt is the all libraries you need for the analysis

## Libraries 
```
pandas
numpy
seaborn 
matplotlib
scipy
sklearn
xgboost
```
## Author 

https://github.com/bugrataksuk
