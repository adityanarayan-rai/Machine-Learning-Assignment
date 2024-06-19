# Course Assignments - Machine Learning

This repository includes the Python Assignments from the Machine Learning course I did for the partial completion of my MSc Data Science for Public Policy degree at Hertie School, Berlin

**Assignment 1:**

- Calculate summary statistics for the label and five features
- What is the formula for the closed-form estimate of the coefficient vector in ordinary least squares regression? Estimate the coefficients using numpy in Python by performing the matrix operations from the closed-form solution
- Estimate the coefficients using the statsmodels package and compare them
- Estimate the variance of the coefficients using the matrix formula
- Write a function with three arguments - beta: A 1D numpy array representing a particular value of your coefficients; label: A 1D numpy array of the labels in your dataset; features: A 2D numpy array representing the features in your dataset
- Using the SciPy library, minimize the objective function for logistic regression.
- Construct your predictions by taking the dot-product between *beta_logistic* and your feature matrix and then passing that dot-product through the sigmoid function
- Construct class estimates for your OLS predictions as well by calculating 1
- Calculate the full confusion matrix for the logistic regression and the OLS model.
- Plot the relationship between the predictions from the linear regression in Question 1 (on the x-axis) and the predictions from the logistic regression (on the y-axis). What do you see?
- Comment on supervised learning, unsupervised learning and reinforcement learning

**Assignment 2:**

- Exploratory Data Analysis - What do the variables look like? Is there missingness? What does the distribution of the outcome look like?
- Create the Training set and Test set
- Define how you are going to (1) impute missing data, (2)standardize the data and (3) fit the model.
- Using the pipeline you created, fit a ridge regression where the regularization parameter is alpha = 0.1 on the (entire) training set.
- Use the KFold class to construct a set of 10 folds to be used for cross-fold
- Using the training data, use cross-validation to choose a good value of the regularization parameter.
- Point out which value of the regularization parameter (and therefore which model) you would choose to use based on these results, using the one-standard-error rule
- Create a new version of your function from Question 3 which replaces ridge regression with KernelRidge
- Find the cross-validated MSE for a range of values of gamma
- Calculate the error in the test set for both your best Ridge and KernelRidge model. Which is better?

**Assignment 3:**
