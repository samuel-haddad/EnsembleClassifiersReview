# Ensembles Classifiers Review
**Keywords:** Extra Trees, Randon Forrest, XGBoost, Churn, k-fold

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-035a7d?style=for-the-badge&logo=kaggle&logoColor=white)
![](https://api.visitorbadge.io/api/VisitorHit?user=samuel-haddad&repo=TreeClassifiersReview&countColor=#40e0d0)

## Introduction
After reviewing some issues related to tree models, such as Decision Trees, Randon Forrest, bagging, bootstrap, ensemble models, Gini Index..., I decided to do a practical exercise and chose three algorithms: Extra Trees, Randon Forrest XGBoost. It's not a study of models, but quick implementations of them just to practice on a different business problem.

It's worth noting that in this exercise I used a cross-validation technique known as k-fold.

I hope it will be useful to you and feel free to send me suggestions or corrections.

Best.

## Telco Costumer Churn

This will be a quick exercise in building classification models with the k-fold cross-validation technique. For this reason, we will not look very closely at data exploration and will do a simple treatment of missing values using the IterativeImputer library, a more sophisticated solution for replacing with regression. <br>

<br>**Dabase description:**<br>
https://community.ibm.com/community/user/businessanalytics/blogs/steven-macko/2019/07/11/telco-customer-churn-1113
