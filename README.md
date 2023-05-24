# Car_Price_Prediction


Problem Statement : A Chinese automobile company Geely Auto aspires to enter the US market by setting up their manufacturing unit there and producing cars locally to give competition to their US and European counterparts. They have contracted an automobile consulting company to understand the factors on which the pricing of cars depends. Specifically, they want to understand the factors affecting the pricing of cars in the American market, since those may be very different from the Chinese market. The company wants to know :

Which variables are significant in predicting the price of a car.
How well those variables describe the price of a car Based on various market surveys, the consulting firm has gathered a large dataset of different types of cars across the Americal market.
Business Goal : You are required to model the price of cars with the available independent variables. It will be used by the management to understand how exactly the prices vary with the independent variables. They can accordingly manipulate the design of the cars, the business strategy etc. to meet certain price levels. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

StandardScaler removes the mean and scales each feature/variable to unit variance. This operation is performed feature-wise in an independent way. StandardScaler can be influenced by outliers (if they exist in the dataset) since it involves the estimation of the empirical mean and standard deviation of each feature. In Machine Learning, StandardScaler is used to resize the distribution of values so that the mean of the observed values is 0 and the standard deviation is 1
K N N : The k-nearest neighbors (
) algorithm is a simple, easy-to-implement supervised machine learning algorithm that can be used to solve both classification and regression problems. The 
 algorithm can compete with the most accurate models because it makes highly accurate predictions. Therefore, you can use the 
 algorithm for applications that require high accuracy but that do not require a human-readable model. The quality of the predictions depends on the distance measure.
 
 
 R F E : Recursive Feature Elimination, or 
 for short, is a popular feature selection algorithm. 
 is popular because it is easy to configure and use and because it is effective at selecting those features (columns) in a training dataset that are more or most relevant in predicting the target variable.
 
 After training the model we then apply the evaluation measures to check how the model is performing. Accordingly, we use the following evaluation parameters to check the performance of the models respectively :
Accuracy Score : Typically, the accuracy of a predictive model is good (above 90% accuracy)
Execution time : Variable that depends on the machine on which the program was executed, but which can give a small idea of the model that executes the fastest.
F1 score : The F1 score
 is a weighted harmonic mean of precision and recall such that the best score is 1.0 and the worst is 0.0. F1 scores are lower than accuracy measures as they embed precision and recall into their computation.
ROC-AUC Curve : The Area Under the Curve (
) is the measure of the ability of a classifier to distinguish between classes and is used as a summary of the 
 curve. The higher the 
, the better the performance of the model at distinguishing between the positive and negative classes.
Confusion Matrix with Plot : A Confusion matrix is an 
 x 
 matrix used for evaluating the performance of a classification model, where 
 is the number of target classes. The matrix compares the actual target values with those predicted by the machine learning model. Note that :
