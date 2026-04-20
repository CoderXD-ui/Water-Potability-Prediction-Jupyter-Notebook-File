Water potability prediction uses machine learning to determine if water is safe to drink (potable=1) or 
not (not potable=0) based on physicochemical properties like pH, hardness, solids, and turbidity. Key
models include XGBoost, Random Forest, and Support Vector Machines, achieving accuracies ranging from 
66% to over 99% depending on the dataset.
Top Machine Learning Models
Research indicates that ensemble methods often outperform simpler algorithms in classification: 
GitHub
GitHub
 +2
XGBoost: Frequently provides the highest accuracy (reaching up to 99.5% in some studies).
Random Forest: Highly effective for handling mixed data types.
Support Vector Machine (SVM): Good for moderate-sized datasets.
K-Nearest Neighbor (KNN): Useful for classification based on proximity.
Water Potability Project
Introduction
The Water Potability Prediction project aims to predict the potability of water based on various physicochemical properties. The project involves analyzing various aspects of water quality, including pH, hardness, solids, and other chemical properties, to determine whether the water is potable or not. This was a semester-end project for the machine learning course offered by Jai Hind College Mumbai. I did the analysis and preprocessing in jupyter notebook and created a web application using python's Streamlit library. This project will provide a powerful tool for researchers, policymakers, and the general public to analyze the potability of water and make informed decisions based on the insights gained from the analysis. The project will help identify which physicochemical properties are most important in determining water potability, while the web app will provide a user-friendly tool for predicting water potability based on the input of various physicochemical properties.

Important Links:
Web App
EDA and MLA
Source Code
Workflow:
Importing required libraries and functions from models and loading the data.
Exploratory data analysis and data visualization to understand the relationship between the attributes.
Data preprocessing which involves filling in the missing values and scaling the numerical columns.
Splitting the model into train & test data and evaluating its performance using a confusion matrix.
Visualizing the decision tree and getting the feature importances.
Saving the model for further use and concluding the notebook.
Creating an interactive and user-friendly web application that predicts the water potability given the parameter values using the trained model.
Deploying the web application on share.streamlit.io for making it available for everyone.
