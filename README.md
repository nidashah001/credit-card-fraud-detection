# credit-card-fraud-detection

## Dataset Link

The dataset used in this project can be found [here](https://drive.google.com/file/d/1WLZyKSL3CLeGZ6k2Py41UWQ6gT1AdDQt/view?usp=drive_link).



## Description

This project is a **Credit Card Fraud Detection System** designed to identify fraudulent transactions from a credit card dataset using machine learning models like **Logistic Regression** and **Decision Tree Classifier**. The goal is to predict whether a transaction is fraudulent or not, based on various features such as transaction amount, time, and anonymized account details.

The dataset used in this project contains information about credit card transactions, where each record is either fraudulent (Class = 1) or not (Class = 0). The system helps in detecting fraudulent activity and reducing financial loss.

## Features

- **Data Preprocessing**: Handles missing values, scales features, and addresses class imbalance using **RandomOverSampler**.
- **Model Training**: Implements machine learning models like **Logistic Regression** and **Decision Tree Classifier**.
- **Hyperparameter Tuning**: Uses **RandomizedSearchCV** to optimize decision tree parameters.
- **Model Evaluation**: Evaluates model performance using classification metrics like **accuracy**, **precision**, **recall**, **F1-score**, and **confusion matrix**.
- **Prediction**: Predicts if a new transaction is fraudulent or not.

## Project Structure

- **fraud_detection.py**: The main Python script where data is preprocessed, models are trained, and predictions are made.
- **creditcard.csv**: The dataset used for training and testing the models.
- **README.md**: This file.
- **requirements.txt**: A list of required libraries for the project.

## Installation

### Prerequisites

To run this project, you need to have Python 3.x and the following libraries installed:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- imbalanced-learn
  

### Install Libraries

You can install all required libraries using `pip`:

```bash
pip install -r requirements.txt

pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
