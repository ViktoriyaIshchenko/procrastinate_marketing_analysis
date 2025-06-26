# Marketing Metrics Analysis for Procrastinate Pro+ App

## Project Description  
Despite significant advertising investment, the Procrastinate Pro+ entertainment app has been experiencing financial losses over the past few months. This project aims to uncover the reasons behind the negative trends and help the company move towards profitability through a comprehensive analysis of user behavior, acquisition channels, and return on marketing investment.

## Objectives  
The analysis seeks to answer the following questions:
- Where do users come from, and what devices do they use?
- How much does it cost to acquire users from different marketing channels?
- How much revenue does each customer generate?
- When do customer acquisition costs break even?
- What factors hinder effective customer acquisition?

## Dataset Description  
The data spans from May 1 to October 27, 2019, and includes:

- **User session logs**  
  File: `visits_info_short.csv`  
  - `User Id`: Unique user ID  
  - `Region`: User's country  
  - `Device`: User device type  
  - `Channel`: Source of traffic  
  - `Session Start`: Session start datetime  
  - `Session End`: Session end datetime  

- **Purchase records**  
  File: `orders_info_short.csv`  
  - `User Id`: Unique user ID  
  - `Event Dt`: Purchase datetime  
  - `Revenue`: Order amount  

- **Advertising costs**  
  File: `costs_info_short.csv`  
  - `dt`: Date of advertising campaign  
  - `Channel`: Advertising source  
  - `costs`: Expenses for the campaign  

## Project Workflow  
1. **Data Overview**  
2. **Data Cleaning & Preprocessing**  
3. **Exploratory Data Analysis**  
4. **Marketing Metric Calculation**  
   - Customer Acquisition Cost (CAC)  
   - Revenue per User  
   - Return on Investment (ROI)  
   - Payback Period  
5. **Insights and Recommendations**

## Tools & Technologies  
- Python  
- pandas  
- matplotlib, seaborn  
- datetime, numpy  

## Key Outcomes  
- Identification of the most cost-effective advertising channels  
- Evaluation of user behavior across devices and countries  
- Insights into profitability and customer lifetime value (LTV)

## Author  
This project was developed as part of a Data Science educational program.
