# ResamplingMethods_CrossVal.Bootstrap

Homework3-1
•
Cross-validation
–
sklearn.model_selection.LeaveOneOut
–
sklearn.model_selection.Kfold
–
sklearn.model_selection.cross_val_score
•
(1) Cross validation
–
Read ‘data07_iris.cvs’ and plot train, cv, and test errors using KNN method by changing K from 1 to 40


Homework3-2
•
(2) Bootstrap
–
Read ‘data07_iris.cvs’ and find a linear regression model for Sepal.Length~ Sepal.Width+Petal.Length+Petal.Width
–
Using ‘data07_iris.cvs’, generate abootstrapeddataset and find a linear regression model for 
Sepal.Length~ Sepal.Width+ Petal.Length+ Petal.Width. By repeating this many times, find the empirical distribution of 
intercept and coefficients. Provide their histograms. What is their means and standard deviations? Find their empirical 
95% confidence intervals.
–
As we did in Linear Regression, find the intercept and coefficient, their standard errors, and 95% confidence intervals 
(hint. use StatsModels)
–
Comparetheanalysesofbootstrappingandt-statistics.
