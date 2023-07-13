# Credit Card Fraud Detection Project

## Project Overview
This project aims to build a machine learning model to detect fraudulent credit card transactions. We use the K-Nearest Neighbors (KNN) algorithm for this classification task. 

## Requirements
This project requires the following Python libraries:
- numpy
- pandas
- sklearn

You can install these with pip:
```
pip install numpy pandas sklearn
```

## Setup
To set up this project on your local machine:

- Clone the repository
- Install the necessary Python libraries
- Download the dataset from Kaggle and place it in the data director

## Usage
To run the project, navigate to the src directory and run main.py:

```
python main.py
```

This will train the model and evaluate its performance.

## Data
The data for this project comes from a Kaggle dataset, which contains transactions made by European credit card holders in September 2013. The dataset is highly unbalanced, with 492 frauds out of 284,807 transactions.

The data has been transformed using Principal Component Analysis (PCA) for confidentiality reasons. The only features which have not been transformed with PCA are 'Time' and 'Amount'. The 'Class' feature is the response variable and it takes value 1 in case of fraud and 0 otherwise.

[Link](https://www.kaggle.com/datasets/whenamancodes/fraud-detection)

## Model
The model used in this project is the K-Nearest Neighbors (KNN) classifier from the Scikit-Learn library. The model is trained using the features from the dataset and then evaluated on a separate test set.

## Contribute
We welcome contributions to this project. Please feel free to submit a pull request or open an issue on GitHub.