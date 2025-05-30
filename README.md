## I. Introduction
### 1. About Cohort Analysis
### What is cohort and cohort analysis? 
- A **cohort** is a group of users who share a common characteristic, and cohort analysis is a tool to measure their engagement over time.
- **Cohort analysis** helps to differentiate between actual improvements in user engagement and those that may be driven by growth, while vanity indicators do not provide the same level of insight.
### Three major types of Cohort
- **Time cohorts**: customers who signed up for a product or service during a particular time frame.
- **Behavior cohorts**: customers who purchased a product or subscribed to a service in the past.
- **Size cohorts**: refer to the various sizes of customers who purchase the company’s products or services.
### Which type of cohort is for this project?
- I will focus on performing Cohort Analysis based on Time(**Time cohorts**). 
- Customers will be divided into acquisition cohorts depending on the month of their first purchase. 
- The cohort index would then be assigned to each of the customer’s purchases, which will represent the number of months since the first transaction.
### 2. Business Questions
- Using Python to analyze transaction data from KPMG and creating a cohort that allows stakeholders to assess user engagement starting from their first transaction.
## II. Data Visualization with Python
- **MoM Retention Rate for Customer Transaction Data**
![image](https://github.com/user-attachments/assets/3112a8cc-a808-4a8c-9205-31b06e233bef)

## III. Insights
- Customers who register and place their first order in July 2017 have a high retention rate (up to 48.1%) after 5 months of operation.
- Customers who register and place their first order in April 2017 have a stable and relatively high retention rate: 45.1% (4th month), 42.1% (5th month) ), and 42.7% (7th month).
- Customers who register and place their first order in May 2021 also have a fairly high and stable retention rate: 40.4%,39%, and 41.3% in the 2nd, 3rd and 4th-month activities.
- Looking at the above insights, we can see that customers who start ordering from mid-year 4,5,6,7,8 tend to order stable, and relatively higher than the rest months of the year.
- Customers who place orders at the beginning of January and February only show stability, nothing special.
