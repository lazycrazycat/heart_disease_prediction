# Heart Disease Prediction with Machine Learning and an Artificial Neural Network

## Project Overview

This project explores heart disease prediction using supervised machine
learning and a fully connected artificial neural network (ANN). It
compares several classification algorithms and evaluates their
performance on a heart disease dataset.

> **Note:** This is an educational project, not a medical diagnostic
> tool.

## Objectives

-   Explore and prepare the dataset for classification.
-   Compare traditional machine learning classifiers.
-   Tune selected models using grid search.
-   Build and evaluate an artificial neural network.
-   Compare model performance using classification metrics.

## Workflow

1.  Exploratory data analysis (EDA).
2.  Review of outliers and missing values.
3.  Data preprocessing, including categorical encoding and feature
    scaling.
4.  Training and comparison of classification models.
5.  Hyperparameter tuning.
6.  Building and evaluating a fully connected ANN.
7.  Comparing results using accuracy, precision, recall, F1-score, and
    ROC-AUC where available.

## Models

The notebook explores multiple classification approaches, including:

-   Logistic Regression
-   K-Nearest Neighbors (KNN)
-   Support Vector Machine (SVM)
-   Decision Tree
-   Random Forest
-   AdaBoost
-   XGBoost
-   CatBoost
-   Artificial Neural Network (ANN)

## Selected Results

  --------------------------------------------------------------------------------
  Model             Accuracy    Precision       Recall        F1-score      ROC-AUC
  ------------ ------------ ------------ ------------ --------------- ------------
  Tuned                                                          
  Logistic   
  Regression          0.837        0.808        0.880           0.821        0.921                                                        

  Artificial             
  Neural                                                               
  Network          0.853        0.765        0.963   approximately  0.85    Not listed 
                                                                            here
  --------------------------------------------------------------------------------

The metrics above are reproduced from the notebook and are not an
independent validation of the models. In particular, recall and
precision describe different aspects of classification performance, so
accuracy alone should not be used to compare models.

## Technologies

-   Python
-   Jupyter Notebook
-   pandas and NumPy
-   scikit-learn
-   TensorFlow / Keras
-   Matplotlib and Seaborn
-   XGBoost and CatBoost


## Limitations

-   This is a learning project based on a particular dataset.
-   The reported results depend on the dataset, preprocessing choices,
    and evaluation setup in the notebook.
-   Performance on this dataset does not establish clinical usefulness
    or generalization to other populations.
-   The model must not be used to make medical decisions.

## Author

GitHub: [@lazycrazycat](https://github.com/lazycrazycat)
