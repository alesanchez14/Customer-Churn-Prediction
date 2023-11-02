# Customer Churn Prediction Project using PySpark

In this 90-minute project, "PySpark for Data Science: Customer Churn Prediction", you will learn how to use PySpark to build a machine learning model to predict customer churn at a telecommunications company.

## Table of Contents
1. [Project Description](#project-description)
2. [Prerequisites](#prerequisites)
3. [Installation](#installation)
4. [Usage](#usage)
5. [License](#license)


## Project Description

This project covers a series of essential tasks including:

- Data Loading
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Feature Preparation
- Model Training
- Evaluation
- Deployment

All using PySpark. The developed machine learning model identifies the factors contributing to customer churn, providing actionable insights to the company to reduce churn and increase customer retention.

## Prerequisites

- Basic knowledge of Machine Learning and Decision Trees.
- Familiarity with Python programming concepts such as loops, if statements, and lists.

## Installation

To run this project, you'll need to install PySpark and some other libraries and modules. Here's how to do it:

1. **PySpark Installation**:
   ```bash
   !pip install pyspark
   
2. **Modules Installation:**:
   ```bash
   # Importing Spark session
   from pyspark.sql import SparkSession
    
   # Data visualization modules
   import matplotlib.pyplot as plt
   import plotly.express as px
    
   # Pandas module
   import pandas as pd
    
   # PySpark SQL functions
   from pyspark.sql.functions import col, when, count, udf
    
   # PySpark data preprocessing modules
   from pyspark.ml.feature import Imputer, StringIndexer, VectorAssembler, StandardScaler
    
   # PySpark data modeling and model evaluation modules
   from pyspark.ml.classification import DecisionTreeClassifier
   from pyspark.ml.evaluation import BinaryClassificationEvaluator 

## Project Description

- Main Script: The main script to run is The_Notebook.ipynb. It is recommended to execute this notebook on Google Colab.

- Execution Order:
  
   - Task 1 - Loading our data
   - Task 2 - Exploratory Data Analysis
   - Task 3 - Data Preprocessing
   - Task 4 - Feature Preparation
   - Task 5 - Model Training
   - Task 6 - Model Evaluation
   - Task 7 - Model Deployment

## Licence 

This project is for educational purposes and does not have a specific license.

