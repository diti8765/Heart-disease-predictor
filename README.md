Heart Disease Prediction using Machine Learning

The goal of this project is to predict the likelihood of a person having heart disease based on clinical and lifestyle-related features.
Early prediction can help in timely treatment and better healthcare outcomes.


###Dataset & Features:
The dataset includes patient health records with attributes such as:

Age, Sex – demographic details
Chest Pain Type (cp) – typical angina, atypical angina, non-anginal pain, asymptomatic
Resting Blood Pressure (RestingBP)
Cholesterol levels (Cholesterol)
Fasting Blood Sugar (FastingBS)
Resting ECG Results (RestingECG)
Max Heart Rate Achieved (MaxHR)
Exercise-Induced Angina (ExerciseAngina)
ST Depression (Oldpeak)
ST Slope (ST_Slope)
Target (HeartDisease) – binary label (1: disease, 0: no disease)

###Methodology:

##Data Preprocessing:

Encoded categorical variables using one-hot encoding.
Standardized numerical features using StandardScaler.
Split dataset into training & test sets.

##Model Training:

Trained multiple ML algorithms for comparison:
Logistic Regression
K-Nearest Neighbors (KNN)
Naïve Bayes
Decision Tree
Support Vector Machine (RBF Kernel)


##Evaluation Metrics:
Accuracy Score
F1 Score
Classification Report (precision, recall, f1-score)


##Model Deployment Preparation:

Saved best-performing model (KNN) using joblib.
Exported scaler.pkl and feature columns.pkl for consistency during inference.
