# Cohort-Analysis

##Table of Contents 
-[Proiect overview](#proiect-overview) 
-[Proiect_Objective](#project-obiective).
-[Data_Soursesl](#data-sourses).
-[Data Preprocessing](#data-preprocessing), 
-[Machine Learning_Model](#machine-learning-model). 
-[Evalvation Metrics](#evaluation-metrics). 
-[Key Insiehts1](#Key-insigh8) 
-[Conclusion](#conclusion).


Project Overview
This project uses cohort analysis and customer segmentation to understand customer behavior over time. The goal is to analyze retention patterns, identify churn, and uncover insights that can improve customer engagement and business performance.

Project Objectives

- **Analyse customer purchasing behaviour** to understand transaction patterns and changes in purchasing activity over time.
- **Measure customer retention** by grouping customers into monthly cohorts based on their first purchase and tracking their subsequent purchasing activity.
- **Examine customer disengagement patterns** by identifying changes in repeat purchasing and retention across cohorts.
- **Segment customers based on purchasing behaviour** using features such as recency, frequency, monetary value, product variety and average order value, applying K-means clustering.
- **Generate actionable business insights** to inform customer retention strategies, targeted marketing and opportunities to improve customer lifetime value and revenue.

Data Sources
The dataset contains transactional data including customer purchases, product categories, quantity, price, and invoice dates. This data is used to track customer activity and build cohorts.


## Data Preprocessing

- **Data cleaning:** Checked data quality and prepared the dataset for analysis, addressing relevant missing values and inconsistencies.
- **Date conversion:** Converted `InvoiceDate` to datetime format to support time-based analysis.
- **Revenue calculation:** Created a `Sales` feature by multiplying `Quantity` by `UnitPrice` for customer monetary value analysis.
- **Time-based features:** Extracted monthly and yearly transaction periods to analyse purchasing trends over time.
- **Cohort analysis:** Created `CohortMonth` and `CohortIndex` to group customers by their first purchase month and measure  retention across subsequent months.
- **Customer segmentation:** Engineered customer-level features, including recency, frequency, monetary value, product variety and average order value, for K-means clustering.
- **Data preparation:** Reviewed relevant product descriptions and transaction records to ensure they were suitable for the   planned analysis.

Machine Learning Model
Customer segmentation was performed using RFM (Recency, Frequency, Monetary) analysis combined with K-Means clustering.
This approach groups customers based on their purchasing behavior into segments such as:
•	Champions 
•	Loyal customers 
•	At-risk customers 

Evaluation Metrics
•	Retention rate across cohorts 
•	Customer frequency and spending patterns 
•	Cluster distribution and behavior differences 

Key Insights
•	Revenue shows steady growth, especially in later months 
•	Customer retention drops significantly after the first purchase 
•	Most customers fall into low to medium engagement segments 
•	A small group of high-value customers (Champions) drives most revenue 
•	Customer behavior varies across different cohorts 

Conclusion
The business demonstrates strong growth but faces challenges with early customer retention. Improving first-month engagement and targeting at-risk customers can significantly increase long-term customer value and overall performance.
