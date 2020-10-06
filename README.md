# Data_Analysis_of_Online_Retail_datasets
Online Retails datasets of size over 1 Million records are joined, analyzed with the help of Pandas (performing all SQL operations) and the resultant dataset was grouped by Stock Description ordered with respect to frequency. Items are classified based on frequency of the words occured in combined dataset, Text classification has been done based on Term frequency using Python. Later items are categorized and most frequent categories were displayed.


This project highlights data manipulation using Pandas.


## Datasets choosen: 
Online Retail Datasets were picked from UCI Machine Learning Repository'https://archive.ics.uci.edu/ml/datasets/Online+Retail+II' 
This Dataset has Multivariate, Sequential, Time-Series, Text characteristics. 
Number of instances: 1067371
Area: Business
Attribute characteristics; Integer, Real
Number of Attributes: 8
Associated tasks: Classification, Regression, Clustering

Dataset Information: This Online Retail II data set contains all the transactions occurring for a UK-based and registered, non-store online retail between 01/12/2009 and 09/12/2011.The company mainly sells unique all-occasion gift-ware. Many customers of the company are wholesalers.


## Attribute Information:

InvoiceNo: Invoice number. Nominal. A 6-digit integral number uniquely assigned to each transaction. If this code starts with the letter 'c', it indicates a cancellation.
StockCode: Product (item) code. Nominal. A 5-digit integral number uniquely assigned to each distinct product.
Description: Product (item) name. Nominal.
Quantity: The quantities of each product (item) per transaction. Numeric.
InvoiceDate: Invice date and time. Numeric. The day and time when a transaction was generated.
UnitPrice: Unit price. Numeric. Product price per unit in sterling (Â£).
CustomerID: Customer number. Nominal. A 5-digit integral number uniquely assigned to each customer.
Country: Country name. Nominal. The name of the country where a customer resides.


## Instructions:
The above link will leads us to https://archive.ics.uci.edu/ml/machine-learning-databases/00502/, and there is an excel file named “online_retail_II.xlsx” for the data. It has two sheets with each one having a dataset.


Programming language used for coding was 'Python'. 
Data Manipulations such as joining, combining, deletion, addition operations on table/datasets were done using 'Pandas'.
Data Visualizations were done using 'Matplotlib'.


## Tasks for the Assignment:

A1. Append the data sets together from the two the sheets. You should have ~1 million records.
A2. Create a “profile” of the data set (A1). That is, generate some stats like min, max, mean, missing counts, number of unique values etc.
A3. Create a StockCode, Invoice Year, Invoice Month level data set. That is, one row will represent unique StockCode, Invoice Year, Invoice Month combination. E.g. If a StockCode had invoices for 3 months for a particular year and 4 months for another year, then there should be only 7 records for that StockCode in the summarized data set.
A4. When creating the above dataset (in A3), the other attributes need to be summarized. In addition to the summarized columns you create, below columns needs to be created (for the StockCode-InvoiceYear- InvoiceMonth combination).
a. Number of unique customers
b. Number of unique prices
c. Customer ID who purchased the highest quantity. If there are multiple customers qualified, choose the minimum Customer ID.
d. Number of price changes
e. Weighted average of the price (using quantity)
f. Amount (quantity*price) below weighted average price (which calculated in e)
g. Amount (quantity*price) above weighted average price (which calculated in e)
A5. Give 5 insights which are interesting to you from the above dataset (A4).
A6. Referring to the main dataset in A1, create below grouping using the description column. Output should be a dataset with unique group column and corresponding description column and the corresponding StockCode.
a. Group based on the core item. For example, below items are all pencils.
b. Group this column based on some other criteria you think which will be useful when thinking about summarizing data across the grouping.

