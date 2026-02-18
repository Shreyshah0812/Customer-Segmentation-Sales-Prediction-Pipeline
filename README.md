# Customer-Segmentation-Sales-Prediction-Pipeline
End-to-end machine learning pipeline for customer segmentation and sales forecasting using K-Means, Decision Trees, and time-series models, integrated into an interactive Streamlit application.
🚀 Project Overview

The objective of this project is to:

Identify distinct customer segments using behavioral and transactional data

Predict customer cluster membership using supervised learning

Forecast future sales trends using time-series models

Integrate models into an interactive application for real-time insights

The project demonstrates practical ML pipeline design, model validation, and deployment readiness.

📂 Dataset

Customer transactional and behavioral dataset including:

Spending patterns

Credit utilization

Payment behavior

Sales records

Preprocessing included:

Missing value handling

Feature scaling (StandardScaler)

Dimensionality reduction (PCA)

🧠 Models Implemented
🔹 Unsupervised Learning

K-Means Clustering

Optimal cluster selection using Elbow Method

PCA-based visualization of clusters

🔹 Supervised Learning

Decision Tree Classifier (Entropy-based)

Predicts customer segment

Train/Test split validation

Model persistence using Pickle

🔹 Sales Forecasting

Random Forest Regression

Prophet Time-Series Forecasting

MAE-based evaluation

Trend and seasonality modeling

⚙️ Pipeline Workflow

Data Cleaning & Feature Engineering

Feature Scaling & PCA

K-Means Segmentation

Supervised Cluster Prediction

Sales Forecasting

Model Serialization (Joblib / Pickle)

Integration into Streamlit App

📊 Model Evaluation

Elbow Method (Cluster optimization)

Accuracy (Classification)

Mean Absolute Error (Forecasting)

Train/Test Validation Split

🖥 Deployment

The models are integrated into a Streamlit-based interactive application allowing:

Real-time cluster prediction

Customer behavior visualization

Sales forecast exploration

🛠 Tech Stack

Python

Pandas, NumPy

Scikit-learn

Prophet

Matplotlib / Seaborn

Streamlit

Joblib / Pickle

📈 Key Outcomes

Built reusable ML pipeline for segmentation and prediction

Automated model persistence for scalable inference

Enabled interactive, real-time business insights
