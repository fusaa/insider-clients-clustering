# Insiders VIP Clients

# Situation  
This project refers to an online retailer/wholesaler that sells through an e-commerce platform. The aim is to create a VIP club for important customers with access to extra perks. Customers will be selected according to the frequency and amount they buy. This program will be called “Insiders”. Using advanced data manipulation techniques, customers will be grouped(clustered) according to similarities.

# Problem
Segment customers according to shared characteristics to identify a group relevant in revenue for marketing actions.

**Solution Planning (IOT)**

**Input**  

    - Business Problem: Select the most valuable customers to join a loyalty program.  
    - Dataset: E-commerce online sales.  
**Output**  

    1.List of customers who will join the Insiders program.  
    2.Who are the people eligible to join the Insiders program?  
    3.How many customers will be part of the group?  
    4.What are characteristics of these customers?  
    5.What is the percentage of revenue contribution coming from the Insiders?  
    6.What is the expected revenue of this group for the next months?  
**Tasks**  

1. Segment customers eligible to join the Insiders program.  
    •	What are the most valuable customers?  
    •	Revenue, RFM Model, average spending, churn
    •   Cost: Items return rate
2. How many customers will be part of the group?  
•   Total number of customers vs % of Insiders Group  
3. What are the main characteristics of these customers?  
•	Clustering attributes  
4. What is the percentage of revenue contribution coming from the Insiders?  
•	Anual total revenue  
•	Insiders' revenue  
5. What is the expected revenue of this group for the next months?  
•	Insiders' LTV •	Cohort Analysis •	Timeseries (ARIMA, ARMA, Prophet)
6. What actions can the marketing team take to increase revenue?  
•	Discount  
•	Shipping  
•	Company visit  
•	Perks  

**Benchmark guide: RFM Model:**

![RFM Model](./rfm.png)

The goal is to extract clusters that best fit the RFM(Recency, Frequency, Monetary) model.
