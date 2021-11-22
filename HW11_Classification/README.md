# Homeowrk 11 - Risky Business

![Risk](Images/Financial-Risk-Management.png)

In this assignment, I'll build and evaluate several machine learning models to predict credit risk using data you'd typically see from peer-to-peer lending services. I will use the imbalanced-learn and Scikit-learn libraries to build and evaluate models using the two following techniques:

1. [Resampling](#Resampling)
2. [Ensemble Learning](#Ensemble-Learning)


## Notebook Files

[Resampling Starter Notebook](credit_risk_resampling.ipynb)

[Ensemble Starter Notebook](credit_risk_ensemble.ipynb)


## Resampling 

* Oversample the data using the Naive Random Oversampler and SMOTE algorithms.

* Undersample the data using the Cluster Centroids algorithm.

* Oversample and undersample the data using the SMOTEENN algorithim.

* Generate the Balance Accuracy Score, Confusion Matrix and Classification Report for all of the above methods.


### Classification Analysis - Resampling






## Ensemble Learning

### Balanced Random Forest

* Balanced Accuracy Score : 0.7624430424114966

* Confusion Matrix:

![score-forest](Images/acc_score_random_forest.png)

* Imbalanced Classification Report

![report](Images/report_random_forest.png)

* Feature Importance - Top 10

![feature-importance](Images/feature_importance.png)


### Classification Analysis - Ensemble Learning

1. Which model had the best balanced accuracy score?

    The Easy Ensemble Classifier: 0.925


2. Which model had the best recall score?

    The Easy Ensemble Classifier: 0.94 vs. 0.76


3. Which model had the best geometric mean score?

    The Easy Ensemble Classifier: 0.93 vs. 0.76


4. What are the top three features?

    total_rec_prncp	0.081656 <br>
    last_pymnt_amnt	0.068982 <br>
    total_rec_int	0.059083
