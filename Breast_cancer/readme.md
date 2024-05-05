


Breast Cancer Detection with Support Vector Classifier (SVC)
This repository contains Python code demonstrating the use of Support Vector Classifier (SVC) for detecting breast cancer using the Breast Cancer Wisconsin (Diagnostic) dataset. The code showcases how to load the dataset, preprocess it, train an SVC model, and evaluate its performance.

Dataset
The dataset used in this project is the Breast Cancer Wisconsin (Diagnostic) dataset, which is a classic binary classification dataset. It contains features computed from digitized images of fine needle aspirates (FNA) of breast masses, describing characteristics of cell nuclei present in the images.

Number of Instances: 569
Number of Attributes: 30 numeric features
Classes: Malignant and Benign
Code Structure
The main script, breast_cancer_detection.py, performs the following tasks:

Data Loading and Exploration:
Loads the dataset using Scikit-learn's load_breast_cancer function.
Explores the dataset structure and content.
Data Preparation:
Converts the dataset into a Pandas DataFrame for easier manipulation.
Splits the dataset into training and testing sets using Scikit-learn's train_test_split function.
Model Training and Evaluation:
Initializes an SVC model.
Trains the model using the training data.
Makes predictions on the testing data.
Evaluates the model's performance using a classification report and confusion matrix.
