📰 Fake News Confidence Predictor

This project is a Fake News Detection System focused on predicting the label confidence of an article using machine learning regression models like Random Forest and XGBoost.


🚀 Overview

The dataset contains ~10,000 entries with 27 features, including numeric and encoded categorical variables.
The goal is to predict the confidence level (between 0 and 1) of an article being fake or real.
Ideal for understanding how text features and metadata can help quantify credibility.


🔧 Features

Exploratory Data Analysis (EDA)
Data Cleaning & Preprocessing
Feature Encoding and Correlation Analysis
Model Training: Random Forest & XGBoost Regressors
Hyperparameter Tuning using RandomizedSearchCV
Performance Comparison & Visualization
Model Saving & Reusability via joblib


📁 Dataset

27 columns including content-based features, sentiment scores, metadata etc.
Target variable: label_confidence


📊 Visualizations

Confidence trend comparison (actual vs predicted)
Feature Importance Bar Chart
Evaluation Metrics Bar Graph
Correlation Heatmap


🙌 Acknowledgements

Sklearn, Seaborn, Pandas, Matplotlib


📬 Contact

Made with ❤️ by Raunak Raj
Connect on https://www.linkedin.com/in/raunakraj04/
