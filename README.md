# Udacity-DS-ND-CP-Create-Segmentation-Report-for-AFS
Udacity Data Scientist Nanodegree Capstone Project: Create a Customer Segmentation Report for Arvato Financial Services

**Intallation:**
Most of the libraries used in project code are already included in Anaconda Distribution. However troughout the project i'had to use the following installation coments:
  - pip install lightgbm
  - pip install xgboost
  - pip install imblearn.

First 2 was needed for their classifiers, imblearn was needed for SMOTE class for resampling.
  
## Bussiness Understanding and Problem Definition

**Motivation:**

Main motivation for me was with my banking and bussiness development professional experiences working with Arvato Financial Services data set will be very educational.
By starting to the project I've aimed:
  - First even if it was prepocessed for Udacity i'wanted to analyze a real word sales data as DS profession candidate
  - Secondly learn new aspects by trying to cluster a real word data and making predictions from a real campaign data.
These goals were very important to me since i'm trying to learn set of skills outside of my profession and handling with real word data is a very good learning experience.

Project data set consists population and customers data from a mail order company in Germany. There are lost of learning points but main questions of the porject host's are:
  - Creating a segmentation model for population data based on customer data to describe relationships as a Customer Segmentation Report.
  - Build a prediction model from mail-order campaign to find which customers will be customers of next campaign.

**Data Sets:**

Project has 4 data sets:
  - azdias.csv: Population data for AFS with shape of [891222, 365]
  - customers.csv: Customers data of AFS mail-order campaing with shape of [191652, 368]
  - mailout_train.csv: Labelled campaing data of AFS with shape of [42XXX, 366]
  - mailout_test.csv: Unlabelled test data of AFS with shape of [42XXX, 365]

First 2 data sets are used for EDA and Visualization and clustering part of the project.
Last 2 data sets are used to create a prediction model and testing it via project host's Kaggle competition.

Due to AFS Terms and Conditions I could not uploaded sets driectly to this repository.

**Objective and Plan :**

Since our project structure consists of 2 main questions my project plan is diveded into 3 main and relative subparts:
  - Data Undestanding:
    - Data Analysis
    - Data Visualization
    - Data Cleaning Strategy
    - Feature Selectio
  - Clustering:
    - Clustering with Customers Data Set
    - Applying Clustering Method to Population Data Set
    - Comparison
  - Prediction Modelling:
    - Applying Cleaning Strategy to Labelled Data
    - Model Selection
    - Final Model Application and Tuning
    - Applying Parts of the Cleaning Strategy to Unlabelled Data
    - Making Predictions to Unlabelled Data
    - Testing Predictions on Kaggle Competition
 
## Results

My Resuls for the 2 bussiness question for project are:
  - Result-1
  - Result-2

Also my detailed analysis and report are below medium blog post as project rubic suggested:
BLOG_URL

## Acknowledgement

This project and its all data is belong to Arvato Finalcial Services and used for educational purposes to earn Udacity Data Science Nanodegre Certificate.

For my project solving prediod I wanted to thanks many conributers on medium and stackoverflow. Trough the process i've searched most of the topics i've encountered first time and learn from the common knowledge created by these amazing comunities.
