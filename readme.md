## Lung Cancer Analysis

## Description of Dataset
This project is a Python-based data visualization dashboard for LUNG CANCER data. 
It includes modules for data cleaning, file handling, exception, analysis of data,visual_streamlit, and dashboard creation.
This project predict lung cancer,visualize data.

## Columns used for Data Visualization:
-GENDER : Gender of patient
-AGE : Age of patient
-LUNG_CANCER : Display patient is positive or negative

## How to run the Code
To run the program based on this project, follow these steps:

## 1. Setup the Environment:
    -> Ensure proper/required version of Python is installed on your system.
    -> Install required libraries using by pip:
        pip install pandas
        pip install matplotlib
        pip install streamlit

## 2. Use the Dataset
    - Use the 'survey_lung_cancer_cleaned_data.csv' dataset for the project.  

## 3. Run the Application
    - Open a terminal or command prompt.
    - Navigate to the project directory.
    - Execute the following command:
        streamlit run dashboard.py
    - This command will start a local server and open the application in your default web browser.   

# Data Cleaning (data_cleaning.py)
The data cleaning process involves loading the dataset, handling missing values, removing duplicates.


# Exception (Exception.py)
Custom exceptions are defined in 'Exception.py 'and are handled throughout the project to manage errors effectively.


# File Handling (file_handling.py)
File handling functions are used open the file and write the data into survey_lung_cancer_cleaned_data.csv
File handling functions are used for saving cleaned data and loading data from files.

# Dashboard (dashboard.py)
Creates a Streamlit dashboard for user interactive data visualization.

# Visualization (visual_streamlit.py)
Generates plots 

# Analysis (analysis.py) 
Organize/Arrange data cleaning, visualization, and dashboard creation.

