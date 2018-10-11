# StockPrediction-SVM

## Support Vector Machine:-

###### Hyperplane
    Seperating plane between two categories of data. The equation of the hyperplane is:-  UW + B
    U -> Unknow vector
    W -> Perpendicular vector from origin to the hyperplane
    B -> Bias variable
    
###### Support Vectors
    They are the vectors whose removal will affect the hyperplane.
    
###### Optimization modules
    i) CVXOPT
    II) LibSVM
    
    The goal of optimization is to minimize vector 'W' and maximize bias variable 'B'. This optimization problem is known as Convex problem.
    
## Support Vector Regression

It is a regression problem used to find continious value using SVM approach. Support vector regression comes under polynomial regression. 

###### Kernel
    It is a funciton that maps lower dimensional data to higher dimensional data.
    
###### Conversion of non-linear data to linear data
    Non-linear problem is converted to linear one by adding dimensions. That's what kernel does. 
    
Support vector regression model is used to predict the stock price. There is no much difference between SVM and SVR. Simply, SVM is classification model and SVR is regreesion model. 

