# diabetes-Prediction-using-logistic-regression-
This Logistic Regression model was created as part of an exciting assignment in our Machine Learning class, where our goal was to forecast the likelihood of diabetes in patients based on their responses to specific medical questions.

To build this model, we utilized a dataset from Kaggle (https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset) and employed the LogisticRegression model from the linear_model module in the Sklearn library. The model achieved an impressive accuracy of 84.4%.

Initially, we normalized the data using Min-Max scaling, a technique that rescales values to a range between 0 and 1, leveraging the minimum and maximum values of the original data. Following this, we filtered the data by replacing all the given 0s (unknown values) with the mean of other values in the same tuple.

The training process ensued, accompanied by a series of inquiries. The model, now armed with its predictive prowess, can determine whether certain health conditions might be indicative of diabetes or not.

Our journey involved not just crafting a predictive tool but also fine-tuning the data to ensure optimal performance. Let's delve into the fascinating world of diabetes prediction and discover the insights our model has uncovered!





