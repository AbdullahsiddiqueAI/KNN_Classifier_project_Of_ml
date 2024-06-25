# Diabetes Prediction using K-Nearest Neighbors (KNN) Classifier
This project involves predicting whether a person has diabetes based on various medical attributes using a K-Nearest Neighbors (KNN) classifier. The dataset used is the PIMA Diabetes Dataset from Kaggle, which contains several features related to the medical history and condition of patients.

# Dataset
The dataset can be found on Kaggle at the following link:
[Diabetes Dataset CSV](https://www.kaggle.com/datasets/saurabh00007/diabetescsv)

# Data Collection and Analysis


# Loading the Data
The data is loaded from a CSV file into a pandas DataFrame.

# Exploring the Data
The first few rows of the DataFrame are printed to get an overview of the dataset.
The shape of the dataset is checked to understand the number of rows and columns.

# Dataset Overview
The dataset consists of the following columns:

Pregnancies
Glucose
BloodPressure
SkinThickness
Insulin
BMI
DiabetesPedigreeFunction
Age
Outcome
Data Preprocessing
Separating Features and Target
The features (all columns except 'Outcome') and the target ('Outcome') are separated into different variables:

X: Features
Y: Target

# Train-Test Split
The dataset is split into training and testing sets to evaluate the performance of the model. The split is done using an 80-20 ratio, with stratification based on the target variable to maintain the distribution of classes.

# Model Training
KNN Classifier in Sklearn
A K-Nearest Neighbors classifier from the sklearn.neighbors module is used. The classifier is initialized with the parameter p=1, which specifies the use of Manhattan distance.

# Model Evaluation
Accuracy Score
The accuracy of the model is evaluated on the test data. The accuracy score provides an indication of how well the model is performing.

# Conclusion
This project demonstrates the process of training a KNN classifier to predict diabetes based on various medical attributes. The model's performance is evaluated using the accuracy score on the test data.

# Note
Ensure you have the required libraries installed in your Python environment:

numpy
pandas
scikit-learn
How to Run
Download the dataset from the Kaggle link provided.
Place the CSV file in your project directory.
Run the Python script to load data, preprocess it, train the model, make predictions, and evaluate the results.