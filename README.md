Crop Recommendation System

Project Overview

The Crop Recommendation System is a machine learning project designed to assist farmers in selecting the most suitable crop based on soil nutrients (N, P, K), soil pH, temperature, humidity, and rainfall. The system aims to maximize crop yield, optimize resource usage, and promote sustainable agricultural practices.

Features

Predicts the best crop to cultivate based on environmental and soil parameters.

Uses machine learning classification algorithms for high accuracy.

Supports decision-making for sustainable agriculture.

Can be extended to web or mobile applications for farmers.

Dataset

Source: Crop Recommendation Dataset - Kaggle

Format: CSV

Dataset Details:

Feature	Description
N	Nitrogen content in soil (kg/ha)
P	Phosphorous content in soil (kg/ha)
K	Potassium content in soil (kg/ha)
temperature	Average temperature (°C)
humidity	Average humidity (%)
ph	Soil pH
rainfall	Average rainfall (mm)
crop	Target crop (categorical variable)

Number of Records: 2200+

Purpose: Train ML models to recommend suitable crops based on soil and weather conditions.

Data Cleaning: Checked for missing or duplicate values. Filled missing numeric values with mean and dropped duplicates.

Feature Selection: Selected features: N, P, K, temperature, humidity, ph, rainfall.

Encoding Target Variable: Converted crop names to numeric labels using LabelEncoder.

Feature Scaling (Optional): Used StandardScaler for models requiring scaling (e.g., KNN, SVM).

Train-Test Split: Split data into training (80%) and testing (20%) sets.

Machine Learning Model

Algorithm Used: Random Forest Classifier (baseline). Alternatives: Decision Tree, KNN, XGBoost.

Evaluation Metrics:

Accuracy

Confusion Matrix

Classification Report

Workflow:

Load and preprocess dataset.

Split dataset into training and testing sets.

Train ML model on training data.

Predict crop on testing data.

Evaluate model performance.

Author

Prachi Urgunde | Crop Recommandation System | Sustainable Agriculture
