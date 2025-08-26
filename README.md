📌 Project Overview

This project demonstrates how to build a Decision Tree-based Random Forest Classifier to predict the likelihood of heart disease using the heart.csv dataset.
The goal is to analyze patient health records and identify key risk factors contributing to heart disease.

Random Forest is chosen because it is:

Robust against overfitting

Handles both categorical and numerical data well

Provides feature importance for medical interpretability

📂 Dataset: heart.csv

The dataset contains patient medical information such as:

Age – Age of the patient

Sex – Male/Female

ChestPainType – Type of chest pain

RestingBP – Resting blood pressure

Cholesterol – Serum cholesterol (mg/dl)

FastingBS – Fasting blood sugar

RestingECG – Resting electrocardiographic results

MaxHR – Maximum heart rate achieved

ExerciseAngina – Exercise-induced angina

Oldpeak – ST depression induced by exercise

ST_Slope – The slope of the ST segment

HeartDisease – Target variable (1 = Heart Disease, 0 = No Heart Disease)

⚙️ Tech Stack

Python 🐍

Pandas → Data manipulation & preprocessing

NumPy → Numerical operations

Matplotlib / Seaborn → Data visualization

Scikit-learn → Model building (Random Forest Classifier, train-test split, evaluation)

🚀 Steps Performed

Data Preprocessing

Handled missing values

Converted categorical features into numerical (encoding)

Normalized/standardized numerical features

Exploratory Data Analysis (EDA)

Visualized age distribution, cholesterol levels, and correlations

Compared features between patients with and without heart disease

Model Building

Applied Random Forest Classifier

Tuned hyperparameters (n_estimators, max_depth, etc.)

Evaluated using accuracy, precision, recall, and F1-score

Results & Insights

Achieved high accuracy in predicting heart disease

Identified age, cholesterol, max heart rate, and ST slope as top risk factors

📊 Results

Accuracy: ~85–90% (depending on tuning)

Feature Importance helps interpret which factors are most significant for predicting heart disease.

📌 Future Work

Deploy as a web app using Streamlit or Flask

Integrate with real-time health monitoring systems

Apply SHAP values for better interpretability
