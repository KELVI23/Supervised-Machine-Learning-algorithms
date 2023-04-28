# Predict-Customer-Churn

## About the project
The churn of customers is a concern for every company, this project aims to predict which demographic of customers of a telecommunication company are likely to leave and why.Typically it is less expensive to keep customers than acquire new ones, so the focus of this analysis is to predict the customers who will stay with the company. 

### About the dataset 

This is a historical customer dataset where each row represents one customer.

The dataset includes information about:

Customers who left within the last month – the column is called Churn
Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
Customer account information – how long they had been a customer, contract, payment method, paperless billing, monthly charges, and total charges
Demographic info about customers – gender, age range, and if they have partners and dependents

#### Process
1. Dataset preprocessing
2. Remove some features from dataframe

|tenure|age| address| income| ed| employ| equip| callcard| wireless| longmon| ...| pager| internet| callwait| confer| ebill| loglong| logtoll| lninc| custcat| churn
|--- |--- |
|tenure|age| address| income| ed| employ| equip| callcard| wireless| churn|

3. Turn Churn categorical value into intergers
4. Normalize the dataset
5. Train/Test dataset
6. Evaluate the model

 
 
 
 ## Evaluation
 
 ### Confusion matrix
<p align="left">
  <img src="https://imgur.com/1O798EY.png" alt="Confusion matrix" />
</p>
Churn=1 Out of 15 churning customers the classifier correctly predicted 6 of them as likely to churn and 9 incorrectly as false positives. While 9 of the customers had a churn value of 1 it predicted the churn value as 0.

Churn=0 Out of the 25 customers who were predicted as unlikely to churn 24 were correctly prediected and 1 was a False negative.

### Precision & recall of each label
<p align="right">
  <img src="https://imgur.com/ZY6rc7j.png" alt="Number of cylinders vs Co2 Emmissions" />
</p>

Precision is a measure of the accuracy provided that a class label has been predicted. It is defined by: precision = TP / (TP + FP)

Recall is the true positive rate. It is defined as: Recall =  TP / (TP + FN). 

_The balance between precision and recall makes for higher F1 score_
