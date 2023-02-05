# Loan default prediction
### Key finding: 1) Borrowers who are small business owners, do not meet the credit policy of lenders, have a higher interest rate, and have low fico are associated with high default risk. 2) The Logistic Regression model performs best in predicting loan default.
## Business problem
Online lending platforms have experienced a rapid development in recent years thanks to their convienience and feasibility. However, they are facing various difficulties related to loan default, given their clients are individual or small business owners, and borrowers with low income who had been rejected by traditional banks.
## Aims of the project
1. Identify factors associated with repayment failures beased on financial information provided by customers.
2. Training a Machine Learning model that is capable of  predicting defaulters and non-defaulters based on clients’ financial information, in order to provide suitable support for loan approval decision making.
## Data source: 
  https://www.kaggle.com/datasets/itssuru/loan-data
## Research Design
![Picture 1](https://user-images.githubusercontent.com/76152416/216819237-f17af206-40ad-4c72-8b96-dfd17be255ad.png)
## Quick glance at the result!

### The results of data analysis showed that borrowers who do not meet the credit policy of lenders, have a higher interest rate, and low fico are associated with a high default risk. The high risk is also observed in customers with the purpose of borrowing listed as “small business”. 
###Proves are shown in figures and table below:

 	 
  ![image](https://user-images.githubusercontent.com/76152416/216822264-faf4cf9f-a184-4e43-b14a-c0e3381a2a56.png) 

Counts of clients according to credit criteria (left) and percentage of fully paid/not fully paid clients in each type of credit policy (right).


  ![image](https://user-images.githubusercontent.com/76152416/216821393-260b819d-e11a-41d0-8485-b997b453d850.png)

Scatterplot of interest rate and fico, grouped by loan paid.


  ![image](https://user-images.githubusercontent.com/76152416/216821608-cbabb110-fcd2-496c-8f59-1db3132c7d9e.png) 

28.59% customers who do not meet credit policy with interest rate greater than 0.1 and fico lesser 737 wouldn't pay for their loan.


  ![image](https://user-images.githubusercontent.com/76152416/216821858-467e77b0-c63f-4ecc-8669-d320207529e7.png)
Percentage of not_fully_paid/ fully_paid by purpose of borrowing!


### All classification models were successfully built with satisfactory performance, with XGBoost and Random Forest accuracy exceeding 80%. 

  ![image](https://user-images.githubusercontent.com/76152416/216821955-6f2beb84-6236-4fc8-b6d1-4b34f2a8daa0.png)


### Logistic Regression performed best on prediction loan defaulters - 83%  of the defaulted loan was correctly identified when decision threshold is set to 0.4.
