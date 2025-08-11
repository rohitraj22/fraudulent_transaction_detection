Fraudulent Transactions Detection
This project focuses on detecting fraudulent transactions using a machine learning model. The model is built using a logistic regression classifier and is trained on a dataset of financial transactions. The project includes a Jupyter notebook for the model development process and a Streamlit application for real-time predictions.

📋 Table of Contents
Project Overview

Dataset

Model

Streamlit App

Installation

Usage

📝 Project Overview
The goal of this project is to build a reliable model for identifying fraudulent financial transactions. The process involves:

Exploratory Data Analysis (EDA): Understanding the data and identifying patterns related to fraud.

Feature Engineering: Creating new features to improve model performance.

Model Training: Building and training a logistic regression model.

Model Evaluation: Assessing the model's performance using various metrics.

Deployment: Creating a Streamlit app to make real-time predictions.

📊 Dataset
The dataset used in this project is Fraud.csv, which contains information about financial transactions. The key features include:

step: Represents a unit of time in the real world.

type: The type of transaction (e.g., CASH_OUT, PAYMENT).

amount: The amount of the transaction.

nameOrig: The customer who started the transaction.

oldbalanceOrg: The initial balance before the transaction.

newbalanceOrig: The new balance after the transaction.

nameDest: The customer who is the recipient of the transaction.

oldbalanceDest: The initial balance of the recipient before the transaction.

newbalanceDest: The new balance of the recipient after the transaction.

isFraud: Indicates whether the transaction is fraudulent (1) or not (0).

🤖 Model
The machine learning model is a logistic regression classifier. It is trained to distinguish between fraudulent and non-fraudulent transactions based on the features in the dataset. The model is saved as fraud_detection_pipeline.pkl.

🚀 Streamlit App
The Streamlit app (fraud_detection.py) provides a user-friendly interface for making real-time predictions. Users can input transaction details, and the app will predict whether the transaction is fraudulent or not.

⚙️ Installation
To run this project, you need to have Python installed. You can then install the necessary libraries using pip:

pip install pandas numpy scikit-learn streamlit joblib

Usage
Clone the repository:

git clone https://github.com/your-username/Fraudulent-Transactions-Detection.git

Navigate to the project directory:

cd Fraudulent-Transactions-Detection

Run the Streamlit app:

streamlit run fraud_detection.py
