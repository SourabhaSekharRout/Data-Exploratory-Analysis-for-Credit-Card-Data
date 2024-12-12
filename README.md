# Data Exploratory Analysis for Credit Card Data
## Objective
To analyze credit card data for PSPD Bank, providing actionable insights into customer spending and repayment behaviors, uncovering fraud patterns, and supporting strategic decision-making.
## Overview
Credit card data offers valuable insights into customer behavior, fraud detection, and revenue growth opportunities. By analyzing transaction and repayment patterns, the bank can enhance customer experiences, create personalized offerings, and implement fraud prevention mechanisms. This project aims to address key business problems posed by the CEO of PSPD Bank.
## Dataset Used
The dataset comprises the following sheets:
1.	<a href="https://github.com/SourabhaSekharRout/Data-Exploratory-Analysis-for-Credit-Card-Data/blob/main/Customer%20Acqusition.csv">Customer Acquisition</a>:
   - Details of customers at the time of card issuance.
2.	<a href="https://github.com/SourabhaSekharRout/Data-Exploratory-Analysis-for-Credit-Card-Data/blob/main/spend.csv">Spend (Transaction Data)</a>:
   - Records of credit card spending for each customer.
3.	<a href="https://github.com/SourabhaSekharRout/Data-Exploratory-Analysis-for-Credit-Card-Data/blob/main/Repayment.csv">Repayment</a>:
   - Data on credit card payments made by customers.
## Questions Addressed
- Data cleaning tasks for invalid age, spending, and repayment amounts.
- Summarizations:
  - Number of distinct customers and categories.
  - Average monthly spend and repayment amounts.
  - Bank profit calculations.
  - Top product types, cities with maximum spend, high-spending age groups, and top customers in repayment.
- City-wise yearly spending analysis by product with graphical representation.
- Visual comparisons of spending trends across various dimensions.
- Python function for dynamic analysis of top customers.
## Process
The process involves the following steps:
- Load the data from various sources into the working environment.
- Adjust data types to ensure compatibility and accuracy.
- Handle missing values to maintain data integrity.
- Identify and treat outliers to avoid skewed analysis.
- Combine datasets to form a cohesive structure for analysis.
- Perform initial analysis to summarize key patterns and insights.
- Data Transformation:
  - Replace invalid age values (< 18) with the mean age.
  - Adjust spending amounts exceeding the limit to 50% of the respective customer’s limit.
  - Cap repayment amounts exceeding the limit to the respective limit.
- Summarization:
  - Count distinct customers and categories.
  - Calculate average monthly spend and repayment amounts.
  - Compute monthly bank profit based on the defined profit formula.
  - Identify top product types and cities with the highest spending.
  - Analyze spending patterns by age group and repayment rankings.
- City-wise and Yearly Analysis:
  - Calculate yearly spending by city and product.
  - Create graphical representations for the findings.
- Visualization:
  - Monthly total spend comparisons city-wise.
  - Yearly spending trends for air tickets.
  - Monthly spending patterns by product to identify seasonality.
- User-defined Python Function:
  - Find the top 10 customers for each city based on repayment amounts by specified product types and time periods (yearly or monthly).
## Features
- Data preprocessing for robust analysis.
- Statistical summaries and insights.
- Visualizations for spending trends and patterns.
- Dynamic user-defined function for custom analysis.
## Insights
- Key customer demographics and spending behaviors.
- Profit-generating patterns and trends.
- Fraud detection through anomaly analysis.
- City-wise and product-wise spending insights.
- Seasonal trends in spending across various products.
## Conclusion
This project empowers PSPD Bank to better understand customer behaviors, enhance fraud detection, and drive revenue growth through data-driven decision-making.
