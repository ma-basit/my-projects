PowerBI Dashboard 
![image](https://github.com/user-attachments/assets/376d29a7-41e6-48bc-919b-052d30251986)


# Customer Segmentation and Behaviour Analysis                                

## Project Overview                                                        
This project focuses on analyzing customer purchasing behavior and segmenting customers based on transactional data. Key objectives include identifying trends by time, week, and month, as well as creating actionable customer segments for business intelligence insights.

## Dataset
The dataset consists of:

Columns: InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country
Preprocessing: Rows with missing Description values were removed, as they provide little value for product-based analysis.

## Steps Performed
### 1. Data Preprocessing
Extracted Hour, Weekday, and Month columns from InvoiceDate for temporal analysis.
Filtered and cleaned the dataset to ensure quality.

### 2. Feature Engineering
Created the Segment column based on RFM (Recency, Frequency, Monetary) analysis:
Best Customers
Loyal Customers
At Risk
Churned Customers
Big Spenders
Other

### 3. Visualizations and Analysis
#### a. Customer Segment Distribution

Insight:
Loyal Customers dominate the customer base.
At Risk customers are significant, indicating the need for re-engagement strategies.
Best Customers and Big Spenders form a small but valuable group.

#### b. Shopping Trends by Hour

Insight:
Peak shopping hours occur between 11 AM to 3 PM, with a sharp drop after 4 PM.
Business strategies can focus on these peak hours to optimize marketing campaigns.

#### c. Shopping Trends by Month

Insight:
November records the highest number of transactions, likely due to seasonal sales.
September and October show rising trends, suggesting early holiday shopping behavior.

#### d. Monthly Distribution by Customer Segment

Insight:
Loyal Customers are consistently the largest segment across months.
November sees a spike across all segments, especially At Risk and Loyal Customers, aligning with peak shopping trends.

#### e. Shopping Trends by Weekday

Insight:
Thursday has the highest number of transactions.
Saturday shows the least activity, possibly indicating a shift toward weekdays for shopping.

#### f. Weekly Distribution by Customer Segment

Insight:
At Risk and Loyal Customers dominate the weekly distribution.
Transaction activity is consistent from Monday to Thursday, with a drop on weekends.

### Key Insights
Temporal Analysis:

Peak shopping hours: 11 AM - 3 PM.
November sees the highest sales activity.
Thursdays are the busiest days for transactions.

#### Customer Segmentation:

Loyal Customers form the largest group, indicating strong retention.
At Risk customers need targeted re-engagement strategies to prevent churn.
Best Customers and Big Spenders contribute significant revenue despite smaller numbers.
Monthly and Weekly Trends:

November sales spikes align with seasonal promotions.
Customer activity drops significantly on Saturdays.

## Conclusion
This project demonstrates the use of data analysis and visualization for customer segmentation and behavior insights. Key findings around peak hours, weekdays, and monthly trends can help businesses tailor their strategies for customer retention and revenue growth.

#### Tools and Skills Used
Python: Data cleaning, feature engineering, and analysis
Libraries: Pandas, Matplotlib, Seaborn
RFM Analysis: Customer segmentation
Visualizations: Charts for time-based and segment analysis

