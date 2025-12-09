**Comprehensive Weather Analysis Using Supervised & Unsupervised Machine Learning**

📖 Project Overview

This project focuses on analyzing historical weather data using Exploratory Data Analysis (EDA), data visualization, and Machine Learning models.
The goal is to:

Understand weather patterns

Predict weather conditions using classification

Predict temperature using regression

Discover hidden patterns using unsupervised learning

Compare and fine-tune multiple models

🗂️ Dataset

File Name: Weather.csv

Type: Structured tabular data

Features include:

Temperature (max, min, average)

Feels-like temperature

Humidity

Precipitation

Heat index

Time-based features

Weather conditions (categorical)

⚙️ Technologies Used
Category	Tools
Programming Language	Python
Libraries	Pandas, NumPy
Visualization	Matplotlib, Seaborn
Machine Learning	Scikit-learn
Models	Random Forest, Linear Regression, Ridge, KMeans, PCA
🛠️ Project Workflow
1️⃣ Data Loading

Loaded dataset using Pandas

Checked structure, columns, and data types

2️⃣ Exploratory Data Analysis (EDA)

Missing value detection

Statistical summary

Correlation analysis

Feature understanding

3️⃣ Data Visualization

Temperature distribution plots

Humidity vs Temperature scatter plots

Correlation heatmap

Cluster visualization

🤖 Machine Learning Models Applied
✅ Supervised Learning
1. Classification

Target: conditions

Model: RandomForestClassifier

Objective: Predict weather conditions (Clear, Rain, Cloudy, etc.)

Evaluation Metric: Accuracy, Precision, Recall, F1-score

2. Regression

Target: temp

Models:

Linear Regression

Ridge Regression

Evaluation Metrics:

R² Score

Mean Absolute Error (MAE)

✅ Unsupervised Learning
1. KMeans Clustering

Features used: temp, humidity, heat_index

Identifies natural weather clusters

Evaluation Metric: Silhouette Score

2. Principal Component Analysis (PCA)

Reduces high dimensional data

Helps visualize data in 2D

Measures explained variance

🔧 Model Fine-Tuning

Random Forest:

Tuned number of estimators and tree depth using GridSearchCV

Regression:

Used Ridge Regression to handle multicollinearity

Unsupervised:

Optimal cluster selection for KMeans

📊 Model Comparison Summary
Model	Type	Metric	Performance
Random Forest	Classification	Accuracy	High
Linear Regression	Regression	R² Score	Moderate
Ridge Regression	Regression	R² Score	Improved
KMeans	Clustering	Silhouette Score	Good
PCA	Dimensionality Reduction	Explained Variance	High

✅ Best Classifier: Random Forest
✅ Best Regressor: Ridge Regression
