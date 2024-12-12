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

Fig 2. Feature-Target Correlation Heatmap
![image](https://github.com/user-attachments/assets/20fbb9cc-d6a8-48e6-91e2-1011070058bb)

Fig 3. Top Features by Importance using Random Forest Regressor
![image](https://github.com/user-attachments/assets/7251c6ff-bd45-421c-898b-073324b51fa6)

## Methodology - Regression Analysis
![image](https://github.com/user-attachments/assets/012ceb50-aa3b-47b2-add6-79557a303cc0)

## Results-Regression Analysis
Table 2: Model Performance Metrics Comparison
![image](https://github.com/user-attachments/assets/ccd37279-1e7c-4039-b52d-453c9c398d71)
Custom Bayesian Linear Regression is the best overall performer

Fig 4. Actual vs Predicted Operational Range
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

## Clustering & Classification
Fig 5. PCA Visualization of UGV Performance Classes: Pre- and Post-Clustering
![image](https://github.com/user-attachments/assets/aa820745-844b-430f-9c79-22244545d101)
Fig 6. UGV Design Clustering with Convex Hulls and Ellipses in 2D PCA Space
![image](https://github.com/user-attachments/assets/c1e382ee-7bc6-47dd-bc0a-919524a0964b)
![image](https://github.com/user-attachments/assets/9a4837e9-b4cd-4d4a-bbc7-06d537230693)

PCA (Principal Component Analysis) is used here to reduce the dimensionality of the data, making it easier to visualize and interpret. 

Convex Hulls define the outer boundary of each class, showing the region containing all points. Ellipses visualize the spread and orientation of the class data, reflecting the distribution and variance within the 2D PCA space.

## Methodology - Classification
![image](https://github.com/user-attachments/assets/3f229add-c70f-41cd-9b6b-82933cbc32ea)

## Results-Classification
Table 3. Model’s Performance Comparison
![image](https://github.com/user-attachments/assets/71702c4e-4393-43e5-9cb8-c9e177059f83)
Custom LDA and Custom QDA both have perfect scores (Accuracy: 1.0000, Precision: 1.0000, Recall: 1.0000, F1 Score: 1.0000), making them the best performers.

Fig 7. Confusion Matrix for all classification task models
![image](https://github.com/user-attachments/assets/a2af8a2a-00de-4e71-9038-be8485aa556a)
![image](https://github.com/user-attachments/assets/540d92cf-fcf0-4771-b310-b01ac0ef6bbd)
![image](https://github.com/user-attachments/assets/d50b2804-6d94-4484-b350-6e2451c3fb1f)
![image](https://github.com/user-attachments/assets/16770750-0c8b-4ade-b645-98aa53ae547e)
![image](https://github.com/user-attachments/assets/f9965321-c74d-4c9f-aa55-e7b3a324f3d0)
![image](https://github.com/user-attachments/assets/bafde178-2296-4d4c-82c2-b3046921b3ed)
![image](https://github.com/user-attachments/assets/3cf22f77-f887-4a6c-8259-8a403deef210)
![image](https://github.com/user-attachments/assets/9ac9108d-0cbe-4652-8b65-6aa72bfa88ec)
![image](https://github.com/user-attachments/assets/e13eebc1-55d3-41a9-af23-7a5da4703fff)
![image](https://github.com/user-attachments/assets/fe98cc2a-08ad-4bdf-9a95-39a8367eb76c)
![image](https://github.com/user-attachments/assets/5b86e026-baea-4b0d-a802-c5725481b2ee)
![image](https://github.com/user-attachments/assets/3efa487c-79d3-4225-8944-e21e8807ba71)
![image](https://github.com/user-attachments/assets/4735435a-ff1d-405d-9ec7-1fde200b88b9)
![image](https://github.com/user-attachments/assets/a33a5fa2-da47-4403-9889-ff86c3a241b7)

## Conclusions

For both regression and classification tasks, custom implementation models performed the best.

Regression Task: The Bayesian Linear Regression model achieved competitive results, with a high 𝑅2  score of 0.9564 and an RMSE of 8.0482, comparable to Ridge Regression. Among third-party models, Gradient Boosting performed slightly better, but the custom model remains highly effective.

Classification Task: Custom models, particularly Custom LDA and Custom QDA, achieved perfect performance with an accuracy, precision, recall, and F1 score of 1.0000, outperforming all other models. Among third-party models, Random Forest Classifier and Gradient Boosting Classifier achieved near-perfect performance (∼99.89%), making them strong contenders.


# ![URL link:Video Presentation]( )

# Steps to Replicate

Download the Repository: Clone or download the ZIP file.

Load the Dataset: Open ICP_Data.csv in your notebook.

Run Notebooks:

       Open and execute ICP_Classification.ipynb
       Open and execute ICP_Regression.ipynb

Acknowledgement: In certain instances, this project employs the scikit-learn library for specific analyses. For further details, please refer to the official scikit-learn website: [https://scikit-learn.org/stable/].

