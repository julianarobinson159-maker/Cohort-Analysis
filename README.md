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
•	Analyze customer behavior using cohort analysis 
•	Measure customer retention over time 
•	Identify when customers stop engaging (churn) 
•	Segment customers based on purchasing behavior 
•	Provide insights to improve retention and revenue 

Data Sources
The dataset contains transactional data including customer purchases, product categories, quantity, price, and invoice dates. This data is used to track customer activity and build cohorts.

Data Preprocessing
•	Cleaned missing and inconsistent data 
•	Converted date columns to datetime format 
•	Created new features such as Revenue (Quantity × Price) 
•	Extracted Month and Year from transaction dates 
•	Built Cohort Month and Cohort Index for retention analysis 
•	Filtered and cleaned product category data 

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
