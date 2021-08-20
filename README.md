# Telco-Customer-Churn-Prediction

# Problem Definition
Based on the introduction the key challenge is to predict if an individual customer will churn or not. To accomplish that, machine learning models are trained based on 80% of the sample data. The remaining 20% are used to apply the trained models and assess their predictive power with regards to “churn / not churn”. A side question will be, which features actually drive customer churn. That information can be used to identify customer “pain points” and resolve them by providing goodies to make customers stay.

To compare models and select the best for this task, the accuracy is measured. Based on other characteristics of the data, for example the balance between classes (number of “churners” vs. “non-churners” in data set) further metrics are considered if needed.

# Description of the features

Classification labels
* Churn — Whether the customer churned or not (Yes or No)

Customer services booked
* PhoneService — Whether the customer has a phone service (Yes, No)
* MultipleLines — Whether the customer has multiple lines (Yes, No, No phone service)
* InternetService — Customer’s internet service provider (DSL, Fiber optic, No)
* OnlineSecurity — Whether the customer has online security (Yes, No, No internet service)
* OnlineBackup — Whether the customer has online backup (Yes, No, No internet service)
* DeviceProtection — Whether the customer has device protection (Yes, No, No internet service)
* TechSupport — Whether the customer has tech support (Yes, No, No internet service)
* StreamingTV — Whether the customer has streaming TV (Yes, No, No internet service)
* StreamingMovies — Whether the customer has streaming movies (Yes, No, No internet service)

Customer account information
* Tenure — Number of months the customer has stayed with the company
* Contract — The contract term of the customer (Month-to-month, One year, Two year)
* PaperlessBilling — Whether the customer has paperless billing (Yes, No)
* PaymentMethod — The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))
* MonthlyCharges — The amount charged to the customer monthly
* TotalCharges — The total amount charged to the customer

Customers demographic info
* customerID — Customer ID
* Gender — Whether the customer is a male or a female
* SeniorCitizen — Whether the customer is a senior citizen or not (1, 0)
* Partner — Whether the customer has a partner or not (Yes, No)
* Dependents — Whether the customer has dependents or not (Yes, No)

# Methodology

Use of multiple Machine Supervised learning alogirthms along with Gridsearch cross validation to get best hyper parameters to predict the Churn of the customers:
1. Logistic Regression
2. KNN
3. SVM
4. Decision Tree
5. Random Forest
6. Adaptive Boosting
7. Gradient Boosting
