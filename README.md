# Credit-Card-Segmentation
Objective
There are a lot of features in this dataset (18 behavioral features). We will now perform:

Data preprocessing
Clustering
Feature extraction to improve clustering
Experiment with various clustering models: KMeans, Agglomerative Hierarchical, Gaussian Mixture
Choosing the number of clusters
EDA to segment the customers
Concluding the project by giving marketing strategy based on what we learn from the data
Data Description
Link to the dataset: Kaggle link

Following is the Data Dictionary for Credit Card dataset:

CUST_ID: Identification of Credit Card holder (Categorical)
BALANCE: Balance amount left in their account to make purchases
BALANCE_FREQUENCY: How frequently the Balance is updated, score between 0 and 1 (1 = frequently updated, 0 = not frequently updated)
PURCHASES: Amount of purchases made from account
ONEOFF_PURCHASES: Maximum purchase amount done in one-go
INSTALLMENTS_PURCHASES: Amount of purchase done in installment
CASH_ADVANCE: Cash in advance given by the user
PURCHASES_FREQUENCY: How frequently the Purchases are being made, score between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased)
ONEOFFPURCHASESFREQUENCY: How frequently Purchases are happening in one-go (1 = frequently purchased, 0 = not frequently purchased)
PURCHASESINSTALLMENTSFREQUENCY: How frequently purchases in installments are being done (1 = frequently done, 0 = not frequently done)
CASHADVANCEFREQUENCY: How frequently the cash in advance being paid
CASHADVANCETRX: Number of Transactions made with "Cash in Advanced"
PURCHASES_TRX: Number of purchase transactions made
CREDIT_LIMIT: Limit of Credit Card for user
PAYMENTS: Amount of Payment done by user
MINIMUM_PAYMENTS: Minimum amount of payments made by user
PRCFULLPAYMENT: Percent of full payment paid by user
TENURE: Tenure of credit card service for user
