# Capstone_Project
Project Overview

This capstone project involves the analysis and classification of data from the Dentistry Dataset.csv. The goal is to preprocess the data, build predictive models, and evaluate their performance using various machine learning techniques.

Dataset

File Name: Dentistry Dataset.csv

Description: Contains data relevant to dental case studies with multiple attributes.

Libraries and Tools

The project uses the following libraries and tools:

pandas - Data manipulation and analysis

numpy - Numerical computations

seaborn and matplotlib.pyplot - Data visualization

scikit-learn - Preprocessing, model training, and evaluation

xgboost - Advanced machine learning models

plotly - Interactive visualizations

Project Workflow

1. Data Collection

Download the dataset and load it into the environment using pandas.

2. Data Preprocessing

Identify and handle missing values.

Drop unnecessary columns (Sample ID, Sl No).

Normalize and encode relevant features.

3. Model Building

Split the dataset into training and testing sets.

Build and evaluate multiple models:

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

XGBoost Classifier

4. Model Evaluation

Generate and plot ROC and AUC curves to evaluate model performance.

Instructions to Run

Clone the repository:

git clone https://github.com/username/repository-name.git

Install the required libraries:

pip install -r requirements.txt

Run the Jupyter Notebook:

jupyter notebook CapstoneprojectED.ipynb

Results

Model accuracy and comparison metrics.

ROC and AUC curves for model evaluation.
