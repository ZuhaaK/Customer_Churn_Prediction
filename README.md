

**Customer Churn Prediction**



\*Project Overview



This project predicts customer churn (whether a customer will leave the service) using various machine learning algorithms.

The goal is to identify at-risk customers early, enabling businesses to take proactive retention measures.



\*Dataset



Source: Telco Customer Churn Dataset (Kaggle)



Rows: 7,043 customers



Features: 21 (demographics, account info, service usage, etc.)



Target: Churn (Yes/No → 1/0)



\*Technologies Used



Language: Python



Libraries:



pandas, numpy, matplotlib, seaborn



scikit-learn



xgboost



lightgbm



joblib



jupyter notebook



\*Models Implemented

1️⃣ Random Forest Classifier



Tuned using GridSearchCV for optimal hyperparameters.



Chosen because it handles non-linearity and feature interactions well.



Best recall achieved ≈ 0.71, ROC-AUC ≈ 0.83.



2️⃣ XGBoost Classifier



Tuned using GridSearchCV and early stopping.



Outperformed Random Forest with better precision-recall balance.



Feature importance plots used for interpretability.



3️⃣ LightGBM Classifier



Extremely fast gradient boosting framework by Microsoft.



Achieved best F1-score ≈ 0.66 and ROC-AUC ≈ 0.85.



Used for final model deployment.



\*Evaluation Metrics



Accuracy



Precision



Recall



F1-Score



ROC-AUC



Confusion Matrix



\*Visualizations



Confusion Matrix Heatmap



ROC Curve



Feature Importance Bar Charts



\*Model Saving



Each trained model was saved for reuse:



rf\_churn\_model\_final.pkl

xgb\_churn\_model\_final.pkl

lgb\_churn\_model\_final.pkl





Feature importances were also stored as CSVs for interpretability.



\*Key Takeaways



Boosting methods (XGBoost, LightGBM) slightly outperform bagging (Random Forest).



Threshold tuning improves precision without sacrificing recall.



Feature importance insights help understand customer churn behavior.



\*Author



Zuhaa K.



Gmail- zuhakhan2024@gmail.com



LinkedIn Profile- https://www.linkedin.com/in/zuha-khan-1a7b79231/





