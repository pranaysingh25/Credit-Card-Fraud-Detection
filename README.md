# Credit-Card-Fraud-Detection
Build a model to detect Fraud Credit Card Transactions over a dataset containing 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions(492 frauds out of 284,807 transactions). 

The model was created by first doing random oversampling using SMOTE and then fitting the a machine learning model at the re-sampled data. The best performance was given by Random Forest Classifier and the evaluation metrics were Precision, Recall and AUC score. 

The model was trained using cross-validation at the time of over sampling to avoid data leakage and then tested on raw and skewed data, giving a precision of 90% and Recall of 70%. The AUC score came out to be 85%
