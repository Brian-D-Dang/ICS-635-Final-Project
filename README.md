# ICS-635-Final-Project

1. Does the project demonstrate techniques discussed in class?
   Utilizes cross-validation, hyperparameter tuning, regularization and reduce variance, 
3. Were the modeling choices reasonable?
   Yes, we utilize XGBoost classification and Logistic Regression as a base model to compare performances
5. Is the model performance evaluated?
   It is evaluated through KFold CV, and traversed through hyperparameter space.
   We also evaluate the performance by running a final test on a new dataset taking note of the precision, accuracy, recall, and f1 score
7. Is performance compared against alternative models?
   Yes it was compared to Logisitic Regression as a baseline model
9. What was adopted from existing projects, and how much is new? (And was this clearly explained?)
    What was adopted was the general process of training the dataset on XGBoost, but what was different was how we test the feature extraction from the paper and compare it to a new dataset to see if the trained dataset would be able to provide enough information to help determine if essays are synthetic or human made.
