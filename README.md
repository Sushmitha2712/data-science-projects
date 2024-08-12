TITANIC SURVIVAL PREDICTION

Objective 🎯 :
The primary objective of the Titanic survival prediction project is to build a predictive model that can accurately determine whether a passenger would survive or not based on various features of the passenger and the ship. This task involves applying data science techniques to historical passenger data from the Titanic disaster to create a model that can generalize to new, unseen data.

Key Insights 📑 :
•Collected Dataset from kaggle
•Data Cleaning: Handle missing values (e.g., fill in missing ages or drop rows with missing target values), correct inconsistencies, and encode categorical features.
•Feature Scaling: Logistic Regression benefits from feature scaling. Normalize or standardize numerical features to ensure that they are on the same scale.
•Categorical Encoding: For Logistic Regression, use one-hot encoding or label encoding for categorical variables like Sex and Embarked.
•Model Building: Use libraries like scikit-learn to implement Logistic Regression. This model will serve as a baseline due to its simplicity and interpretability.
•Cross-Validation: Perform cross-validation on both models to assess their generalization capabilities and avoid overfitting.
•Performance Metrics: Compare models using performance metrics and determine which model provides the best results for predicting survival.
•Ngrok Tunnel: Use ngrok to create a secure tunnel to your local server, allowing you to share the application or model endpoint with others or test it externally. This is useful for demonstrating your model or integrating it with other applications.
•Local Server Setup: If deploying a web application or a model endpoint locally, set up a local server here we have used flask framework.
