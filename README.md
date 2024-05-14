# Introduction
SONAR (Sound Navigation Ranging) is a technology that uses sound waves to detect and locate objects underwater.The SONAR Rock vs Mine Prediction project uses sonar data to classify objects as either rocks or mines. The project employs logistic regression, a widely used statistical method for binary classification, to achieve accurate predictions. This classification is particularly useful in underwater explorations and military applications.

# Dataset
The dataset used in this project is collected from UCI Repository. It consists of 208 instances and 60 attributes, Each instance is labeled as either rock or mine.This data is used for training and testing purpose. The Last column in this dataset indicates that, whether it's a mine or a rock, which is useful in prediction. The dataset is included in this repository.

# Model
The model used here is Logistic Regression.Logistic regression is used for binary classification where we use sigmoid function, that takes input as independent variables and produces a probability value between 0 and 1.
As it a binary classification model it is perfect to predict if an object is mine or rock based on the sonar data.
