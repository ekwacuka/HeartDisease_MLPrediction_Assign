# Heart_Disease_ML_Prediction

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
  
  ![image](https://user-images.githubusercontent.com/77937714/114914029-dae33500-9def-11eb-91a8-2ccc1797f875.png)

  - Get the target and features
  
  ![image](https://user-images.githubusercontent.com/77937714/114914152-fa7a5d80-9def-11eb-8125-5b26d29cd91b.png)

  - Split into training and test set
  
  ![image](https://user-images.githubusercontent.com/77937714/114914279-1aaa1c80-9df0-11eb-976a-ed3e75078bba.png)
  
  - Create and fit your model using KNeighbors classification for five neighbors (sklearn) - KNN model fit
  
  ![image](https://user-images.githubusercontent.com/77937714/114914415-40372600-9df0-11eb-9a6f-3bbf26634394.png)

  - Predict on dataset model calculate Accuracy Score
  
  ![image](https://user-images.githubusercontent.com/77937714/114914503-59d86d80-9df0-11eb-8409-2cc3a735f3fd.png)

  - Calculate the model accuracy
  
  ![image](https://user-images.githubusercontent.com/77937714/114914605-7e344a00-9df0-11eb-889a-b1030c3ef67c.png)

  - Create a confusion matrix with a Pandas cross table - confusion matrix
  
  ![image](https://user-images.githubusercontent.com/77937714/114915139-33ff9880-9df1-11eb-9733-02db6abeee02.png)

  - Print the TN, FN, TP, FP values
  
  ![image](https://user-images.githubusercontent.com/77937714/114915230-50033a00-9df1-11eb-8cc0-1c51fbb82b66.png)

  
  - Print the model precision value - precision is the ratio of  tp / (tp + fp)

   ![image](https://user-images.githubusercontent.com/77937714/114915351-6dd09f00-9df1-11eb-98da-3b7e88a5ad5a.png)
   
  - Recall = the ratio tp / (tp + fn)
  
  ![image](https://user-images.githubusercontent.com/77937714/114915437-8f318b00-9df1-11eb-9ebf-ee57b1c4e3b0.png)

  - Visualize the confusion matrix with a Heatmap

   ![image](https://user-images.githubusercontent.com/77937714/114915541-ad978680-9df1-11eb-9dd3-7ae48315bf69.png)

