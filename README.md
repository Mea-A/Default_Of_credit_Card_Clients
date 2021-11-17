# Default_Of_credit_Card_Clients
T5 bootcamp project /
Meaad Almutairi


Abstract
  Defaults of credit cards are one of the biggest  problems for many companies and banks . On time and efficient identification of probability of default  plays a key role in saving banks from any crisis , particularly in the field of payments. In this project, I built an efficient and accurate model to detect the default credit card  of the customers and the model is based on machine learning techniques. Particularly supervised learning algorithms. The model is developed based on classification algorithms including Support vector machine and Decision tree. I applied the models after exploring the best features. After I trained the  models  I  evaluated each one using an accuracy metric.


Design
  This project is part of the course requirements. Data provided by UCI Machine Learning Repository has been used in this project. Default of credit card clients Data Set to estimate the real probability of default. the binary result of classification - credible or not credible clients  using machine learning algorithms would enable understanding of clients.


Data
   This data is set to the case of customers' default payments in Taiwan and compares the predictive accuracy of the probability of default. The data includes  24 columns. 23 columns contain independent variables and one dependent variable which will predict default payment next month. And 30000 instances . as the UCI site mentioned.
   
   
   Algorithms

Feature Engineering:

Applied a Standard Scaler method to scaling data before applying the model.

Splitting  data into train data and test data, 70% of data is used to train models during the learning process.
Checking missing values


Models

Decision Tree Classifier (DTC) and Support Vector Machine Classifier  (SVM) . SVM gives higher accuracy than DTC.

Model Evaluation and Selection

The entire training dataset of records was split into 70/30 train vs. testing and all scores reported below were calculated.


The official metric was classification rate (accuracy); however, class weights were included to improve performance against F1 score
Accuracy 0.727

For SVM:
Accuracy: 0.818


Tools
  Numpy and Pandas for data manipulation   
  Scikit-learn for modeling
  Matplotlib and Seaborn for plotting and visualizations      
  Jupyter Notebook to write code 
  
  
  Communicatiom
  




