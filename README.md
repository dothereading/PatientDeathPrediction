# PatientDeathPrediction
Given patient demographic and hospitalization data, we predict (1) likelihood of patient death and (2) length of hospital stay in two different in-class kaggle competitions.

The two notebooks walk through an initial data analysis and feature engineering stage before diving into the algorithms. Most of the feature engineering and algorithms are done within an sklean-pipeline in order to maintain the accuracy of cross-validation in training the model.

* `KNN_SVM.ipynb` uses k-nearest neighbors and support vector machine methods to predict patient death (4th place with a score of 0.92077),
* `DecisionTrees.ipynb` uses random forests, xgboost, neural networks, and ensembel models to predict length of hospital stay (5th place). 
