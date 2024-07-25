# Credit Card Spending Analysis

## Project Objective:

The objective of this Power BI dashboard is to analyze the dataset and generate a comprehensive report aimed at facilitating strategic decision-making for stakeholders. 

By leveraging the insights provided, stakeholders can identify patterns and trends in credit card usage, enabling them to make informed decisions on optimizing features to potentially increase revenue.

## Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiNjUxOWM2OTQtZmQxNS00ZWMzLThjZTktYjI1MTM4ZDE1M2IyIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9

## About Datset:

Before Moving Forward I want to share with you about data set,

 * So Basicaly For this project, an American credit card transaction dataset has been utilized, encompassing data from January 2023 to December 2023.

 * The dataset comprises two Excel sheets: "credit_card.xls" and "customers.xls". These sheets contain essential information regarding credit card transactions and customer details.

## Data Description:
### Credit_Card.xls 
Here's a description of the data fields in the provided dataset:

 * Client_Num: Unique identification number assigned to each client/customer.
 * Card_Category: Category of the credit card (e.g., Blue, Gold, Platinum).
 * Annual_Fees: Annual fee associated with the credit card.
 * Activation_30_Days: Indicator (0 or 1) specifying whether the card was activated within 30 days of issuance.
 * Customer_Acq_Cost: Cost incurred in acquiring the customer.
 * Week_Start_Date: Start date of the week to which the data pertains.
 * Week_Num: Week number corresponding to the data entry.
 * Qtr: Quarter of the year (Q1, Q2, Q3, Q4).
 * current_year: Year to which the data belongs.
 * Credit_Limit: Maximum amount that can be charged on the credit card.
 * Total_Revolving_Bal: Total outstanding balance on the credit card.
 * Total_Trans_Amt: Total transaction amount made using the credit card.
 * Total_Trans_Vol: Total transaction volume (number of transactions) made using the credit card.
 * Avg_Utilization_Ratio: Average utilization ratio of the credit card balance to the credit limit.
 * Use Chip: Indicates whether the credit card transaction was done using a chip (Chip) or not (Swipe, Online).
 * Exp Type: Type of expenditure associated with the transaction (e.g., Travel, Entertainment, Bills, Grocery, Fuel).
 * Interest_Earned: Interest earned on the credit balance.
 * Delinquent_Acc: Indicates whether the account is delinquent (1) or not (0).

### Customer.xls
Here's a description of the data fields in the provided customer dataset:

 * Client_Num: Unique identification number assigned to each client/customer.
 * Customer_Age: Age of the customer.
 * Gender: Gender of the customer (M for Male, F for Female).
 * Dependent_Count: Number of dependents the customer has.
 * Education_Level: Educational qualification of the customer.
 * Marital_Status: Marital status of the customer (Single, Married, Divorced, etc.).
 * state_cd: State code indicating the state where the customer resides.
 * Zipcode: Zip code of the customer's location.
 * Car_Owner: Indicates whether the customer owns a car (yes/no).
 * House_Owner: Indicates whether the customer owns a house (yes/no).
 * Personal_loan: Indicates whether the customer has a personal loan (yes/no).
 * contact: Preferred mode of contact with the customer (cellular, telephone, etc.).
 * Customer_Job: Occupation or job role of the customer.
 * Income: Annual income of the customer.
 * Cust_Satisfaction_Score: Customer satisfaction score, possibly based on feedback or surveys.

## Dashboard Overview:

The Power BI dashboard comprises two distinct pages, each serving a specific purpose in alignment with the project request:

#### 1.Customers Demographic Page:
This page offers an in-depth portrayal of customers' demographic attributes.

#### 2.Customers Transaction Page:
The second page of the dashboard is dedicated to presenting customer transaction data.
## Detailed Explanation:
### Dashboard 1: Customer
As evident above, Page One focuses on customer-based analysis. However, here's a detailed explanation:
#### Here are the important key performance indicators (KPIs) in detail:
 * Total Customers: The dataset comprises a total of 10,110 customers.
 * Male Customers: There are 4,228 male customers in the dataset.
 * Female Customers: The dataset includes 5,880 female customers.
 * Average Customer Satisfaction Score: The average satisfaction score among customers is 3.19.
### Total Customers by Car Ownership:
Utilizing a bar chart, it's evident that out of the total customers, 6,044 do not own a car, whereas 4,064 customers possess a car.
### Total Customers by Marital Status:
Represented with a donut chart, it's easy to observe that out of the total customer base, 5,128 are married, 4,236 are single, and there are 744 customers with unknown marital status.
### Customers by State Code and Gender:
Using a bar chart, the top 5 states by customer count are depicted, along with the distribution based on gender.
 * California (CA): This state has the highest number of customers. Specifically, there are 1,609 female customers and 859 male customers.
 * Texas (TX): Texas holds the third position in customer count. It comprises 1453 female customers and 941 male customers.
 * New York (NY): Following California, New York ranks second in terms of total customers. Here, there are 1,279 female customers and 991 male customers.
 * Florida (FL): Florida is the fourth-ranked state in terms of total customers. It consists of 897 female customers and 814 male customers.
 * New Jersey (NJ): Lastly, New Jersey is among the top 5 states, with 350 female customers and 366 male customers.
By examining this analysis in detail, stakeholders can gain valuable insights into the distribution of customers across different states and genders.
### Customers by Job Type and Gender:
Through this analysis, it can be observed how many customers hold different job types, indicating the nature of their employment or profession.
Examining the data in detail provides clear insights into the distribution of customers based on their job type and gender.
### Total Customers by Age:
For the analysis of total customers by age group, a column chart has been employed. 

 * This visualization allows for easy interpretation of the distribution of customers across different age groups. It's evident that the highest number of customers falls within the 40-50 age group, while the lowest number is observed within the 20-30 age group.
### Customers by Income Group:
For the analysis of total customers by income group, a column chart has been utilized. 
This visualization facilitates easy observation of the distribution of customers across different income brackets. It's apparent that the highest number of customers belongs to the low-income group, whereas the high-income group comprises fewer customers.
### Customers by Education level-
For the analysis of total customers by education level, a column bar chart has been employed. This visualization allows for easy observation of the distribution of customers across different education levels.
Upon analysis, it is evident that the highest number of customers hold a graduate degree.
## Dashboard 2: Transaction 
#### Here's a detailed description of the important KPIs on Page Two - Transaction:
 * Total Revenue: The total revenue generated is $55 million.
 * Total Transactions: The total number of transactions is 656,000.
 * Transaction Amount: The total transaction amount is $45 million.
 * Interest Earned: The interest earned is $7.8 million.

### 1.Revenue Trend by Date:
A line chart has been utilized to illustrate the revenue trend over time. It's evident that the highest revenue was generated in July.

### 2.Quarterly Revenue by Transaction Count:
This analysis shows the revenue generated in each quarter alongside the transaction count. It's found that Q3 generated the highest revenue, amounting to $14.2 million, with the highest transaction count of 167,000.

### 3.Revenue by Card Category:
A table has been used to display revenue generated by different card categories, along with transaction count, transaction amount, and interest earned. Analysis reveals that the Blue card category yields the highest revenue, highest transaction amount, highest transaction count, and maximum interest earned.

### 4.Revenue by Use Method:
The analysis indicates that the highest revenue was generated through the swipe use method, totaling $34.9 million, while online transactions contributed the least, amounting to $3.4 million.

### 5.Revenue by Gender:
Using a donut chart, it's observed that revenue from male customers is $30 million, constituting 54% of the total revenue, whereas revenue from female customers amounts to $25 million.

### 6.Revenue by Marital Status:
A donut chart is employed to visualize revenue generated by different marital statuses. It's evident that married customers contributed the highest revenue ($28 million), followed by single customers ($23 million) and unknown marital status ($4 million).

### 7.Revenue by Expenditure Type:
The analysis reveals that bill expenditure generated the highest revenue ($14 million), while travel expenditure contributed the least revenue ($6 million).

### 8.Revenue by Customer Job:
It's observed that revenue generation is highest among business owners, totaling $17 million, followed by white-collar jobholders ($10 million) and self-employed individuals ($8 million).

### 9.Revenue by State Code:
Texas generates the highest revenue, amounting to $12.8 million, followed by New York with $12.7 million.

This detailed analysis provides comprehensive insights into revenue generation trends based on various factors.



## Our Target Customers:
Based on the analysis results, our target customers are likely to be:

#### 1.Graduate Degree Holders:
Since the majority of customers hold a graduate degree, targeting this demographic segment can be fruitful.

#### 2.Middle-Aged Individuals (40-50 age group):
With the highest number of customers falling within this age bracket, tailoring marketing strategies and product offerings to meet their needs and preferences can be effective.

#### 3.Low to Middle Income Group: 
As the dataset suggests a larger customer base in the low-income group, focusing on providing affordable and value-added services/products could attract and retain these customers.

#### 4.Blue Card Category Holders: 
Since the Blue card category contributes the most to revenue generation, offering incentives, rewards, or exclusive benefits to this group could further enhance their loyalty and spending.

#### 5.Customers Employed in Business/White-Collar Jobs:
Business ownrs and white-collar jobholders seem to generate the highest revenue. Thus, targeting professionals in these sectors with tailored financial products/services could lead to increased engagement and revenue.

## Recommendation:
 * Promote Rewards and Benefits: Enhance marketing efforts to highlight the rewards, cashback offers, and exclusive benefits associated with the Blue card category to attract more customers towards it.
 * Targeted Marketing Campaigns: Design targeted marketing campaigns focusing on the preferences and needs of middle-aged individuals, emphasizing convenience, security, and tailored financial solutions.
 * Financial Education and Planning Services: Offer financial education workshops or online resources to help customers in the low-income group manage their finances better and improve their financial well-being.
 * Personalized Offers and Recommendations: Leverage data analytics to provide personalized offers and recommendations based on customers' transaction history, preferences, and life stage to increase engagement and cross-selling opportunities.
 * Customer Retention Strategies: Implement customer retention strategies such as loyalty programs, personalized communications, and proactive customer service to foster long-term relationships and reduce churn.
By targeting these specific customer segments and implementing the recommended strategies, we can aim for sustainable revenue growth and enhanced customer satisfaction in the long run.


## SQL Queries for Effective Bank Loan Testing
### KPI’s:
### Number of people not taken personal loan
![Credit card](https://github.com/user-attachments/assets/c573958b-6703-4e65-945e-af9e28d086e6)
### Number of people taken personal loan
![Credit card](https://github.com/user-attachments/assets/42f1793c-b824-4178-b95a-0aa404d50904)
### Number of people are having Own house's
![Credit card](https://github.com/user-attachments/assets/88bb6dde-0682-4ef7-a2e8-7e54a362f01f)
### Number of people not having Own house's
![Credit card](https://github.com/user-attachments/assets/2550ea99-bfbf-4208-8405-23f1a8d54bdb)
### Total Customer by Department
![Credit card](https://github.com/user-attachments/assets/b9fb50a8-f107-4298-9531-6c9f20c5e865)
### Customers by Education Level | Gender
![Credit card](https://github.com/user-attachments/assets/af47d28f-3127-4ae8-aa6f-fb324338d2b5)
### Top State by Total Customer | Gender
![Credit card](https://github.com/user-attachments/assets/72593574-d155-4f9c-abc9-e6da92b9c1f2)
### Average Customer Satisfaction Score
![Credit card](https://github.com/user-attachments/assets/3ed0a855-7e68-4a96-8b31-563b03cbe49b)
### Male Customers
![Credit card](https://github.com/user-attachments/assets/831b0470-d7e9-40bc-add9-12dda3d4a7bf)
### Female Customers
![Credit card](https://github.com/user-attachments/assets/2c170f2f-3f82-486d-96fb-564c35d45843)
### Total Customers
![Credit card](https://github.com/user-attachments/assets/580ec581-1eca-4e73-a84f-e81375eb0d0b)
### Revenue by Card Category
![Credit card](https://github.com/user-attachments/assets/54753649-945a-4b98-b467-381e94dc641c)
### Quarterly Revenue by Transaction Count
![Credit card](https://github.com/user-attachments/assets/a366733f-3dd8-4ed9-aae3-f08174975f58)
### Revenue Trend by Date
![Credit card](https://github.com/user-attachments/assets/20834ce0-6610-4e0c-a162-aa61e2f29eb7)
### Transaction_count
![Credit card](https://github.com/user-attachments/assets/a661ea23-5db4-4a8e-989a-3f5941d94777)
### Total_Interest_Earned
![Credit card](https://github.com/user-attachments/assets/2af65dbc-0768-4a69-888f-1f086e8ae60c)
### Total_Transaction
![Credit card]("https://github.com/user-attachments/assets/41d93329-3b70-42b0-9197-fbb9ae0bb60e)
### Total_Revenue
![Credit card](https://github.com/user-attachments/assets/71b1a27e-756a-4903-9bb9-601e697fc903)

## Conclusion
The Credit Card Spending Analysis project, using data from January to December 2023, reveals key insights into customer demographics and transaction patterns. The dashboard highlights significant findings, including a predominance of female customers, a high concentration in the 40-50 age group, and substantial revenue from the Blue card category. Swipe transactions generate the most revenue, while online transactions contribute the least. Recommendations focus on targeting graduate degree holders, middle-aged individuals, and low to middle-income groups, enhancing rewards for Blue cardholders, and tailoring financial products for business owners and white-collar jobholders. By leveraging these insights, stakeholders can optimize credit card features, improve customer engagement, and drive revenue growth.

