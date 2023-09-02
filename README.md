# Chance-of-Admission-Prediction-Model

The dataset and the content described below has been taken from YBI-Foundation.com for the better understanding of the readers. Please click the link below to download the dataset.

https://github.com/YBI-Foundation/Dataset/blob/main/Admission%20Chance.csv

# Content

The dataset contains several parameters which are considered important during the application for Masters Programs. The parameters included are :

GRE Scores (290 to 340)

TOEFL Scores (92 to 120)

University Rating (1 to 5)

Statement of Purpose (1 to 5)

Letter of Recommendation Strength (1 to 5)

Undergraduate CGPA (6.8 to 9.92)

Research Experience (0 or 1)

Chance of Admit (0.34 to 0.97)

# GOAL

Our goal here would be to predict the “Chance of Admit” based on the different parameters that are provided in the dataset.

We will achieve this goal by using the Simple Linear Regression model.

Based on the data that we have, we will split out data into training and testing sets. The Training set will have features and labels on which our model would be trained. The label here is the “Chance of Admit”. If you think from a no-technical standpoint then label is basically the output that we want and features are the parameters that drive us towards the output. Once our model is trained, we will use the trained model and run it on the test set and predict the output. Then we will compare the predicted results with the actual results that we have to see how our model performed .

This whole process of training the model using features and known labels and later testing it to predict the output is called Supervised Learning.

Now, before diving into how to prepare and model out data, let’s have a brief understanding on how Simple Linear Regression works.

# Linear Regression

It is a statistical method which is used to obtain formulas to predict the values of one variables from another where there is a relationship between the 2 variables.

The formula for simple linear regression is that of a straight line y =mx + c

The variables y and x in the formula is the one whose relationship will be determined.

Both the variables are named as below:

1. y : Dependent variable
2. x : Independent variable

The above equation is more equivalent to the slope intercept form in which the dependent variable is denoted by y, and c denotes the intercept, m denotes the slope, and x is the independent variable.

So, if we are given a particular Independent Variable x, the regression model would basically compute the results of c and m which would minimize the absolute difference between the dependent variable y which is the actual value we have and the predicted value of y.

To create the Linear Regression model we will use python.

