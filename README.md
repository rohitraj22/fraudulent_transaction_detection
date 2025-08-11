# Fraudulent Transactions Detection

## Overview

This project is dedicated to identifying fraudulent financial transactions through a machine learning model. It features a comprehensive Jupyter notebook detailing the model's development and a Streamlit application for interactive, real-time predictions.

## Features

* **Exploratory Data Analysis (EDA):** In-depth analysis to uncover patterns and insights related to fraudulent activities.
* **Feature Engineering:** Creation of new features to enhance the model's predictive power.
* **Machine Learning Model:** A logistic regression model trained to distinguish between fraudulent and legitimate transactions.
* **Interactive Web App:** A user-friendly Streamlit application for real-time fraud detection.

## Dataset

The model is trained on the `Fraud.csv` dataset. The details of the variables used in the dataset have been provided in the `Data Dictionary.txt` file

## Model Details

The core of this project is a **logistic regression classifier**, chosen for its interpretability and efficiency. The model is trained to differentiate between fraudulent and non-fraudulent transactions and is saved in the `fraud_detection_pipeline.pkl` file.

## Streamlit Application

The `fraud_detection.py` script launches a Streamlit web application that allows users to:

* Input transaction details through an intuitive interface.
* Receive instant predictions on whether a transaction is fraudulent.

##  Installation

To get started with this project, ensure you have Python installed. Then, install the required libraries:

```bash
pip install pandas numpy scikit-learn streamlit joblib
```

## Usage

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/Fraudulent-Transactions-Detection.git](https://github.com/your-username/Fraudulent-Transactions-Detection.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd Fraudulent-Transactions-Detection
    ```
3.  **Launch the Streamlit app:**
    ```bash
    streamlit run fraud_detection.py
    ```
