
# Customer-Churn-Analysis-using-Power-BI

This project is designed to analyze and understand the factors influencing customer churn in a banking institution.

Using data visualization and analysis tools in Power BI, this project explores various customer attributes, such as customer demographics, activity status, product usage, and credit scores, to identify trends and patterns that contribute to customer churn. 

The dashboard provides actionable insights into which customer segments are most at risk of leaving the bank and helps in devising strategies to improve customer retention. 
## Data Source
The data for this project is consist of 10,000 bank customers.

It providing detailed insights into various aspects of customer behavior and demographics. The dataset includes information on:
- Customer demographics
- Credit scores
- Age groups
- Account balances
- Activity status
- Product and service usage
- Credit card status

This rich dataset serves as a valuable resource for understanding customer churn patterns and improving strategies to enhance customer retention in the banking sector.
[Churn Dataset](https://drive.google.com/file/d/17bUJhEkQEDmoyLZ88TyS_Pi2IRcRMfAg/view).



## Data Importation
Utilized Power BI to import data through a MySQL local database, ensuring a seamless data integration process. 

This approach enabled efficient data extraction and transformation, facilitating real-time analytics and interactive reporting. 

## Data Cleaning and Preparation
Performed comprehensive data cleaning and preparation using Power Query Editor, including:

- Promoted Headers
- Changed Data Types
- Replaced Values
- Reordered Data
- Added Conditional Columns
- Filtered Data


## Dashboard Guide
This dashboard presents key metrics and insights related to customer churn in a bank. 

It is designed to provide a clear and concise overview of various factors influencing churn, enabling stakeholders to better understand customer behavior and make informed decisions.

![image](https://github.com/user-attachments/assets/33dad20b-4c9c-4e4f-8cc2-4f80f8f8e677)

- **Total Customers & At-Risk Customers:** Overview of the total number of customers and those at risk of churning.
- **Churn Rate:** A visual representation of the churn rate across all customers.
- **Customer Segmentation:** Pie charts show the distribution of customers by products/services, activity status, country, credit card status, and gender.
- **Churn Analysis:** Bar charts analyze the number of customers and churn rates across different age groups, credit scores, and account balances.

## Key Findings

**Overall Churn Rate**:
- The churn rate is calculated at 20.4%, indicating that a significant portion of customers are leaving the bank. 

**Customer Distribution** 

Out of 10,000 customers, 2,037 (20.4%) are at risk of churn.
- 69.17% of at-risk customers have a debit card
- 10.8% have a loan
- 17.08% use insurance services
- 2.95% use other products and services
Higher churn rates are observed among females, credit card holders, and inactive customers.


**Activity Status Impact**
- 63.92% are inactive and might be more prone to churn. Re-engaging these customers could help reduce churn.

**Credit Card Ownership**
- 30.09% do not own a credit card, while 69.91% own a credit card, are at risk of churn.
- Credit card ownership appears to be associated with customer retention. 


**Gender Insights**
- Females exhibit a higher churn rate compared to males.

**Age Group Analysis**
- 51-60 age group shows a higher churn rate.

**Credit Score Insights**
- Lower credit scores (<400) are associated with higher churn.
- Higher credit scores (601-700) have varying churn rates. 

**Balance Impact**
- Customers with balances >200K show the highest churn rate, suggesting possible dissatisfaction.



## Recommendations
**Customer Segmentation** 
* The bank should consider segmenting customers based on balance, activity status, and credit score for more personalized retention strategies.
  
**Engagement Initiatives** 
- Focus on re-engaging inactive customers and those in high-risk segments like the 51-60 age group or those with low balances or credit scores.

**Product Offerings** 
- Tailor product offerings to meet the needs of customers with high churn rates, such as providing better loan or insurance options.

