# Linear Regression

As a conclusion of Linear Regression model.
I tried to implement
#### 1. Linear regression with One Variable Using Ordinary Least Square Method
#### 2. Linear regression with One Variable Using Gradient Descent
#### 3. Linear regression with One Variable Using sklearn.linear_model
#### 4. Linear regression with Mutiple Variable Using Gradient Descent by solving equation
#### 5. Linear regression with Mutiple Variable Using Gradient Descent by Matrix Implementation
#### 6. Linear regression with Mutiple Variable Using sklearn.linear_model


## Linear Regression One Variable

### Dataset Used
*Headbrain.csv* this dataset contains head size and brain weight of 237 different people. This data set has other features. But, we will not use them in this model.

#### Linear Regression using Gradient Descent
#### Accuracy :  0.5657205360649368
#### Linear Regression using Ordinary Least Square Method
#### Accuracy :  0.6393117199570004
#### Linear Regression using sklearn.linear_model
#### Accuracy :  0.6393117199570001

Ordinary Least Square Method and sklearn.linear_model gives almost same accuracy but Gradient Descent gives bit less accuracy



## Linear Regression Mutiple Variable

### Dataset Used
*student.csv* In this particular dataset, we have math, reading and writing exam scores of 1000 students. We will try to find a predict the score of writing exam from math and reading scores.

#### Linear Regression using Gradient Descent by solving equation
#### Accuracy :  0.9097223273061553
#### Linear Regression using Gradient Descent by Matrix Implementation
#### Accuracy :  0.9097209716909908
#### Linear Regression using sklearn.linear_model
#### Accuracy :  0.9098901726717316

Gradient Descent by solving equation is much slower than Gradient Descent by Matrix Implementation i suggest to used Matrix Implementation.

## Model Evaluation 

#### On Using Sklearn.linear_Model
Model is evaluated using _from sklearn.metrics import mean_squared_error and inbuilt sklearn score fn_ 

#### On Using Gradient Descent
Model is evaluated using root mean squared error and R2 score 

#### Resource Used
[Andrew Ng](https://www.youtube.com/watch?v=Hxm4ERsDv5U&index=1&list=PLBAGcD3siRDghsFtvJH9HjWSq9DHk1fTJ),
[mubaris article](https://mubaris.com/posts/linear-regression/)
