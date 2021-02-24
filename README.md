# CS205-TUTORIAL

In this this tutorial we will using a dataset called phising.csv.

The first step is to prepare the dataset and this includes collecting data, cleaning it and manipulating the data. Then, we train the model using supervised learning models: logistic regression. Next, we will be implementing naive bayes model. Finally we test the data and optimize the model.

 

For this tutorial, we are using different libraries:

Pandas (https://pandas.pydata.org/) to manipulate datasets,
other library to help with already implement function and attributes like Matplotlib (https://matplotlib.org/), Numpy (http://www.numpy.org/) but also Seaborn (https://seaborn.pydata.org/).
Before starting this tutorial, make sure that you imported the dataset in the files used by Google collab.

It is a good practice to import all the libraries at the beginning of the code.
Approach:
To design a system for predicting phishing websites, we import the phshing dataset from Kaggle: https://www.kaggle.com/akashkr/phishing-website-dataset.

This dataset consists of 32 attributes. We try to predict the probability of illegitimate websites using the 2 machine algorithms -Logistic Regression and Naive Bayes.

Steps followed:
Step 1: Load Data

Step 2: Splitting dataset into train and test set

Step 3: Implement Algorithms

Step 4:Evaluate predictions of algorithms

import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

%matplotlib inline

import os

from google.colab import files
uploaded = files.upload()
