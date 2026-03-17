
# Network Attack Detection using Machine Learning

## Overview
This project focuses on building a machine learning model to detect and classify network attacks in IoT environments using the Bot-IoT dataset.

## Dataset
A subset of the Bot-IoT dataset was used, consisting of approximately 1.5 million records selected from three different files.  
The dataset includes three main types of attacks:

- Denial of Service (DoS)
- Distributed Denial of Service (DDoS)
- Reconnaissance

Dataset source:
https://www.kaggle.com/datasets/vigneshvenkateswaran/bot-iot

## Data Preprocessing
Extensive preprocessing was applied to prepare the data for modeling, including:

- Handling missing values
- Encoding categorical features
- Log transformation for skewed features
- Feature scaling
- Handling rare categories
- Feature selection based on importance

## Model
A Random Forest classifier was trained to detect and classify network attacks.

## Results
The model was evaluated on a test set of approximately 250,000 samples and achieved strong performance in predicting attack types.

## Goal
The goal of this project is to build an effective intrusion detection model capable of identifying malicious network traffic in IoT systems.

## Tools & Technologies
- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn
- pca
