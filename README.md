📦 Supply Chain Management – Product Sales Prediction
   Deep Learning approach to predict product sales using Supply Chain data

📌 Project Overview
This project focuses on predicting the number of products sold in a supply chain using data preprocessing,
exploratory data analysis (EDA), and a deep learning regression model built with TensorFlow/Keras.
The goal is to help businesses make data-driven decisions about demand forecasting and resource allocation.


🎯 Objectives

    🧹 Clean & preprocess supply chain dataset
    
    📊 Analyze data patterns using EDA
    
    🏗 Build & train a deep learning model to predict product sales

    📈 Evaluate model performance using Mean Squared Error (MSE)

    📤 Provide a reproducible pipeline for future data predictions



🛠 Tools & Libraries
  Python – Core programming language

  Pandas / NumPy – Data manipulation

  Matplotlib / Seaborn – Data visualization

  Scikit-learn – Data preprocessing & metrics

  TensorFlow / Keras – Deep learning model



📂 Dataset
File: supply_chain_ Management_data.csv

Target Variable: Number of products sold

Features: Product type, location, supplier info, pricing, inventory, etc.


🔄 Data Preprocessing Steps
Drop rows with missing target values

Fill missing values:

Numeric → median

Categorical → "Unknown"

One-hot encode categorical columns

Split data into training and testing sets

Scale numerical features using StandardScaler



🧠 Model Architecture
  Input Layer: Based on number of features after encoding

  Hidden Layers: Multiple Dense layers with ReLU activation

  Output Layer: Single neuron (regression output)

  Optimizer: Adam

  Loss Function: Mean Squared Error (MSE)



📈 Results
Evaluation Metric: Mean Squared Error

Model successfully learned sales patterns and can predict sales quantity for new inputs.



🚀 Project Workflow
  Data Loading

  Data Cleaning & Preprocessing

  EDA (Visualizations & Insights)

  Feature Encoding & Scaling

  Deep Learning Model Building

  Model Training & Evaluation

  Results & Insights


