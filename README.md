#Telecom Customer Churn Prediction Project
This analysis focuses on the behavior of telecom customers who are more likely to leave the platform. 
We intend to find out the most striking behavior of customers through EDA and later on use some of the predictive analytics techniques to determine the customers who are most likely to churn.
The data set includes information about:
•	Customers who left within the last month – the column is called Churn
•	Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
•	Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
•	Demographic info about customers – gender, age range, and if they have partners and dependents       


#Data source
Kaggle datasets repository

#Data Description
The data contains 7043 rows (customers) and 21 columns (features)
Each variable is described as follows:
    Type    /	  Variable        /	 Description
1	 Factors	/ customerID        / Customer ID 
2	 Factors	/ gender	          / Customer gender (female, male)
3	 Integer	/ SeniorCitizen	    / Whether the customer is a senior citizen or not (1, 0)
4	 Factors	/ Partner	          / Whether the customer has a partner or not (Yes,No)
5	 Factors	/ Dependents	      / Whether the customer has dependents or not (Yes,No)
6	 Integer	/ tenure	          / Number of months the customer has stayed with the company
7	 Factors	/ PhoneService	    / Whether the customer has a phone service or not (Yes, No)
8	 Factors	/ MultipleLines	    / Whether the customer has multiple lines or not (Yes, No, No phone service)
9	 Factors	/ InternetService	  / Customer’s internet service provider (DSL, Fiber optic, No)
10 Factors	/ OnlineSecurity	  / Whether the customer has online security or not (Yes, No, No internet service)
11 Factors	/ OnlineBackup 	    / Whether the customer has online backup or not (Yes, No, No internet service)
12 Factors	/ DeviceProtection	/ Whether the customer has device protection or not (Yes, No, No internet service)
13 Factors	/ TechSupport	      / Whether the customer has tech support or not (Yes, No, No internet service)
14 Factors	/ StreamingTV	      / Whether the customer has streaming TV or not (Yes, No, No internet service) 
15 Factors	/ StreamingMovies	  / Whether the customer has streaming movies or not (Yes, No, No internet service)
16 Factors	/ Contract	        / The contract term of the customer (Month-to-month, One year, Two year)
17 Factors	/ PaperlessBilling	/ Whether the customer has paperless billing or not (Yes, No)
18 Factors	/ PaymentMethod     / The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))
19 Numeric	/ MonthlyCharges	  / The amount charged to the customer monthly
20 Numeric	/ TotalCharges	    / The total amount charged to the customer
21 Factors	/ Churn 	          / Whether the customer churned or not (Yes or No)


