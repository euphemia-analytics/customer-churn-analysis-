no markdown 
# Customer churn Analysis
## Project Overview 
This project analyzes customer churn for ABC Communication Ltd,a telecommunications company. The objective is to identify customers behavior, usage patterns and service related factors that derives customer churn. The analysis provides data-driven insights that can help the business increase customer retention/loyalty,curb customer churn and support informed business decision making.
## Business problem
Customer churn is one of the biggest problems faced by telecommunications companies like ABC Communication Ltd,the rate which customers discontinue services, move on to a rival or go dormant long enough that the relationship is lost accumulates loss of revenue and customer loyalty. This project aims to provide key insights, business risk and actionable recommendations to improve customer retention.
## Project Objectives 
- Understand the business problem.
- Clean and prepare the dataset.
- Explore Customer data to identify patterns and trends.
- Analyze factors associated with customer churn.
- create interactive data visualization and dashboard to communicate key insights.
- Provide data driven recommendations to improve customer retention.
## Dataset overview 
The telco customer churn dataset contains customers information from ABC Communication Ltd.it includes customers demographic,subscribed services,contract details,billing methods,payment methods and churn status.The dataset was inspected to evaluate quality before carrying out the business analysis.
## Dataset structure 
- Number of revords(rows):7,043
- number of columns:21

Each row represents each customer while each column represents a specific customer attribute such as demographics, subscribed service,payment informations and churn status.
## Data types 
The dataset contains both categorical and numerical variables 
## categorical variables 
- CustomerID
- Gender
- Partner
- Dependent 
- Phoneservice
- Multiplelines
- Internetservicd
- Onlinesecurity
- Onlinebackup
- Deviceprotection
- Techsupport
- StreamingTV
- SreamingMovies
- Contract
- PaperlessBilling
- PaymentMethods
- Churn
# Numerical Variables
- Tenure
- SeniorCitizen
- MonthlyCharge
- TotalCharge

After inspection , all columns were found to have appropriate type for analysis.
## Missing Values 
The dataset was inspected using Excel's GO TO SPECIAL Feature. No missing values were found except TotalCharges column, which contained 11 blank cells.futher investigations showed that the affected customer had a tenure of 0 months.since the total charge column represents the cumulative charges paid by customers since joining the company. customers with zero months of tenure are yet to accumulate TotalCharge. therefore blank values are consistent with the business context and not a data entery error.
## Dublicate records 
The dataset was checked for duplicate records using power query. No duplicate were found, each customer customer record is unique and can be identified using the CustomerID Column.
## Feature Engineering 
A new variable named Charge category was created by grouping the monthly charge into three categories (LOW,MEDIUM,HIGH) to enable easier comparison of churn rate  across different pricing levels 
## Tools Used 
- Microsoft excel
- power query 
- pivort tables 
- pivot charts 
- Data visualization 
- Dashboard 
## Key Business insights 
- Customers on month-to-month contacts recorded the highest churn rate.
- Fiber optic customer exprienced relatively higher churn than DSL and customers with no internet service.
- Customers paying through electronic check are more likely to churn than customers usung automatic payment methods.
- Customers enrolled in paperless billing also showed higher churn rate.
- New customers (0-12 months)had the highest churn rate, while long term customers are more likely to stay.
- Customers without partners and dependents are more likely to churn.
- Gender and phone service showed little to no influence on churn rate.
## Business Recommendations 
- Encourage month-to-month customers to migrate to long-term contracts 
- Investigate the experience of fiber optic customers.
- Improve onboarding and engagement during customer's first year.
- Develop targeted retention campaign for high risk customers.
## Skills demonstrated 
- Data cleaning 
- Exploratory Data Analysis 
- KPI Development 
- Data visualization 
- Data storytelling 
- Business Recommendations 
----/
*this project is currently in progress as my data analytics internship.*