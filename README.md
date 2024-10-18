# Age-based-insurance-prediction
A Python project analyzing medical insurance charges based on age using linear regression. Includes data visualizations (histograms, pair plots, heatmaps) and evaluates model accuracy by comparing predicted and actual charges with error analysis.



Table of Contents

Overview
Dataset
Installation and Setup
Project Structure
Approach
Results
Visualizations
Future Improvements
Contributing
License
Overview

In this project, we aim to predict the charges incurred by customers based on their age using a simple linear regression model. The project also explores the relationships between various features and charges, and presents several visualizations for a better understanding of the dataset.

Dataset

The dataset used for this project is the Medical Insurance Charges dataset, which contains information about:

Age: The age of the policyholder.
Sex: Gender of the policyholder.
BMI: Body Mass Index.
Children: Number of children covered under the insurance plan.
Smoker: Whether the policyholder is a smoker.
Region: The region where the policyholder resides.
Charges: The amount billed to the insurance company.


Approach

Data Exploration:
Loaded the dataset and explored basic statistics using pandas and seaborn.
Visualized the distribution of the charges column and relationships between features using pairplot and a correlation heatmap.
Model Building:
Built a simple linear regression model using Ordinary Least Squares (OLS) regression to predict charges based on age.
Prediction:
Predicted insurance charges for specific ages: 18, 25, 35, 40, 45, and 55.
Calculated the error and percentage difference between predicted and actual charges.
Model Evaluation:
Examined the residuals and overall model performance using metrics such as R-squared and error percentage.
Results

The model produced reasonable predictions for insurance charges based on age, but tended to overestimate the charges for younger individuals.
The model achieved its best performance for customers around age 45, with a minimal error.
