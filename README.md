# ![alt text](image.png)
# Reducing Customer Churn in Retail with Personalized Incentives

### Big Data (CSGY-6513-C) | Fall 2024
##### Team Members: 
* Abhishek Agrawal aa9360 
* Shubham Naik svn9724 
* Vaibhav Rouduri vr2470


# Exploratory Data Analysis
The dataset consist of 4 tables in separate .csv files. It covers a two year span purchase transactions of 2500 households. In addition demorgraphics information of households, products and coupon codes per product based on business policies are available. Features are engineered to capture the customer behavior and predict churn. 

Below are the features used in the model:
* Frequency: Number of transactions over a defined period (e.g., past 30/60/90 days).
* Monetary Value: Total spending over a defined period.
* Average Basket Size: Average number of items per basket.
* Discount Utilization: Average discount per transaction.
* Discount Count: Number of discounts per transaction.

Churn Defination: Using the recency of the last purchase, churn probability is calculated. A customer is `predicted to be churned` if their churn probability is `greater than 0.5`.


Dataset:
* Transactions (transaction_data.csv) - Contains purchase transactions of households.
* Demographics (hh_demographic.csv) - Contains demographic information of households.
* Products (product.csv) - Contains product details.
* Coupon (coupon.csv) - Contains coupon information.