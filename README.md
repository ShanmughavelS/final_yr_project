Credit Default Prediction using Machine Learning

 Overview:

This project focuses on predicting the probability of credit card default using machine learning techniques. It leverages financial and demographic data to classify customers into default and non-default categories, helping financial institutions make better risk assessment decisions.

The project implements and compares multiple ensemble learning models, with a strong focus on performance and interpretability using Explainable AI (XAI).

Objectives:

* Analyze financial and demographic factors influencing credit default

* Build and evaluate machine learning models for prediction

* Handle class imbalance effectively

* Optimize models using hyperparameter tuning

* Provide interpretability using SHAP (Explainable AI)

Dataset:

* Source: UCI Machine Learning Repository

* Dataset: Default of Credit Card Clients

* Records: 30,000

* Features: 25 + 1 target variable

Key Features:

* Credit limit (LIMIT_BAL)
  
* Age, gender, education, marital status

* Repayment history (PAY_0 to PAY_6)

* Billing amounts (BILL_AMT1–6)

* Payment amounts (PAY_AMT1–6)

Technologies Used:

* Python

* Scikit-learn

* XGBoost

* LightGBM

* Pandas, NumPy

* Matplotlib, Seaborn

* SHAP (Explainable AI)

Machine Learning Models:

* Random Forest
  
* XGBoost

* LightGBM ✅ (Best Performing)

Methodology:

1.) Data Preprocessing

* Removed irrelevant features (e.g., ID)

* Train-test split (80/20)

* Feature scaling using StandardScaler
 
2.) Handling Class Imbalance

* Applied SMOTE (Synthetic Minority Oversampling Technique)

3.) Model Training

* Trained multiple ensemble models

* Compared baseline performance

4.) Hyperparameter Optimization

* Used GridSearchCV

* Optimized based on F1-score

5.) Evaluation Metrics

* Accuracy

* Precision

* Recall

* F1-score

* ROC-AUC

6.) Cross Validation

* Stratified K-Fold (k=5)

7.) Explainable AI

* Feature Importance

* SHAP values for global & local interpretability

📈 Results:

Models:

Random Forest
   
    Accuracy	0.8413
    
    F1 Score	0.8373
    
    ROC-AUC     0.9182
    
XGBoost	

    Accuracy    0.8545	
    
    F1 Score    0.8445	
    
    ROC-AUC     0.9217
    
LightGBM ⭐	

    Accuracy    0.8729	
    
    F1 Score    0.8651	

    ROC-AUC     0.9340


🔍 Key Insights:

* LightGBM achieved the best performance

* Repayment history is the strongest predictor of default

* SMOTE significantly improved recall and F1-score

* SHAP provided clear interpretability of model decisions

📊 Visualizations:


* Correlation Heatmap

* Class Distribution

* ROC Curves

* Confusion Matrix

* Feature Importance Plots

* SHAP Summary Plots


🔎 Key Findings:

* Payment history variables (PAY_0, PAY_2, etc.) dominate prediction

* Demographic features have less impact

* Ensemble models outperform traditional classifiers

* Explainable AI improves trust and transparency

Future Work:

* Implement deep learning models

* Include additional financial features (income, transactions)

* Test on international datasets

* Deploy as a real-time prediction API

👨‍💻 Author:

Shanmughavel Singaravelu

MSc Data Science Project

🔗 GitHub: https://github.com/ShanmughavelS/final_yr_project

📜 License:

This project is for academic and research purposes. Dataset is available under UCI repository license.
