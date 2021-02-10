# Linear Models for Supervised Learning

# Data Sets - Two data sets are provided:

1. A medical data set is provided in the "\diabetes.pickle" along with the target assignment. 
The input variables correspond to measurements (physical, physiological, and blood related) for a given patient
and the target variable corresponds to the level of diabetic condition in the patient. It contains:

- xtrain (242 x 64) and ytrain (242 x 1) for training.
- xtest (200 x 64) and ytest (200 x 1) for testing.

2. A 2D sample data set in the "\sample.pickle".

The following problems are implemented on these datasets:

# Part I - Linear Regression

Problem 1: Linear Regression with Direct Minimization

Here, we were asked to implement the least squared method to estimate the regression
parameters. These parameters will be used to calculate the Root mean squared error i.e
RMSE.

Problem 2: Using Gradient Descent for Linear Regression Learning

Gradient descent can be used to calculate the weights ’w’ in a better and efficient way.
Then we can use these weights to minimize the loss function.

# Part II - Linear Classifiers

Three classifiers implemented are:

1. Perceptron.
2. Logistic Regression.
3. Linear Support Vector Machine (SVM).

Problem 3: Using Gradient Descent for Perceptron Learning

Perceptron is similar to the squared loss function. We trained our model to predict the
accuracy of this function.

Here, the perceptron predicted our accuracy as 84% for both training and test data.

Problem 4: Using Newton's Method for Logistic Regression Learning

In the Newton’s method we compute a Hessian matrix which will give us logistic loss for
the given data set. For this, we had to first calculate the logistic loss and gradient
vector of this logistic loss.

The predicted accuracy for logistic loss were 84% and 86% for training and test data
respectively. This accuracy prediction is almost similar to the prediction we got using
the Perceptron learning method.

Problem 5: Using Stochastic Gradient Descent Method for Training Linear Sup-
port Vector Machine

The SVM model is used to learn the weights of the training data using the hinge loss
function. Here we trained the model to predict the weights using 200 iterations of the
hinge loss function.

We got the prediction of the accuracy as 85% and 87% on the training and test data
respectively, which is more accurate than the what we got using Perceptron and
Newton’s method. This shows that SVM can give better results and more accuracy for
minimizing the loss function.

Problem 6: Comparing Linear Classifiers

Here, we compared the results of the 3 classifiers we implemented above. This is the
graph we got..

![caption](https://github.com/vinita1005/ML/blob/linear_reg_classifier/Graphs.PNG)
