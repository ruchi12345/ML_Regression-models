# ML_Regression-models
### Machine learning:

Machine learning is a part of artificial intelligence (AI) that provides systems the ability to automatically learn and improve from experience.The main focus of machine learning is to develop the computer programs.ML are those that can learn from data and improve from experience, without human intervention. Learning tasks may include learning the function that maps the input to the output. To select the right alogritm is key part of ml.

###  Supervised learning:
supervised learning use labeled training data to learn the mapping function from the input variable to the output variable.

Supervised learning can be of two types:

### 1.Classification: 
To predict the outcome of a given sample where the output variable is in the form of categories
### 2.Regression: 
To predict the outcome of a given sample where the output variable is in the form of real values.

## The algorithms we cover in this blog is:
1.Linear Regression

2.Support vector Regression

3.Random forest Regression

4.Decision Tree Regression

5.polynomial Regression

6.Ridge Regression

7.Lasso Regression

8.Elastic net Regression

9.Bayesian regression

10.Adaboost regression

11.Principal Components Regression

12.Partial Least square Regression

13.Gradient Boosting Regression

14.XGBoost Regression

15.SGD Regressor


### Linear Regression:

This Regression algorithm finds the relationship between dependent variable and independent variable. We have set of input variable that are used to identify the output variable.The goal of ML is to quantify this relationship.
Linear Regression is represented as a line in the form of y = a + bx.

### Support vector Machine-Regression(SVR):

Support Vector Machine can also be used as a regression method,The Support Vector Regression (SVR) uses the same principles as the SVM for classification, with only a few minor differences.First of all, because output is a real number it becomes very difficult to predict the information at hand, which has infinite possibilities.It create hyperpalne with maximum margin from support vectors.

### Random Forest Regression:

Random forest creates multiple decision trees on randomly selected data samples, then merge that trees for the accurate and stable output. It is flexible and easy to use alogrihtm.As the name suggest it create forest of trees,features are the root nodes and subnodes are the trees created by the random forest.

### Decision Tree Regressor:

A decision tree is graphical represention of all the possible solutions to a decision tree based on certain conditions. It is decision tress because it start with a single root it create tree for the best fir output.

### Polynomial Regression:

It is a technique to fit a nonlinear equation by taking polynomial functions of independent variable.There are some relationships that a researcher will hypothesize is curvilinear. Clearly, such type of cases will include a polynomial term.

### Ridge Regression:

Ridge regression is for reduce the complexity of model that is number of predictors.Removing predictors from the model can be seen as settings their coefficients to zero. Instead of forcing them to be exactly zero.

### Lasso Regression:

Lasso regression is as same as the ridge regression  both used for the reduce the complexity of model.The only difference 
instead of taking the square of the coefficients, magnitudes are taken into account. some of the features are completely neglected for the evaluation of output. So Lasso regression not only helps in reducing over-fitting but it can help us in feature selection.

### Elastic net Regression:

The method linearly combines the L1 and L2 penalties of the LASSO and Ridge Regression. Including the Elastic Net, these methods are especially powerful when applied to very large data where the number of variables might be in the thousands or even millions.

### Bayesian regression:

Bayesian regression techniques can be used to include regularization parameters in the estimation procedure,the regularization parameter is not set in a hard sense but tuned to the data at hand.

### Adaboost regression:

It is Adaptive boasting Algorithm aims to convert a set of weak learners into a strong one. It starts by predicting original data set and gives equal weight to each observation. If prediction is incorrect using the first learner, then it gives higher weight to observation which have been predicted incorrectly.

### Principal Components Regression:

Principal Components Regression is a technique for analyzing multiple regression data that suffer from
multicollinearity.It Selects and keeps only the main principal components,The only hyperparameter is the number of principal components, which is an integer.It is used for Great for visualisation and intuitive understanding of the data.

### Partial Least square Regression:

It is extension of the multiple linear regression or general stepwise regression ,in the simplest form a linear model specifies the relationship between a dependent variable y and set of predictions.instead of finding hyperplanes of maximum variance between the response and independent variables it finds the linear regression model by projecting the predicted variables and the observable variables to a new space.

### Gradient Boosting Regression:

Gradient boosting is a machine learning technique for regression and classification problems, which produces a prediction model in the form of an ensemble of weak prediction models, typically decision trees.

### XGBoost Regression:
It is extreme Gradient Boosting Algorithm.There are two reasons to use this algorithm 1) Execution Speed 2) model performance,Generally It is fast compared to other gradient  Boosting implemantations.This algorithm was engineered for efficiency of compute time and memory resources. A design goal was to make the best use of available resources to train the model.

### SGD Regression:

It is Stochastic Gradient Descent Regression ,It regularizer is a penalty added to the loss function that shrinks model parameters towards the zero vector.The implementation of this works with data represented as dense numpy arrays of floating point values for the features.And this is also known as incremental gradient descent.














## Research Infinite Solutions LLP
by Research Infinite Solutions (https://www.ris-ai.com//)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE
