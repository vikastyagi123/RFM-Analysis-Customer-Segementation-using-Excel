# RFM-Analysis-Customer-Segementation-using-Excel

##  Customer Segmentation using RFM Analysis
This repository contains data and analysis related to customer segmentation using the RFM (Recency, Frequency, Monetary) framework. The RFM analysis is a powerful technique in marketing and customer relationship management that helps classify customers based on their purchasing behavior. This README provides an overview of the contents and structure of the repository.

Table of Contents
Overview
Data
Analysis
Results
Usage
Contributing
License
Overview
In this project, we conducted customer segmentation using the RFM framework. RFM analysis involves the following components:

Recency (R): How recently a customer made a purchase.
Frequency (F): How often a customer makes purchases.
Monetary (M): How much money a customer spends.
By analyzing these three aspects, we can categorize customers into different segments, which helps in tailoring marketing strategies, customer engagement, and overall business decisions.

Data
The data used for this analysis includes the following sheets:

Sheet 1: Customer Segmentation

Columns: CustomerID, SalesOrderNumber, SalesAmount, OrderDate
Sheet 2: RFM Metrics

Columns: CustomerID, MostRecentOrderDate, DaysSinceLastOrder, SalesOrderCount, TotalSalesAmount, Recency, Frequency, Monetary
Sheet 3: ZCTA Data

Columns: ZCTA, Households100to149K, Households150to199K, Households200KorMore, RFM1, RFM2, RFM3
Analysis
We performed the following steps for customer segmentation:

Extracted and prepared the raw sales data to calculate RFM metrics for each customer.
Calculated Recency, Frequency, and Monetary values based on customer purchasing behavior.
Classified customers into segments based on RFM values, using techniques such as clustering or predefined thresholds.
Results
The analysis led to the identification of distinct customer segments based on their purchasing behavior. These segments can be used to tailor marketing campaigns and business strategies to better serve the needs of each customer group.

Usage
To reproduce or build upon this analysis:

Use the provided data or replace it with your own dataset.
Refer to the analysis scripts and notebooks for the steps performed in the analysis.
Customize the segmentation approach or visualization methods as needed.
Contributing
Contributions are welcome! If you find any issues or have improvements to suggest, please open an issue or create a pull request.

