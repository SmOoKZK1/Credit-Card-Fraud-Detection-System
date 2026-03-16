# Credit-Card-Fraud-Detection-System

This project addresses the critical challenge of financial security by detecting fraudulent transactions in real-time. The primary technical hurdle was the extreme class imbalance (0.17% fraud), which was solved through advanced sampling techniques and ensemble learning.

1. Machine Learning Pipeline: Evaluated and optimized multiple classifiers including XGBoost, Random Forest, and Logistic Regression, ultimately achieving an F1-score of 0.94 and 99.96% accuracy.

2. Imbalanced Data Handling: Applied SMOTE (Synthetic Minority Over-sampling Technique) and Random UnderSampling to ensure the model could accurately identify rare fraudulent patterns without being biased toward legitimate transactions.

3. Optimization: Utilized GridSearchCV and RandomizedSearchCV for hyperparameter tuning, focusing on maximizing Recall and AUC-ROC to minimize costly false negatives (missed fraud).
