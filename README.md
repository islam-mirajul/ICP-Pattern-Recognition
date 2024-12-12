# ICProject: Machine Learning Based Regression Analysis and Classification of Unmanned Ground Vehicle (UGV) Designs

Welcome to the repository for my ICProject! This project leverages machine learning to analyze and classify Unmanned Ground Vehicles (UGVs) based on their design specifications and performance metrics. Below, you'll find an overview of the project, key objectives, instructions for replicating results, and references.

🔍 Project Purpose
The objective of this project is to employ machine learning models for:

Clustering and Classification of UGV Designs

Utilize unsupervised clustering algorithms (K-Means) to group UGVs based on their performance metrics.
Use these clusters to train supervised classifiers to categorize UGVs into predefined performance classes:
Low
Moderate
Standard
Advanced

Regression Analysis for Operational Range Prediction

Build regression models to predict the operational range of UGVs based on other performance metrics.

# Report
## Background, Baselines, and Approach

We are exploring new methods to reduce both the cost and time associated with computer-based simulations of physical systems. As part of this effort, we aim to evaluate and compare models for regression and classification tasks, focusing on minimizing errors (MAE, MSE, RMSE, R²) and maximizing performance metrics (accuracy, precision, recall, F1 score). 

This approach involves exploring a variety of machine learning models, including third-party and custom models to predict and optimize simulation parameters, aiming for faster and more cost-effective simulation results.

Baseline Methods

For regression: Mean, Median, Persistence, Zero, and Decile-based predictions.

For classification: Most Frequent Class, Random Classifier, and Stratified Classifier.

![image](https://github.com/user-attachments/assets/de1d47a5-6392-407d-82c1-09796f73078d)


## Dataset Overview
Table 1. Dataset Overview
![image](https://github.com/user-attachments/assets/75689d30-1ba5-414a-b1fc-882fcc642cf1)

Dataset Splits
![image](https://github.com/user-attachments/assets/67246590-aeb6-4b82-acb9-e9295cf74a2d)

## Data Analysis for Regression

Fig 1. Feature-Target Correlation Heatmap
![image](https://github.com/user-attachments/assets/20fbb9cc-d6a8-48e6-91e2-1011070058bb)

Fig 2. Top Features by Importance using Random Forest Regressor
![image](https://github.com/user-attachments/assets/7251c6ff-bd45-421c-898b-073324b51fa6)

## Methodology - Regression Analysis
![image](https://github.com/user-attachments/assets/012ceb50-aa3b-47b2-add6-79557a303cc0)

## Results-Regression Analysis
Table 2: Model Performance Metrics Comparison
![image](https://github.com/user-attachments/assets/ccd37279-1e7c-4039-b52d-453c9c398d71)
Custom Bayesian Linear Regression is the best overall performer

Fig 3. Actual vs Predicted Operational Range
![image](https://github.com/user-attachments/assets/176cb5e8-64db-407a-83f0-1c2996246023)
![image](https://github.com/user-attachments/assets/73d48375-45e4-4428-837f-5f4305e68b38)
![image](https://github.com/user-attachments/assets/7a5d665e-544e-4859-bada-99d94af942e8)
![image](https://github.com/user-attachments/assets/dd740056-90ba-4d62-a6bc-5441933be046)
![image](https://github.com/user-attachments/assets/dcc8537a-749e-4bed-a905-0a8153186d01)
![image](https://github.com/user-attachments/assets/764ed109-26e6-453e-8748-5956339786f8)
![image](https://github.com/user-attachments/assets/605af77c-3d20-43ce-bf11-c4d994155557)
![image](https://github.com/user-attachments/assets/1942b8f4-21cc-4e78-9180-f4bdc71c93c4)
![image](https://github.com/user-attachments/assets/9c909425-3e16-4548-9154-9c75e6e5fa63)
![image](https://github.com/user-attachments/assets/c6fd64dc-79f1-4859-8ecc-642c5d20a023)
![image](https://github.com/user-attachments/assets/f20c92f9-636e-461f-9a35-43c9ee829da3)



























# ![URL link:Video Presentation]( )

# Steps to Replicate

Download the Repository: Clone or download the ZIP file.

Load the Dataset: Open ICP_Data.csv in your notebook.

Run Notebooks:

       Open and execute ICP_Classification.ipynb
       Open and execute ICP_Regression.ipynb

Acknowledgement: In certain instances, this project employs the scikit-learn library for specific analyses. For further details, please refer to the official scikit-learn website: [https://scikit-learn.org/stable/].

