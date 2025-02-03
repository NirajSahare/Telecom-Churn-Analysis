# 📊 Telecom Churn Analysis Dashboard
## 📌 Project Overview
This Power BI project analyzes telecom customer churn to identify key factors influencing customer retention and predict high-risk customers. The analysis is divided into two dashboards: Churn Summary and Churn Predictions, offering insights into customer demographics, service usage, and predictive churn modeling.

## ❓ Business Questions Answered
1. What are the key demographic factors influencing churn?
2. How does contract type affect churn rates?
3. Which services contribute most to customer retention or churn?
4. Are there specific states with higher churn rates?
5. What customer profile is most at risk of churning?
6. How can the company reduce churn through targeted interventions?

## 📂 Dashboards
### 1️⃣ Churn Summary Dashboard
This dashboard provides an overview of churn trends, customer demographics, and account-related factors affecting churn.

#### 🔹 Key Performance Indicators (KPIs)

1. Total Customers
2. New Joiners
3. Total Churn
4. Churn Rate

#### 🔹 Demographic Analysis

1. Total churn by gender
2. Churn rate by age group
   
#### 🔹 Account Information

1. Churn rate by payment method
2. Churn rate by contract type
3. Churn rate by tenure group

#### 🔹 Geographic Distribution

1. Churn rate in the top 5 states

#### 🔹 Service Usage Analysis

1. Total churn by internet type
2. Churn by additional services (e.g., streaming, phone service, etc.)
   

![Image](https://github.com/user-attachments/assets/31f9deb0-3bc1-4818-885b-62ee9b58f098)

## 🔍 Key Business Insights
1. Customers with month-to-month contracts have the highest churn rate.
2. Online payment methods show higher churn rates compared to traditional methods.
3. Customers with longer tenure periods(> 24 months) have higher churn rate.
4. Geographic trends show some states have significantly higher churn rates.
5. Total Churn for female(1,111) was higher than male(921).
6. Women aged **18-24** months in tenure show a significant increase in churn rate when crossing the 24-month threshold.
7. Women over 65 years old have a **14.2%** higher churn rate compared to younger age groups.
8. Jammu & Kashmir accounts for **59%** of churned female customers, making it the highest churn region for women.
9. Customers with "None" as their internet type have the highest churn rate, especially in Jammu & Kashmir.
10. **64.8%** of churned women in Jammu & Kashmir do not have an internet plan, suggesting dissatisfaction with available services or a lack of suitable options.

## 💡 Suggestions for Reducing Churn:
 ✔️ Introduce special loyalty offers or renewal discounts for female customers nearing 24 months of tenure.
 
 ✔️ Develop targeted retention programs for customers over 65, possibly by improving customer service and offering personalized plans.
 
 ✔️ Investigate and conduct a survey the high churn rate in Jammu & Kashmir—potential issues like network quality, pricing, or service disruptions could be driving customers away.
 
 ✔️ Consider door-to-door outreach to assess whether customers face network issues, affordability concerns, or lack awareness about available plans.
 
 ✔️ Develop customized internet packages for non-internet users to encourage service adoption and reduce churn.

### 2️⃣ Churn Predictions Dashboard
This dashboard identifies at-risk customers using predictive analytics to help telecom companies take preventive measures.

#### 🔹 Customers at Risk

1. Count of predicted churners
2. Monthly charge, total revenue, total refunds, and number of referrals for predicted churners

#### 🔹 Predicted Churner Profile

1. Gender distribution of predicted churners
2. Churn probability by:
  Age group
  Marital status
  Tenure group
  Payment method
  Contract type
  State

![Image](https://github.com/user-attachments/assets/d396d750-673e-4116-b4d6-a445d1542ca1)


## 💡 Suggestions for Reducing Churn
✔️ Offer discounts or loyalty rewards for long-term contracts.
✔️ Improve service quality for customers in high-churn states.
✔️ Provide incentives for referrals and customer retention.
✔️ Target high-risk customers with personalized retention campaigns.
✔️ Simplify the payment process to encourage automatic payments.

## 🛠 Tools Used
Power BI – Data visualization and dashboard creation
MySQL  – EDA and Data preprocessing
DAX – Custom measures for KPIs and calculations
### 🚀 How to View the Dashboard
Download the Power BI file from this repository.
Open the file in Power BI Desktop.
Explore interactive visuals to gain insights.
