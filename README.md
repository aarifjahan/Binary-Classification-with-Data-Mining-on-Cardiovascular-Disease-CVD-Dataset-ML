# Binary-Classification-with-Data-Mining-on-Cardiovascular-Disease-CVD-Dataset-ML

Supervised/unsupervised ML models such as Logistic Regression, Random Forest, XGBoost &amp; K-Means Clustering to predict probability of CVD cases.


## Background
Cardiovascular disease (CVD) includes heart disease, stroke, heart failure, cardiomyopathy, and other heart related issues. High blood pressure is estimated to account for approximately 13% of CVD deaths, while tobacco, diabetes, lack of exercise, and obesity are also major contributing factors. (Pekka & Norrving, 2011)
Cardiovascular disease accounted for 32.1% of global deaths in 2015, but McGill et al. (2008) estimate that up to 90% of cardiovascular disease may be preventable by improving on personal behavior that contributes to risk. Death by cardiovascular disease may also be avoidable if a patient receives treatment soon enough.

The focus in this project is to employ multiple supervised machine learning modeling techniques to solve a binary classification problem regarding CVDs. In addition, unsupervised machine learning models are also used to perform detailed data exploration and segmentation purposes.

## Problem Statement

How can we use known risk factors to build a machine learning model that identifies patients who might be more likely to have a cardiovascular disease? 

This project attempts to predict the presence or absence of cardiovascular disease in this dataset of 70000 patients using 11 predictor variables. These predictor variables include the leading risk factors for CVD, such as whether a patient smokes or exercises, and the blood pressure of the patient. Each observation in this dataset represents an individual patient.  

The following supervized machine learning models are used to predict CVD classification: logistic regression, random forest, and XGBoost. 

Moreover, an unsupervised model in the form of K-means clustering technique is used to to dissect the original dataset into groups to make inferences about potential performance improvements. 

All models are tuned using cross validation and grid search to optimize for hyperparameters.

## Project Files:

Data_Cleaning_Exploration.ipynb - Contains code used for initial data cleaning and exploration
Logistic_Regression_Model.ipynb - Contains code used for predicting CVDs using Logistic Regression
Random_Forest_Model.ipynb - Contains code used for predicting CVDs using Random Forest
XGBoost_Model.ipynb - Contains code used for predicting CVDs using XGBoost
Project Report/Presentation.pdf - Contains full report and slide decks about the the project

-- Aarif M Jahan -- Jul 17, 2021
