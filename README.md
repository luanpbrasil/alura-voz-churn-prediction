# Alura Voz - Churn Prediction
This project was developed for the 1st Alura Data Science Challenge.

#### -- Project Status: Active

## Project Intro/Objective
The purpose of this project is to develop a classification model for churn prediction for a fictitious company called _Alura Voz_, in order to help them reduce thier churn rate.

To start, let's clarify what Churn is. The term refers to the rate of customer or user loss over a certain period of time. It is a crucial indicator for companies in various sectors as it directly impacts revenue and business health. Therefore, when we refer to Churn in our dataset, we will be discussing whether a customer continues to make purchases with the company or not.

During this workshop, we will follow the CRISP-DM method, a widely used approach in Data Science projects, which consists of: business understanding, data understanding, data preparation, modeling, evaluation, and implementation. Here, we will cover as much as possible of the concepts up to the evaluation phase.

Along the way, we will address data analysis techniques, preprocessing, feature selection, and the choice and evaluation of the performance of Machine Learning models.

Let's go! 😎

### Methods Used
* Exploratory Data Analysis
* Data Visualization
* Data preprocessing
* Data balancing with over-sampling
* Machine Learning
* Classification models (Logistic Regression, Random Forest Classifier and Gradient Boosting)
* Model Evaluation

### Technologies
* Python
* Pandas, Numpy
* Matplotlib, Seaborn, Plotly
* Scikit-Learn
* Imblearn
* Jupyter Notebook

## Project Description
This project aims to develop a classification model to predict customer churn. 
For that, we are using data about the company's customers to train our models and make predictions. These data contains informations such as:
  * `customerID`: unique identifier number of customer
  * `Churn`: if the client has left or not the company
  * `gender`: gender (male or female)
  * `SeniorCitizen`: if the client is older than 65 years old
  * `Partner`:  if the client has a partner or not
  * `Dependents`: if the client has dependants or not
  * `tenure`:  contract months subcription
  * `PhoneService`: telephone service subcription
  * `MultipleLines`: more than one phone line subcription
  * `InternetService`: internet provider subcription 
  * `OnlineSecurity`: aditional subcription for online security 
  * `OnlineBackup`: aditional subcription for online backup
  * `DeviceProtection`: aditional subcription for device protection 
  * `TechSupport`: aditional subcription for technial support
  * `StreamingTV`: cable subscription
  * `StreamingMovies`: streaming subscription
  * `Contract`: type of contract
  * `PaperlessBilling`: if the client prefers to receive the bill online
  * `PaymentMethod`: payment method
  * `Charges.Monthly`: client's total services of the month
  * `Charges.Total`: client's total spents

In order to do that, we are using an over-sampling technique for handling imbalanced classes and traning classification models such as:
  * Logistic Regression
  * Random Forests
  * Gradient Boosting.

## Needs of this project

- data exploration/descriptive statistics
- data processing/cleaning
- statistical modeling
- model evaluation and optimization

## Featured Notebooks/Analysis/Deliverables
* [churn_prediction.ipynb](https://github.com/luanpbrasil/alura-voz/blob/main/churn_prediction.ipynb)

#alurachallengedatascience1
