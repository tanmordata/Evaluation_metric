# Understanding Evaluation Metrics

![alt text](https://www.pngitem.com/pimgs/m/401-4013771_pred-analytics-prediction-analytics-icon-hd-png-download.png)

Developing a predictive model is the use of historical data to make decisions about future events that have not occurred yet. 
Evaluation metrics are used to test how “good” a model’s performance is. There are plenty of metrics available and the process of choosing the correct metric is dependent on the problem that is being asked and characteristics of the data used. 
Metrics to evaluate a classification problem look to demonstrate the performance of predicting categorical values. A common example of a problem would be in identifying emails as either ‘spam’ or ‘not spam’.  

The most common classification metrics are:
Confusion matrix: visualizes the performance of a classification metric by grouping predicted values into four categories. In the image below, we see four outcomes based on an evaluation against the actual values. The true positive and true negative values are the result of having our predictions match our actual values. In the false positive and false negative areas, we incorrectly predict our values based on our actual ones. These lead to Type I (false positive) and type II (false negative) errors. 
![alt text](https://miro.medium.com/max/431/0*AN_NBuYefGEHm6hP)

Accuracy: a measurement of how ‘correct’ our prediction is and is the ratio of correct predictions to total predictions.

Precision: the number of true positive values over total predicted positive values and focuses on type I errors. 

Recall: how many actual positive values are predicted correctly with the model. This is important in cases where the limiting false negative values is of higher concern. 

Metrics evaluating numerical values assigned by regression models “is the task of approximating a mapping function (f) from input variables (X) to a continuous output variable (y)”. These metrics tend to focus on error. Some common metrics are:

Mean squared error (MSE): the mean of squared differences between actual and predicted values 

Mean absolute error (MAE): average of the absolute difference between actual and predicted values 

Root mean squared error (RMSE): the root of the mean squared error: it reduces the sensitivity to outliers that are affected in the MSE

![image](https://user-images.githubusercontent.com/97196000/168316778-8270c78c-7028-47a0-8afe-42b53136f045.png)

When choosing between the two metric sets, it is important to understand what type of questions the model is supposed to answer and what kind of data is available because some metrics will not be applicable. For example, the accuracy function of a confusion matrix applies to classification models but does not apply to regression models because it cannot be calculated for a regression problem  which does not categorize data in the same way. Taking these details into account will ensure the best metrics are applied when evaluating a model.

Sources: 

https://neptune.ai/blog/performance-metrics-in-machine-learning-complete-guide

https://machinelearningmastery.com/regression-metrics-for-machine-learning/

https://medium.com/analytics-vidhya/performance-metrics-classification-model-69a5546b118c

https://www.kdnuggets.com/2020/05/model-evaluation-metrics-machine-learning.html

https://www.kaggle.com/code/nkitgupta/evaluation-metrics-for-multi-class-classification/notebook

https://www.analyticsvidhya.com/blog/2021/07/metrics-to-evaluate-your-classification-model-to-take-the-right-decisions/
