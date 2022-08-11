# Loan Eligibility Prediction using Machine Learning


# Aim: 

To predict whether a person is eligible to get loan or not based on the certain features using Machine Learning.


# Objectives:

To analyze the features like applicant income, credit history, property area and so on which will affect whether a person is eligible for getting loan by applying the machine learning techinques like Decision Tree and Logistic Regression Algorithms.


# Methodology:

**Data collection**: The dataset train.csv was collected from Kaggle.com which consists of 614 rows and 13 features out of which the last column is the target variable(loan_status) having the values yes(Y) or no(N) where Y indicates that a person is eligible for loan which is a classification problem.

**Data cleaning**: The dataset consists of many null values which will affect the accuracy of the model during prediction. So, the null values are replaced by mean and mode depending on the features, if it is categorical feature then it is replaced by mode and if it is numeric then it is replaced by mean. Further the features are standardized and label encoding is applied on categorical columns.

**Exploratory Data Analysis**: After the Data cleaning step we will visualize the data that how features are related to each other, datatype of each feature, descriptive statistics to select the best feature for the further process. 

**Model Creation**: This is the step where we apply the Machine Learning Algorithms, Decision Tree Classifier and Logistic Regression Algorithms are used to create a model. 

**Evaluation**: In this step, the accuracy of the developed model is evaluated and also the confusion matrix is obtained which tells us that which algorithm performed well in terms of accuracy.


# Tools and Technologies:

Python3

Machine Learning

Jupyter notebook

Python libraries(numpy,pandas,seaborn,matplotlib)


# Conclusion:

**The interesting inferences from the dataset are listed below**:

1. In the dataset 68.73% are eligible for loan while 31.27% are not eligible.
2. With the help of Heat map it is obtained that CreditHistory is highly correlated to Loan_Status.
3. The ratio of male and female in the dataset is 8:2.
4. People who are belonging to semi-urban region are more eligible for getting loan.
5. More number of people who are graduated and who are not self_employed have applied for loan.
6. The distribution of Applicant Income is between 0 to 10000.
7. The better accuracy has been obtained from Logistic Regression of about 82.7% and for Decision Tree it is 82.1% accuracy.
8. F1_score obtained for Logistic Regression is 0.89 whereas for Decision Tree it is 0.88.

