# Credit Card Fraud Detection

## Overview

This repository contains a machine learning project for credit card fraud detection. The goal is to build models that can accurately identify fraudulent transactions in credit card data.

## Dataset

The dataset used in this project is obtained from [creditcard.csv](https://www.dropbox.com/s/9kwyyami2vzg56r/creditcard.csv?dl=1). It includes various features, excluding the 'Time' feature, and a binary target variable 'Class' indicating whether a transaction is fraudulent (Class = 1) or not (Class = 0).

## Preprocessing

- The 'Time' feature is dropped from the dataset.
- Data outliers are identified and removed to create a balanced training dataset.
- The dataset is split into training and testing sets.

## Models

Three machine learning algorithms are used for training:

1. K Nearest Neighbors
2. Logistic Regression
3. Decision Tree

## Training and Evaluation

### Entire Training Dataset

The models are trained on the entire training dataset, and their performance is evaluated on the test set.

### Downsampling with Outliers

The training dataset is downsampled with outliers, and models are trained and evaluated on the test set.

### Downsampling without Outliers

The training dataset is downsampled without outliers, and models are trained and evaluated on the test set.

## Results

The project provides insights into the performance of different models on various datasets and outlines key metrics such as accuracy, AUC score, true positive rate (TPR), false positive rate (FPR), training time, and the number of misclassified instances for each class.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/Venkat-Dhulipalla/Credit_Card_Fraud_Detection

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt

3. Run the Jupyter Notebook
    ```bash
    jupyter notebook Credit_Card_Fraud_Detection.ipynb
4. Follow the instructions in the notebook for data preprocessing, model training, and evaluation.
## Support


Feel free to customize and expand this template based on the specifics of your project.
