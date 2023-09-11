# What is Churn Scoring ?
[![](https://img.shields.io/badge/-Classification-orange)](#) [![](https://img.shields.io/badge/-Python-green)](#) [![](https://img.shields.io/badge/-Google--Colab-green)](#) 
* Churn scoring, also known as customer churn prediction, is a data analytics process used by businesses to identify and predict which customers are likely to stop using their products or services in the near future. The goal of churn scoring is to proactively target these at-risk customers with retention strategies to prevent them from leaving the company.
# Use Case: E-Commerce
## Churn Prediction steps:
### 1. Import Dataset
#### Dataset includes 20 variables below:
* CustomerID            : Unique customer ID
* Churn	                : Churn Flag
* Tenure	              : Tenure of customer in organization
* PreferredLoginDevice	: Preferred login device of customer
* CityTier	            : City tier
* WarehouseToHome	      : Distance in between warehouse to home of customer
* PreferredPaymentMode	: Preferred payment method of customer
* Gender	              : Gender of customer
* HourSpendOnApp	      : Number of hours spend on mobile application or website
* NumberOfDeviceRegistered	: Total number of deceives is registered on particular customer
* PreferedOrderCat	    : Preferred order category of customer in last month
* SatisfactionScore	    : Satisfactory score of customer on service
* MaritalStatus	        : Marital status of customer
* NumberOfAddress	      : Total number of added added on particular customer
* Complain	            : Any complaint has been raised in last month
* OrderAmountHikeFromlastYear	: Percentage increases in order from last year
* CouponUsed	          : Total number of coupon has been used in last month
* OrderCount	          : Total number of orders has been places in last month
* DaySinceLastOrder	    : Day Since last order by customer
* CashbackAmount	      : Average cashback in last month
#### *Number of transactions: 5,630 entries
### 2. EDA
#### Data Info
![EDA1](https://github.com/ChampAnuwat/MADT-8101-Seminar-in-Customer-Analytics/blob/main/4.%20Churn%20Scoring/EDA_Info.png?raw=true)
#### Correlation
![EDA2](https://github.com/ChampAnuwat/MADT-8101-Seminar-in-Customer-Analytics/blob/main/4.%20Churn%20Scoring/EDA_Correlation.png?raw=true)
### 3. Model Creation and Evaluation
* Models include LogisticRegression, KKNeighbors, XGBoost, and RandomForest
* Rebalancing technique: SMOTE, Nosampling, Undersampling, and Oversampling
* Model Evalution: Ranked by F1 Score

![Rank](https://github.com/ChampAnuwat/MADT-8101-Seminar-in-Customer-Analytics/blob/main/4.%20Churn%20Scoring/Model_Ranking.png?raw=true)






