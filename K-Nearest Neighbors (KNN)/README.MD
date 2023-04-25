
<h1 align = center>Credit Card Transactions Fraud Detection Using K-Nearest Neighbours (KNN)</h1>

## Requirements:
- pandas
- numpy
- sklearn
- matplotlib
- seaborn
- joblib

In this project we try to detect credit card transactions fraud detection using K-Nearest Neighbours (KNN) and as the dataset: [Credit Card Transactions Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud](https://www.kaggle.com/datasets/kartik2112/fraud-detection?datasetId=817870&searchQuery=svm) provided by Kaggle. For this analysis I focused more on data preprocessing because it helps to gain a better accuracy rather than just sending raw data and telling to build a model.

## Data Preprocessing
What is data preprocessing? It is a data mining technique that transforms raw data into understandable format. Raw data(real world data) is always incomplete and that data cannot be send through a model. Yhay would cause certain errors. That is why we need to preprocess data before sending through a model.

I have used severel preprocessing techniques in this analysis. Without further a do let's get started!!!

### Steps in Data Preprocessing
Here iare the steps I have followed;

## 1. Import libraries
As the main libraries, I am using Pandas, Numpy and time;

Pandas : Use for data manipulation and data analysis.
Numpy : fundamental package for scientific computing with Python.
As for the visualization I am using Matplotlib and Seaborn.

For the data preprocessing techniques and algorithms I used Scikit-learn libraries.

## 2. Read data
You can find more details on dataset here:
![image](![read data](https://user-images.githubusercontent.com/52014041/234171827-4c74498e-3a94-4f96-9c92-93b833b90e4a.png)

## 3. Checking for missing values

## 4. Checking for categorical data
the only categorical cariable we have in this data set is the target variable. Other features are already in numerical format, so no need of converting to categorical data.

## 5. Standardize the data

## 6. PCA transformation
PCA (Principal Component Analysis) mainly using to reduce the size of the feature space while retaining as much of the information as possible. In here all the features transformed into 2 features using PCA.
  
## 7. Data splitting
For the model building I am using K Nearest Neighbors. So we need find an optimal K to get the best out of it.
![image](![data spitting](https://user-images.githubusercontent.com/52014041/234175524-f864a5f3-c14c-428f-a317-db647def61e3.png))


## Result -->
After applying the KNN algorithm to the dataset and performing the necessary data preprocessing, we obtained the following results:
![image](![result](https://user-images.githubusercontent.com/52014041/234175846-5c49ef4f-f17c-465d-b4a9-26792c644294.png))

## KNN Graphical Representation

### Graphical KNN representation 1 - Heatmap
![image](![heatmap](https://user-images.githubusercontent.com/52014041/234176610-abd0a76e-7549-42ac-b479-e8716ca96d02.png))


### Graphical KNN representation 2 - Decision Boundary
![image](![decision boundary](https://user-images.githubusercontent.com/52014041/234176671-977b983b-a801-4b88-93cf-4fdc7e9e7af1.png))

### Graphical KNN representation 3 - Voronoi diagram
![image](![voronoi diagram](https://user-images.githubusercontent.com/52014041/234176707-1d97db88-74e5-4a33-a6da-1c7c73324c74.png))

