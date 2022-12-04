# TuniHack


## 1. Prepare, clean and encode Data

We have 2 different datasets :
1.  Public Data from kaggle : https://www.kaggle.com/datasets/aditiharsh/mental-health-dataset
2.  Data collected from a survey via social media

We will start by **preparing and cleaning** each dataset than merge them together. 

Then we will encode the resulting dataset.

Finnaly, we will **analyze** the weights of the features in the dataset through a HeatMap in order to select the features we will be using in our first Model.

We will thus obtain two files : ``data_for_model1.csv`` and ``data_for_model2.csv``

## 2. Build, run and evaluate the first Model

After importing the file created previously, we will **scale and split** our dataset into train and test data with 80/20.

Then, we will build 6 different supervised ML models (Logistic Regression, Support Vector Machines, Decision Trees, Random Forest, Naive Bayes and K-Nearest Neighbors).

We will evaluate them by their **accuracy** and **f1-score**. 

We ended up choosing Naive Bayes with ``0.8`` f1-score and ``0.857143`` accuracy.

We will also build a DL model with 3 hidden layers. The model has ``0.92`` f1-score and ``0.8333`` accuracy.

We decided to go with the Naive Bayes because we discovered that the DL Model is overfitting.


## 3. Build, run and evaluate the second Model

We will do the same steps as for the first model.

Here we decided to use the Decision Tree Model with  ``0.8`` f1-score and ``0.642857`` accuracy.

We will also build a DL model with 3 hidden layers. The model has ``0.9289`` f1-score and ``0.7619`` accuracy.

## 4. Conclusion

