# HeartDisease_ML_Prediction_Assign

### This project is to create a model that predicts whether a person is at the risk of Heart Disease.

### Import necessary modules

    * import pandas as pd
    * import seaborn as sns
    * import matplotlib.pyplot as plt 
    * import numpy as np
    * from sklearn import metrics
    * from sklearn.neighbors import KNeighborsClassifier
    * from sklearn.feature_selection import SelectKBest
    * from sklearn.feature_selection import chi2
    * from sklearn.feature_selection import f_classif
    * from sklearn.model_selection import train_test_split
  
  ### The process to follow
  - Load the (heart.csv) dataset 
  - Get the target and features
  - Split into training and test set   
  - Create and fit your model using KNeighbors classification for five neighbors (sklearn) - KNN model fit
  - Predict on dataset model calculate Accuracy Score
  - Calculate the model accuracy
  - Create a confusion matrix with a Pandas cross table - confusion matrix
  - Print the TN, FN, TP, FP values
  - Print the model precision value - precision is the ratio of  tp / (tp + fp)
  - Recall = the ratio tp / (tp + fn)
  - Visualize the confusion matrix with a Heatmap
