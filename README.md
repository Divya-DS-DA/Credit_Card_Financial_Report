Overview
This project analyzes customer and credit card transaction data to gain insights into customer behavior, spending patterns, and credit card performance. The goal is to help businesses tailor their strategies for improving customer satisfaction, increasing credit card usage, and optimizing marketing campaigns. The project includes datasets, SQL queries, and visual dashboards to provide a comprehensive understanding of customer demographics and credit card activity.

Files in the Repository
1. customer.csv
Description: Contains demographic and personal details of the credit card customers.
Columns:
Client_Num: Unique identifier for each customer.
Customer_Age: Age of the customer.
Gender: Gender of the customer (Male/Female).
Dependent_Count: Number of dependents the customer has.
Education_Level: Education level of the customer.
Marital_Status: Marital status of the customer.
state_cd: State code where the customer resides.
Zipcode: Customer's residential zipcode.
Car_Owner: Whether the customer owns a car (Yes/No).
House_Owner: Whether the customer owns a house (Yes/No).
Personal_loan: Whether the customer has a personal loan (Yes/No).
contact: Customer's preferred contact method.
Customer_Job: The job or occupation of the customer.
Income: The customer's annual income.
Cust_Satisfaction_Score: A score indicating the customer's overall satisfaction.
2. creditcard.csv
Description: Contains data related to customers' credit card accounts and their usage.
Columns:
Client_Num: Unique identifier for each customer, linking to customer.csv.
Card_Category: The type of credit card the customer has (e.g., Platinum, Gold).
Annual_Fees: The annual fee charged for the credit card.
Activation_30_Days: Whether the card was activated within 30 days of issuance (Yes/No).
Customer_Acq_Cost: The cost to the business for acquiring the customer.
Week_Start_Date: The start date of the current week for the transaction.
Week_Num: The week number within the year.
Qtr: The quarter in which the transaction occurred (1-4).
current_year: The current year of the transaction.
Credit_Limit: The total credit limit assigned to the customer's credit card.
Total_Revolving_Bal: The total revolving balance (debt carried from month to month).
Total_Trans_Amt: The total amount of all transactions made by the customer.
Total_Trans_Vol: The total number of transactions made by the customer.
Avg_Utilization_Ratio: The average ratio of the credit card balance to the credit limit.
Use Chip: Whether the customer used the chip functionality of the card (Yes/No).
Exp Type: Type of expenses charged on the card (e.g., Personal, Business).
Interest_Earned: The amount of interest earned from the customer.
Delinquent_Acc: Number of delinquent accounts associated with the customer.
3. cc_add.csv
Description: Supplementary credit card information, including card limits and types.
4. cust_add.csv
Description: Contains customer address details for further analysis on geographical distribution.
5. credit_card_report_dashboard1.pdf
Description: PDF dashboard showing visualizations related to credit card usage and transaction patterns.
6. customer_credit_card_report_dashboard2.pdf
Description: PDF dashboard focusing on customer demographic data and credit card usage.
7. sql_q.sql
Description: SQL script with queries used to analyze customer behavior, credit card usage, and spending patterns. The queries perform tasks such as:
Joining customer and credit card datasets.
Calculating total transactions, usage ratios, and customer satisfaction.
Identifying high-value customers and those at risk of delinquency.
How to Use
Data Analysis:

Load the CSV files (customer.csv, creditcard.csv, cc_add.csv, cust_add.csv) into your data analysis tool (e.g., Python, Excel, SQL).
Explore relationships between customer demographics and credit card usage to identify patterns.
SQL Queries:

Use the sql_q.sql file to run the pre-built SQL queries on your database. These queries extract and summarize key insights from the datasets.
Visualization:

Review the PDF dashboards (credit_card_report_dashboard1.pdf and customer_credit_card_report_dashboard2.pdf) to get a visual summary of key metrics and findings.
Project Goals
Understand Customer Behavior: Use demographic and transaction data to segment customers.
Optimize Marketing Strategies: Identify high-value customers and create targeted campaigns.
Reduce Risk: Analyze delinquent accounts and identify customers at risk.
Improve Customer Retention: Use customer satisfaction and transaction data to build loyalty programs.
Tools Used
SQL: For querying and joining datasets.
Python (Pandas, Matplotlib, Seaborn): For data analysis and visualizations.
Excel: For preliminary data exploration.
Tableau/Power BI: For creating dashboards and interactive visualizations.
Future Work
Incorporate predictive analytics to forecast customer behavior and credit card usage.
Develop real-time dashboards for monitoring customer activity.
Expand the analysis to include external factors like economic trends and market changes.
