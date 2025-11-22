# Predicting-Customer-Flight-Booking-Completion
This project leverages a historical customer booking dataset to predict the likelihood of bookings being completed. The workflow includes data cleaning, exploratory data analysis (EDA), feature engineering, and training a Random Forest Classifier to identify key drivers of booking completion.

Problem: Can we accurately predict which customers will complete their flight bookings?  
Business Value: Helps travel companies optimize marketing spend, target high-likelihood customers with incentives, and forecast demand more accurately.   
  
Data & Methodology:   
| Phase                       | Approach                                                                              |
| --------------------------- | ------------------------------------------------------------------------------------- |
| Data Cleaning & Preparation | Handling duplicates, converting data types, encoding categorical variables            |
| Exploratory Data Analysis   | Identifying trends, distributions, and anomalies using Pandas, Matplotlib, Seaborn    |
| Feature Engineering         | One-hot encoding, correlation analysis                                                |
| Predictive Modeling         | Random Forest Classifier, class weighting, hyperparameter tuning (RandomizedSearchCV) |
| Evaluation & Insights       | Feature importance, confusion matrix, ROC-AUC, F1-score                               |


Technical Stack:   
Languages: Python  
Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, joblib  
Tools: Jupyter Notebook  
