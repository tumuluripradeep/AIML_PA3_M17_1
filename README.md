# AIML_PA3_M17_1
This repo contains the code for the practical application assignment 3 for Module 17.

ML/AI Module 17 Application

# Predicting Customer Bank Deposit Subscription

# 📌 Project Overview
Predict Bank Deposit Subscription

This project aims to predict whether customers will subscribe to bank deposits based on previous campaigns using machine learning models. Models are trained on customer demographic and behavioral data (such as job, marital status, education, communication type, and previous campaign outcomes) to predict whether a client will subscribe to a term deposit offered by a bank. The goal is to identify potential customers who are more likely to respond positively to marketing campaigns, thereby improving targeting efficiency, reducing costs, and increasing conversion rates.

# 🔑 Key Features Considered
Duration
Job
Mrital Status
Education
Communication Type

# 📖 Notebooks
Explore the Jupyter notebook below with in-depth analysis and insights:

**Data Analysis,Modeling and Insights ** .

# Assignment Objective
Apply various classification methods to a business problem and compare the results of k-nearest neighbors, logistic regression, decision trees, and support vector machines.

# 📊 Model Evaluation Report
Overview
We executed various classification machine learning models on the Portugal – Bank Deposit Subscription Dataset to identify a model with strong performance. We compared metrics, including accuracy, precision, recall, and F1-score, along with the runtime of each model.

# Key Observations
The dataset is imbalanced; therefore, accuracy alone is not a reliable performance measure.

SVC and SVC with hyperparameter tuning showed significant differences in runtime.

The highest test accuracy was observed with the Decision Tree Classifier when combined with GridSearchCV.

The Decision Tree Classifier exhibited a large gap between training and test performance, indicating overfitting.

Logistic Regression produced balanced precision and recall scores.

For the SVC models, precision was consistently higher than recall.

The Decision Tree Classifier without parameter tuning showed severe overfitting.

KNN models demonstrated moderate overfitting.

SVC with GridSearchCV showed the least overfitting but yielded poor recall values.

# Inference
Based on the dataset and the applied transformations, SVC performed better overall compared to other models. However, its recall performance needs improvement. Despite this limitation, SVC can be considered a suitable model for predicting deposit subscription outcomes in this dataset.
