## Project Description: 
Customer churn prediction is to measure why customers are leaving a business.we will be looking at customer churn in telecom business. We will build a Machine learning model to predict the churn and use precision,recall, f1-score to measure performance of our model
## Database Description:

Number of Instances: 7043

Number of Attributes: 20 including the Churn Class

## Attribute Information:
Target column :- Churn Class
Feature Columns:- Customer Id:-unique customer id, gender:- (Male,Female), SeniorCitizen:- (0,1), Partner:- (Yes,No), Dependents:-(Yes,No), tenur:- Period, PhoneService:- (Yes,No),
MultipleLines, InternetService, OnlineSecurity, DeviceProtection, TechSupport, StreamingTV, StreamingMovies, Contract, PaperlessBilling, PaymentMethod, MonthlyCharges, TotalCharges 	, Churn

## Libraries Involved:
1. pandas
2. Numpy
3. Seaborn
4. Matplotlib
5. Sklearn

## Steps Involved:
1. Importing the libraries
2. Loading the dataset
3. Data Preprocessing
4. train and test data split
5. Building the model
6. Compare model performance
7. selection model based on performance
8. Evaluation 
9. Plot ROC and AUC curve

## Machine Learning Steps Involved
1. Multiple Algorithm used 
   * LogisticRegression
   * DecisionTreeClassifier
   * KNeighborsClassifier
   * RandomForestClassifier
   * AdaBoostClassifier
   * XGBClassifier
2. Find best Algorithm is Logistic Regression


