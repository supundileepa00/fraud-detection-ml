
<h1 align = center>Credit Card Transactions Fraud Detection Using K-Nearest Neighbours (KNN)</h1>

## Requirements:
- pandas
- numpy
- sklearn
- matplotlib
- seaborn
- joblib

In this project we try to detect credit card transactions fraud detection using K-Nearest Neighbours (KNN) and as the dataset: [Credit Card Transactions Fraud Detection Dataset]([https://www.kaggle.com/mlg-ulb/creditcardfraud](https://www.kaggle.com/datasets/kartik2112/fraud-detection?datasetId=817870&searchQuery=svm) provided by Kaggle. For this analysis I focused more on data preprocessing because it helps to gain a better accuracy rather than just sending raw data and telling to build a model.

## Data Preprocessing
What is data preprocessing? It is a data mining technique that transforms raw data into understandable format. Raw data(real world data) is always incomplete and that data cannot be send through a model. Yhay would cause certain errors. That is why we need to preprocess data before sending through a model.

I have used severel preprocessing techniques in this analysis. Without further a do let's get started!!!

### Steps in Data Preprocessing
Here iare the steps I have followed;

  1. Import libraries
  2. Read data
  3. Checking for missing values
  4. Checking for categorical data
  5. Standardize the data
  6. PCA transformation
  7. Data splitting


## 1. Import libraries
As the main libraries, I am using Pandas, Numpy and time;

Pandas : Use for data manipulation and data analysis.
Numpy : fundamental package for scientific computing with Python.
As for the visualization I am using Matplotlib and Seaborn.

For the data preprocessing techniques and algorithms I used Scikit-learn libraries.

## 2. Read data
You can find more details on dataset here:
![image](![read data](https://user-images.githubusercontent.com/52014041/234171827-4c74498e-3a94-4f96-9c92-93b833b90e4a.png)
