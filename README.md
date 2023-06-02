# crop-recommendation-system
This repository contains the source code and related files for a Crop Monitoring System, which aims to provide personalized crop recommendations to farmers based on environmental factors. The system utilizes machine learning models to analyze various parameters such as temperature, humidity, pH, and rainfall, and suggests suitable crop options accordingly.

# Features:

Data preprocessing: Includes data cleaning, normalization, and feature engineering to prepare the dataset for training.
Machine learning models: Implements different machine learning algorithms such as Decision Tree, Logistic Regression, Random Forest, k-Nearest Neighbors, Naive Bayes, CatBoost, LinearSVC, NuSVC, and LightGBM for crop recommendation.
User interface: Provides a user-friendly interface using the PySimpleGUI library for inputting environmental parameters and displaying crop recommendations.
Evaluation metrics: Calculates accuracy, precision, and other relevant metrics to evaluate the performance of the crop recommendation models.
Data visualization: Generates visualizations such as bar plots, histograms, and scatter plots to gain insights into the data and model predictions.
# Folder Structure:

data: Contains the datasets used for training and testing the crop recommendation models.
models: Includes the trained machine learning models for crop recommendation.
src: Contains the source code files for data preprocessing, model training, and user interface implementation.
utils: Includes utility functions used in various stages of the crop monitoring system.
# Dependencies:

Python 3.x
NumPy
Pandas
Scikit-learn
PySimpleGUI
# Usage:

Clone the repository: git clone [repository_url]
Install the required dependencies: pip install -r requirements.txt
Run the main.py file: python main.py
Input the environmental parameters through the user interface and click on the "Predict" button to get crop recommendations.
# Contributing:
Contributions to this project are welcome. If you have any suggestions, bug fixes, or additional features to add, please open an issue or submit a pull request.

# License:
This project is licensed under the [License Name]. Please refer to the LICENSE file for more details.

Feel free to explore the repository and utilize the Crop Monitoring System to make informed crop selection decisions based on environmental factors.
