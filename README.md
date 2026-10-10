The Covid Severity Prediction project is a machine learning-based analysis designed to predict the severity of COVID-19 in patients using medical and demographic tabular data. Predicting disease severity accurately helps healthcare professionals prioritize treatments and manage resources effectively.
This project goes beyond basic classification by implementing advanced Machine Learning techniques and Explainable AI (XAI). It not only predicts the severity but also explains why a certain prediction was made, highlighting the critical impact of specific medical features such as SPO2, CRP levels, and Age.

Key Features
Advanced Machine Learning: Utilizes the CatBoost Classifier, a highly efficient gradient boosting algorithm optimized for tabular data.
Hyperparameter Tuning: Implements RandomizedSearchCV to find the most optimal parameters for the CatBoost model, maximizing accuracy and performance.
Class Imbalance Handling: Integrates SMOTE (Synthetic Minority Over-sampling Technique) to address the natural imbalance in medical datasets (e.g., fewer severe cases compared to mild ones), preventing model bias.
Explainable AI (SHAP): Employs SHAP (SHapley Additive exPlanations) to interpret model predictions. It generates visual summaries showing exactly how features like SPO2 and CRP levels drive the model's decision-making process.

Technologies Used
Language: Python 3
Environment: Jupyter Notebook / Google Colab (Covid_Severity_Prediction.ipynb)

Libraries:
pandas, numpy (Data Manipulation)
matplotlib, seaborn (Data Visualization)
scikit-learn (Data Splitting, Evaluation, Hyperparameter Tuning)
imbalanced-learn (SMOTE for handling class imbalance)
catboost (Machine Learning Model)
shap (Model Interpretability & Explainable AI)
