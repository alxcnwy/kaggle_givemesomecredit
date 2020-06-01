<h1> Give Me Some Credit - Kaggle Competition </h1>

Kaggle competition to "improve on the state of the art in credit scoring by predicting the probability that somebody will experience financial distress in the next two years."

Models fit:
* Logistic Regression
* Random Forest
* XGBoost
* TPOT (AutoML in scikit-learn)

SMOTE is used to over-sample the data since it's very imbalanced but did not improve results and the XGBoost model learned using TPOT was found to perform best with a ROC AUC of 0.8649

https://www.kaggle.com/c/GiveMeSomeCredit