# Loan-Default-Prediction-using-Machine-Learning-Plotly-Dashboard
This project builds an end-to-end machine learning pipeline to predict loan default probability and visualize borrower risk insights through an interactive Plotly dashboard. It demonstrates a full data science workflow from raw data preprocessing to model explainability.


📘 Project Overview

Loan default prediction plays a vital role in helping financial institutions manage credit risk and optimize lending strategies.
This project analyzes borrower data, trains multiple ML models, and visualizes insights through a dynamic dashboard to assist in data-driven decision making.


🎯 Objectives

Predict whether a loan applicant is likely to default.

Identify key risk factors influencing default behavior.

Provide interactive visual analytics using Plotly dashboard components.


🧩 Key Features
🧹 Data Preprocessing

Cleaned and handled missing values and categorical variables.

Scaled numerical features using StandardScaler.

Feature engineering:

Debt-to-Income (DTI) ratio

Loan-to-Income ratio

Derived default indicator from credit history

📊 Exploratory Data Analysis (EDA)

Univariate and bivariate analysis with Seaborn, Matplotlib, and Plotly.

Distribution plots, correlation heatmaps, and risk segmentation.

Interactive insights:

Loan amount vs income

Default rate by employment type

Credit score trends

🤖 Model Building

Models trained:

Logistic Regression

Random Forest Classifier

XGBoost Classifier

Applied GridSearchCV for hyperparameter optimization.

Saved trained model using joblib for deployment readiness.

📈 Model Evaluation

Evaluated performance using:

Accuracy

Precision, Recall, F1 Score

ROC-AUC Curve

Confusion Matrix

🔍 Model Explainability

Used SHAP (SHapley Additive exPlanations) for feature importance and interpretability.

Visualized top features influencing default probability.

📉 Interactive Dashboard (Plotly)

The dashboard allows users to:

Explore default risk trends interactively.

Filter by borrower characteristics (age, income, loan amount, etc.).

View live charts of model performance metrics and feature impacts.


⚙️ Tech Stack
Category	                         Tools / Libraries
Language	                         Python
Data Analysis	                     pandas, numpy
Visualization	                     matplotlib, seaborn, plotly
Machine Learning	                 scikit-learn, xgboost
Explainability	                   shap
Dashboarding	                     plotly.graph_objects, plotly.express
Model Persistence	                 joblib


🧠 Results Summary
Model	                   Accuracy	             ROC-AUC	          F1-Score
Logistic Regression     	~0.80	               ~0.85              	~0.78
Random Forest	            ~0.88	               ~0.91	              ~0.87
XGBoost                 	~0.90	               ~0.94	              ~0.89

🥇 XGBoost achieved the highest predictive performance, demonstrating robust generalization and stability.


📊 Dashboard Preview (Example)

| Loan Default Risk Dashboard                         

| • Default rate by emploment type                   
| • Loan amount vs. income (interactive scatter)   
| • Credit score vs. default probability (heatmap)   
| • Model performance metrics visualization         
+--------------------------------------------------

📄 Future Improvements

Deploy the model using Streamlit or Flask.

Add real-time borrower data from APIs.

Implement automated retraining and model monitoring.

Extend dashboard for loan portfolio analytics.

🧾 Folder Structure: 
Loan_Default_Prediction/
│
├── Loan_Default_Prediction_using_Machine_Learning.ipynb   # Main ML notebook
├── loan_dashboard.py                                      # Plotly dashboard
├── data/                                                  # Dataset files
├── models/                                                # Saved models
├── requirements.txt                                       # Dependencies
└── README.md                                              # Project documentation
