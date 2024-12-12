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

## Dataset Overview
![image](https://github.com/user-attachments/assets/75689d30-1ba5-414a-b1fc-882fcc642cf1)





# ![URL link:Video Presentation]( )

# Steps to Replicate

Download the Repository: Clone or download the ZIP file.

Load the Dataset: Open ICP_Data.csv in your notebook.

Run Notebooks:

       Open and execute ICP_Classification.ipynb
       Open and execute ICP_Regression.ipynb

Acknowledgement: In certain instances, this project employs the scikit-learn library for specific analyses. For further details, please refer to the official scikit-learn website: [https://scikit-learn.org/stable/].

