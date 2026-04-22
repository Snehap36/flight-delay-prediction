Dataset : https://drive.google.com/file/d/1HxbcZ41jYzCuxVUASc0xKaXFU-lowBWA/view?usp=drive_link
# Flight Delay Prediction using Machine Learning

#Project Overview

This project develops and evaluates machine learning models to predict flight delay risk using historical flight data. The objective is to support data-driven decision-making in aviation by identifying high-risk flights and improving operational efficiency.

The study compares three models:

* Logistic Regression
* Random Forest
* XGBoost

Performance is evaluated using both classification and probabilistic metrics, including ROC-AUC, F1-score, log loss, and Brier score.

# What the Project Does

* Loads and processes a large flight dataset (~400,000 records)
* Cleans and preprocesses data (handling missing values, encoding categorical features)
* Performs feature engineering (e.g., extracting departure hour - DepHour)
* Trains and compares multiple machine learning models
* Evaluates models using advanced metrics beyond accuracy
* Identifies key factors influencing flight delays using feature importance

# Project Structure

text
project/
│── data/                 # Dataset (or link to dataset)
│── notebooks/            # Optional Jupyter notebooks (if used)
│── src/                  # Python scripts
│   └── main.py           # Main script to run the project
│── results/              # Outputs (plots, metrics, figures)
│── requirements.txt      # Required libraries
│── README.md             # Project documentation



# How to Run the Code

# 1. Clone the repository

bash
git clone https://github.com/Snehap36/flight-delay-prediction.git
https://github.com/Snehap36/flight-delay-prediction.git
cd flight-delay-prediction

# 2. Install required libraries

bash
pip install -r requirements.txt

#3. Run the project

bash
python main.py

#Required Libraries

* numpy
* pandas
* matplotlib
* seaborn
* scikit-learn
* xgboost

#Dataset

The dataset used is a publicly available flight dataset from Kaggle.
It includes variables such as:

* airline (carrier)
* departure time
* distance
* origin and destination
* arrival delay

Flights delayed by more than 15 minutes are classified as “Delayed”, while others are “Not Delayed”.

#Output

The project generates:

* Model performance comparison
* ROC curves
* Confusion matrices
* Calibration analysis
* Feature importance plots

#Report

A full academic report accompanies this project, detailing:

* methodology
* model development
* evaluation and results
* discussion and conclusions

#Author

Sneha Sree Parvathaneni
University of Hertfordshire

