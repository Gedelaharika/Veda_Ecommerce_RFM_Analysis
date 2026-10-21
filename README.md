# E-Commerce Customer Segmentation using RFM Analysis

## 1. Project Overview
This project segments e-commerce customers using Recency, Frequency, and Monetary (RFM) analysis. The objective is to identify valuable customers, loyal buyers, recently acquired customers, and customers who may need re-engagement campaigns.

## 2. Dataset
- **Dataset:** UCI Online Retail Dataset
- **Source:** https://archive.ics.uci.edu/dataset/352/online+retail
- **Original records:** 541,909 transactions
- **Customers analyzed:** 4,338 after data cleaning

## 3. Tools Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Jupyter Notebook
- GitHub

## 4. Methodology
1. Loaded the transaction dataset and examined missing values and duplicates.
2. Removed duplicate records, transactions with missing customer IDs or descriptions, cancelled invoices, and invalid quantities or prices.
3. Calculated transaction revenue as Quantity × UnitPrice.
4. Calculated Recency, Frequency, and Monetary metrics for each customer.
5. Assigned RFM scores from 1 to 5.
6. Segmented customers into Champions, Loyal Customers, Recent Customers, At Risk, and Needs Attention.
7. Visualized customer counts and revenue contribution by segment.

## 5. Key Findings
- **Champions:** 942 customers, contributing approximately 64.6% of revenue.
- **Loyal Customers:** 1,000 customers, contributing approximately 16.9% of revenue.
- **At Risk:** 661 customers, representing an opportunity for win-back campaigns.
- **Needs Attention:** 1,425 customers, the largest segment by customer count.
- **Recent Customers:** 310 customers, who may benefit from onboarding and second-purchase offers.

## 6. Business Recommendations
- Reward Champions with loyalty benefits and exclusive offers.
- Encourage Loyal Customers to increase purchase frequency.
- Test win-back campaigns for At Risk customers.
- Use personalized offers to re-engage Needs Attention customers.
- Encourage Recent Customers to make a second purchase.

## 7. Deliverables
- Jupyter Notebook containing data cleaning, RFM calculations, segmentation, and charts.
- CSV file containing customer-level RFM scores and segments.
- CSV file summarizing customer segments.
- One-page business recommendation.

## 8. Limitations
RFM scores are based on historical transactions and do not guarantee future customer behavior. Campaign effectiveness should be measured through follow-up results.

