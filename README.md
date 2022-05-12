# Understanding Evaluation Metrics

Developing a predictive model is the use of historical data to make inferences about future events that have not occurred yet. 
Evaluation metrics are used to test how “good” a model’s performance is. There are plenty of metrics available and the use choosing the correct metric for one’s data is dependent on the problem that is being asked. These metrics can fall in either two categories: classification or regression.
Classification metrics assign a class label and are common in predicting categorical values. A common example of a label would be in identifying emails as either ‘spam’ or ‘not spam’. 

The most common classification metrics are:
Confusion matrix: visualizes the performance of a classification metric and use known values to test against predicted values. In the image below, we see four outcomes based on an evaluation against the actual values. The true positive and true negative values are the result of having our predictions match our actual values. In the false positive and false negative areas, we incorrectly predict our values based on our actual ones. These lead to Type I (false positive) and type II (false negative) errors. 

Accuracy: a measurement of how ‘correct’ our prediction is and is the ratio of correct predictions to total predictions. 
Precision: the number of true positive values over total predicted positive values and focuses on type I errors. 
Recall: how many actual positive values are predicted correctly with the model. This is important in cases where the limiting false negative values is of higher concern. 
Regression metrics involve predicting numerical values and “is the task of approximating a mapping function (f) from input variables (X) to a continuous output variable (y)”. Regression metrics deal with error instead of accuracy like a classification model does. Some common metrics are:
mean squared error (MSE): the mean of squared differences between actual and predicted values 
Mean absolute error (MAE): average of the absolute difference between actual and predicted values 
Root mean squared error (RMSE): the root of the mean squared error: it reduces the sensitivity to outliers that are affected in the MSE
When choosing between the two metrics, it is important to understand what type of questions the model is supposed to ask and what kind of data is available because some metrics will not be usable. For example, accuracy applies to classification but does not apply to regression because it cannot be calculated for a regression model. Additionally, RMSE cannot be done for classification models. 


Sources: 

https://neptune.ai/blog/performance-metrics-in-machine-learning-complete-guide

https://machinelearningmastery.com/regression-metrics-for-machine-learning/

https://medium.com/analytics-vidhya/performance-metrics-classification-model-69a5546b118c

https://www.kdnuggets.com/2020/05/model-evaluation-metrics-machine-learning.html

https://www.kaggle.com/code/nkitgupta/evaluation-metrics-for-multi-class-classification/notebook

https://www.analyticsvidhya.com/blog/2021/07/metrics-to-evaluate-your-classification-model-to-take-the-right-decisions/
