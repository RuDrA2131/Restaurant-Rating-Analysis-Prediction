# Restaurant-Rating-Analysis-Prediction
Restaurant Rating Analysis &amp; Prediction using Machine Learning. This project performs Exploratory Data Analysis (EDA) and builds ML models to predict restaurant ratings based on various features.
📌 Problem Statement

The goal of this project is to analyze restaurant data and build a machine learning model that predicts restaurant ratings based on various features such as cost, cuisine type, location, and service-related attributes.

Restaurant ratings play a crucial role in customer decision-making. This project aims to identify the key factors influencing ratings and build an accurate predictive model.

🎯 Objectives

Perform comprehensive Exploratory Data Analysis (EDA)

Handle missing values and outliers

Perform feature engineering & encoding

Train multiple ML models

Compare models and select the best-performing one

Extract business insights from data

📂 Dataset contains:

Restaurant Name

Location

Cuisines

Average Cost for Two

Online Delivery Availability

Table Booking

Aggregate Rating

Votes

Other related features

🔎 Exploratory Data Analysis (EDA)

Key analyses performed:

Distribution of Restaurant Ratings

Cost vs Rating relationship

Most popular cuisines

Location-based performance

Online delivery impact on rating

Correlation heatmap

Outlier detection using IQR

📊 Insights Discovered:

Restaurants with online delivery tend to have slightly higher ratings.

Certain cuisines consistently perform better.

Cost has moderate influence on ratings.

Votes strongly correlate with rating reliability.

⚙️ Data Preprocessing

Missing value treatment

Duplicate removal

Ordinal Encoding

Label Encoding

Feature Scaling (StandardScaler / MinMaxScaler)

Train-Test Split

🤖 Machine Learning Models Implemented

Logistic Regression

K-Nearest Neighbors (KNN)

Decision Tree Classifier

Random Forest Classifier

Support Vector Classifier (SVC)

XGBoost Classifier


📈 Model Evaluation Metrics

Accuracy Score

Precision

Recall

F1 Score

Confusion Matrix

Cross Validation

Hyperparameter Tuning (GridSearchCV)

🏆 Best Model

After comparing all models:

Random Forest / XGBoost achieved the best accuracy.

Tree-based models performed better due to:

Handling non-linear relationships

Robustness to outliers

Automatic feature importance ranking

🛠️ Tech Stack

Programming Language: Python

Libraries:

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

XGBoost

Environment: Jupyter Notebook
