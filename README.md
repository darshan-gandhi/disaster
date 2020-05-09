# Disaster Response Website 

# Problem Statement : 

There are messages from Disaster Relief Events, the task is to create a machine learning pipeline to categorize these events so that you can send the messages to an appropriate disaster relief agency.



There are three components for this project

# 1. ETL Pipeline

In a Python script, process_data.py, write a data cleaning pipeline that:

Loads the messages and categories datasets
Merges the two datasets
Cleans the data
Stores it in a SQLite database


# 2. ML Pipeline
In a Python script, train_classifier.py, write a machine learning pipeline that:

Loads data from the SQLite database
Splits the dataset into training and test sets
Builds a text processing and machine learning pipeline
Trains and tunes a model using GridSearchCV
Outputs results on the test set
Exports the final model as a pickle file


# 3. Flask Web App

A simple flask app is provided.
Add data visualizations using Plotly in the web app. 


