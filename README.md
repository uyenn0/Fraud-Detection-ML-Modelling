# Fraud-Detection-ML-Modelling

The rise of malicious acts on Financial transactions, along with its complexity level, poses great threats for Financial Institutions, and challenges them to come up with better measures for detecting these behaviours. 

In terms of Machine Learning models, this problem goes beyond detecting patterns, but more of: finding "the needle in the haystack", as malicious acts volume tends to be way less compared to normal financial transactions. 

This project, thus, aims to deploy certain ML models in hope of finding out the optimal one to solve this problem

Dataset used: https://www.kaggle.com/competitions/ieee-fraud-detection/data

----
#### Core Problem: 
Fraud Cases: imbalaced ration compared to Normal Cases

In comparison between models: False Positives is still better than False Negatives (Negatives: 1, Positives: 0)

----
#### Base Model
Random Forest /
ROC-AUC score: 0.8806
  ##### Key Decision 
  1. Label Encoding over One-Hot (to avoid dimensionality explosion)
  2. Unknown category handling (assign -1 to unseen values)
