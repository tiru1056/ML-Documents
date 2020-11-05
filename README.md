# Assignment 2

This Assignment has 3 sub-problems which are implemented individually 

## Problem 1 :- Implementing logistic regression using sigmoid function and cross entropy
- Generate Train and test data sets each of 1000 values using the mu and sigma values
- Assign the labels 0 and 1 for 500 each of set 0 and set 1 of Train data and similarly for the test data
- Implement the logistic regression using sigmoid function and logloss function
 -  Sigmoid transforms the values between the range 0 and 1.
    -   Here is the mathematical expression for sigmoid
           - f(x) = 1/(1+e^-x)
 -  LoglossFunction,measures the performance of a classification model whose output is a probability value
    between 0 and 1. Cross-entropy loss increases as the predicted probability diverges from the actual label. 
- Calculate the accuracy of the model
- Plot ROC Curve graph and define the AUC Area Under Curve for the model
- Plot The graph between the no of iterations and the learning rate
 

#### Open file from the command line 'jupyter notebook ML_assignment2_01.ipynb ', using jupyter notebook

## Problem 2:- Implementation multi-class logistic regression using a soft-max function and cross entropy
- Read in Train and Test data set MNIST dataset
- Using only images within class 0 to 5(for Train and Test Data)
- Implemented Multi-class Logistic regression using softmax and Cross entropy loss function
  - Softmax Regression is a form of logistic regression that normalizes an input value into 
    a vector of values that follows a probability distribution whose total sums up to 1.
  - The output values are between the range [0,1]
  - we are able to avoid binary classification and accommodate as many classes or dimensions 
    in our model
  -  softmax is sometimes referred to as a multinomial logistic regression.
- Classification report has given the values of our multi class logistic regression model
- Accuracy,Precision and Recall score are used for analysing the performance of our model


#### Open file from the command line 'jupyter notebook ML_assignment2_02.ipynb ', using jupyter notebook

## Problem 3:- Implement Artifical Neural Network Classifier using existing libraries to classify the MNIST dataset 

Read in Train and Test MNIST data set 
- Using only images within class 0 to 5(for Train and Test Data)
- Using the existing MLP (Multi layer Perceptron Classifier) classifier, and with 3 hidden layers each with 150 , 100 and 50 
  hidden units 
  - ReLU (Rectified Linear Unit)Activation Function is used for the first classification report
     -  The formula is deceptively simple: max(0,z). Despite its name and appearance, it’s not linear and provides the same             benefits as Sigmoid but with better performance.
  - Sigmoid Activation Function is used for the second classification report
     -  Sigmoid transforms the values between the range 0 and 1.
        Here is the mathematical expression for sigmoid
           - f(x) = 1/(1+e^-x)
- Accuracy,Precision and Recall score are used for analysing the performance of our model
#### Open file from the command line 'jupyter notebook ML_assignment2_03.ipynb ', using jupyter notebook

