# HEALTH-INSURANCE-CROSS-SELL-PREDICTION
Predict Health Insurance Owners' who will be interested in Vehicle Insurance
![image](https://user-images.githubusercontent.com/90926349/183107575-87b673d5-969b-4971-803c-d17e2d563705.png)


# Problem Statement
Your client is an Insurance company that has provided Health Insurance to its customers now they need your help in building a model to predict whether the customers from past year will also be interested in Vehicle Insurance provided by the company.

# Business Goal
Building a model to predict whether a customer would be interested in Vehicle Insurance is extremely helpful for the company because it can then accordingly plan its communication strategy to reach out to those customers and optimise its business model and revenue.

# Data Description
Data Source : Kaggle

Data Source Link : https://www.kaggle.com/anmolkumar/health-insurance-cross-sell-prediction?select=train.csv

The Dataset used for the analysis includes the following columns:

* id : Unique ID for the customer

* Gender : Gender of the customer

* Age : Age of the customer

* Driving_License : 0 - Customer does not have DL,1 - Customer already has DL

* Region_Code : Unique code for the region of the customer

* Previously_Insured : 1 - Customer already has Vehicle Insurance, 0-Customer doesn't have Vehicle Insurance

* Vehicle_Age : Age of the Vehicle Vehicle_Damage : 1 - Customer got his/her vehicle damaged in the past. 0 -Customer didn't get his/her vehicle damaged in the past.

* Annual_Premium : The amount customer needs to pay as premium in the year

* PolicySalesChannel : Anonymized Code for the channel of outreaching to the customer ie. Different Agents, Over Mail, Over Phone, In Person, etc.

* Vintage : Number of Days, Customer has been associated with the company

* Response : 1 - Customer is interested, 0 - Customer is not interested

# Model Performance
![image](https://user-images.githubusercontent.com/90926349/183013634-22e00fad-1a30-4f37-9ad7-7400028ee2ba.png)![image](https://user-images.githubusercontent.com/90926349/183013664-e7ce96c9-35e9-4b83-ba78-3c653d27cb54.png)
![image](https://user-images.githubusercontent.com/90926349/183013707-e2122013-6818-46e4-b929-5ef852a261fc.png)




# Comparing The Model

![image](https://user-images.githubusercontent.com/90926349/183013345-c8e92815-e515-42f1-bc36-e9abf847c5fb.png)

For this problem we have create 3 models i.e. Logistic Regression, Random Forest and XGB classifier.

The ML model for the problem statement was created using python with the help of the dataset, and the ML model created with Random Forest and XGBClassifier models performed better than Logistics Regression model.

Comparing ROC curve we can see that Random Forest model preform better. Because curves closer to the top-left corner, it indicate a better performance.



# Conclusion

1.Customers of age between 30 to 60 are more likely to buy insurance.

2.Customers with Driving License have higher chance of buying Insurance.

3.Customers with Vehicle_Damage are likely to buy insurance.

4.The variable such as Age, Previously_insured, Annual_premium are more afecting the target variable.

5.Comparing ROC curve we can see that Random Forest model preform better. Because curves closer to the top-left corner, it indicate a better performance.

