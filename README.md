# Udacity-DS-ND-CP-Create-Segmentation-Report-for-AFS
Udacity Data Scientist Nanodegree Capstone Project: Create a Customer Segmentation Report for Arvato Financial Services

**Installation:**
Most of the libraries used in project code are already included in Anaconda Distribution. However throughout the project I ‘had to use the following installation comments:
  - pip install lightgbm
  - pip install xgboost
  - pip install imblearn.

First 2 was needed for their classifiers, imblearn was needed for SMOTE class for resampling.
  
## Business Understanding and Problem Definition

**Motivation:**

Main motivation for me was with my banking and business development professional experiences working with Arvato Financial Services data set will be very educational.
By starting to the project I've aimed:
  - First even if it was preprocessed for Udacity I wanted to analyze a real word sales data as DS profession candidate
  - Secondly learn new aspects by trying to cluster a real word data and making predictions from a real campaign data.
These goals were very important to me since I’m trying to learn set of skills outside of my profession and handling with real word data is a very good learning experience.

Project data set consists population and customers data from a mail order company in Germany. There are lots of learning points but main questions of the project host's are:
  - Creating a segmentation model for population data based on customer data to describe relationships as a Customer Segmentation Report.
  - Build a prediction model from mail-order campaign to find which customers will be customers of next campaign.

**Data Sets: **

Project has 4 data sets:
  - azdias.csv: Population data for AFS with shape of [891222, 365]
  - customers.csv: Customers data of AFS mail-order campaign with shape of [191652, 368]
  - mailout_train.csv: Labelled campaign data of AFS with shape of [42962, 366]
  - mailout_test.csv: Unlabeled test data of AFS with shape of [42833, 365]

First 2 data sets are used for EDA and Visualization and clustering part of the project.
Last 2 data sets are used to create a prediction model and testing it via project host's Kaggle competition.

Due to AFS Terms and Conditions I could not upload sets directly to this repository.

**Objective and Plan:**

Since our project structure consists of 2 main questions my project plan is divided into 3 main and relative subparts:
  - Data Understanding:
    - Data Analysis
    - Data Visualization
    - Data Cleaning Strategy
    - Feature Selection
  - Clustering:
    - Clustering with Customers Data Set
    - Applying Clustering Method to Population Data Set
    - Comparison
  - Prediction Modelling:
    - Applying Cleaning Strategy to Labelled Data
    - Model Selection
    - Final Model Application and Tuning
    - Applying Parts of the Cleaning Strategy to Unlabeled Data
    - Making Predictions to Unlabeled Data
    - Testing Predictions on Kaggle Competition
 
## Results

My Results for the 2-business question for project are:
  - Customers data is well distributed across population data and it could be used estimations for later campaigns especially clusters 5 and 1. 
  - Result on competition was scored as 0.63208 and my ranking was 85 by the time, I was writing this blog post.

Also, my detailed analysis and report are below medium blog post as project rubic suggested:
https://medium.com/@m.bilgehankilinc/creating-a-customer-segmentation-and-prediction-model-for-afs-df9e17e57ff3

## Acknowledgement

This project and it’s all data is belong to Arvato Financial Services and used for educational purposes to earn Udacity Data Science Nanodegree Certificate.

For my project solving period I wanted to thanks many contributors on medium and stack overflow. Through the process I’ve searched most of the topics I’ve encountered first time and learn from the common knowledge created by these amazing communities.
