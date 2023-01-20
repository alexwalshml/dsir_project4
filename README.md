# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 4: Fraud Detection

## Problem Statement

Nearly half of all Americans experienced some form of fraudulent charges in 2021, according to the security.org annual Fraud report. As society moves increasingly towards a cashless society every year, we must continue to advance our ability to detect fraud and protect consumers. Unfortunately, credit card fraud poses a significant challenge for classification algorithms as the classes are typically heavily imbalanced. For this project, we analyze simulated credit card fraud data and aim to build a model that can accurately detect fraud. 


#### Repository overview

- Problem Statement
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Modeling and Evaluation 
- Executive Summary

---

## Exploratory data analysis (EDA)

#### EDA will consist of examining the following:
- Inspecting most common words
- distributions of post lengths
- Unique users
- Most common bigrams
- Inspect class proportions 

## Feature Engineering

#### Feature engineering will consist of examining the following:
- blah 


## Modeling and Evaluation

##### Modeling will consist of the following:
- Building and evaluating a Logistic Regression model
- Building and evaluating a Random Forest model
- Building and evaluating n AdaBoost Classifier model
- Best Model Evaluation 

---

## Executive Summary

In this project, we leveraged a simulation to generate useful data to train and build a fraud detection model to protect consumers from credit card fraud. 
We analyzed the data and highlighted meaningful trends from the data that related to predicting fraudulent activity. We built several classification models to evaluate model performance and address the challenges of highly imbalanced classes. We engineered several features and transformed the data when applicable to aid in model performance. The final model was a Random Forest algorithm which was nearly 99% accurate, and our model did not detect only 1% of all instances of fraud. We recommend implementing our algorithm to reduce future fraud and protect consumers. 

## Recommendations

In this project, we leveraged a simulation to generate useful data to train and build a fraud detection model to protect consumers from credit card fraud. 
We analyzed the data and highlighted meaningful trends from the data that related to predicting fraudulent activity. We built several classification models to evaluate model performance and address the challenges of highly imbalanced classes. We engineered several features and transformed the data when applicable to aid in model performance. The final model was a Random Forest algorithm which was nearly 99% accurate, and our model did not detect only 1% of all instances of fraud. We recommend implementing our algorithm to reduce future fraud and protect consumers. 

---

#### Repository File Structure

Below outlines what files are in which folders of this repository.

**notebooks**
```
- EDA.ipynb contains all of the code used in data cleaning and EDA
- Modeling_subset.ipynb contains all of the code used in preprocessing and initial model evaluation on a subset of our data
- Final_model.ipynb contains all of the code in developing our best model and our summary and recommendations
```
**data**
```
- preprocessed_subsample_100k.csv is the data subset used in our Modeling_subset notebook
- fraud_records.csv.csv is the data created from our simulation and used in our EDA notebook
- preprocessed_all_data.csv is the data used in our final model
```
**Presentataion Slides**

- PDF of the project presentation slides.
