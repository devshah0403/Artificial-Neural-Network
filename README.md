# Artificial Neural Network
 Here, you will find the Python code. Using this Artificial Neural Network, the script classifies many medicines according to one given data set. The script explains end-to-end procedures about this, including preprocessing the dataset, creating models, and fitting.  Key elements include:  Load the drug dataset (drugdataset.csv). Splitting the data into training and test sets. Scaling the data to enhance the model's performance.

## Code Explanation
Import libraries necessary for data manipulation, numerical computations and graphical representation.
Import the drugdataset.csv file and look at the first few rows.
Identify different classes of drugs in the target variable.
Split features (X) and target labels (y) for training the models.
Split the dataset into an 80% training and 20% testing subset using stratified sampling techniques.
Standardize feature data to improve neural network performance.
Construct and train a multi-layer perceptron (MLP) classifier with three hidden layers:.
Predict the drug categories using the test dataset.
Evaluate model performance using a confusion matrix and classification report.
Present basic statistical information about the dataset to give an idea of its makeup.
## Getting Started
Here’s how you can get the project up and running on your computer.
### Prerequisites
Before you begin, make sure you’ve installed the following Libraries:
Pandas
Numpy
Matpotlib
### Installing
You can installed the libraries with following code:
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
%matplotlib inline
Make sure to place the dataset and python file in same folder
## Running the tests
Copy the code or open the same file with the same dataset and run in python
## Breakdown of tests
1) Here’s what it will do:

Train the Artificial Neural Network on the dataset.
Predict the drug classes for the test data.
Display a confusion matrix and a detailed performance report.
2) What You’ll See:

A confusion matrix showing how well the model performed.
A classification report with metrics like precision, recall, and F1-score for each drug type.

## Deployment
You can run this script locally to experiment with the dataset or use it as part of a larger project. If you want to make it accessible online, you can integrate it with a web framework like Flask or Django.

## Built With
Scikit-learn: For building and training the neural network.
Pandas and NumPy: For handling the dataset and numerical operations.
Matplotlib: Could be used for visualizations, though it’s optional for this project.

## Author
Dev Shah

## Licence
This project is open-source

## Acknowledgments
Thanks to my instructors and Durham College for teaching me the foundations of machine learning.
Scikit-learn’s documentation for being an excellent resource during the project.

