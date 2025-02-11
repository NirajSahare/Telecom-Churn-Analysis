# 📊 Telecom Churn Analysis Dashboard
## 📌 Project Overview
This Power BI Telecom Churn Analysis project helps identify key factors influencing customer retention and predicts high-risk customers. It utilizes MySQL, Power BI, and Machine Learning to explore customer behavior, analyze churn patterns, and uncover risk factors. The analysis is divided into two dashboards: Churn Summary and Churn Predictions, providing insights into customer demographics, service usage, and predictive churn modeling. By understanding why customers leave, telecom providers can enhance customer experience, optimize service plans, and implement targeted retention strategies to reduce churn and improve profitability.

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
1. Customers with **month-to-month contracts** have the highest churn rate.
2. **Online payment methods** show higher churn rates compared to traditional methods.
3. Customers with **longer tenure periods(> 24 months)** have higher churn rate.
4. Geographic trends show some states have significantly higher churn rates.
5. Total Churn for **female(1,111)** was higher than male(921).
6. Women aged **18-24** months in tenure show a significant increase in churn rate when crossing the 24-month threshold.
7. **Women over 65 years** old have a **14.2%** higher churn rate compared to younger age groups.
8. **Jammu & Kashmir** accounts for **59%** of churned female customers, making it the highest churn region for women.
9. Customers with **"None"** as their internet type have the highest churn rate, especially in Jammu & Kashmir.
10. **64.8%** of churned women in Jammu & Kashmir do not have an internet plan, suggesting dissatisfaction with available services or a lack of suitable options.

### 2️⃣ Churn Predictions Dashboard
This dashboard identifies at-risk customers using predictive analytics to help telecom companies take preventive measures.

#### 🔹 Customers at Risk

1. Count of predicted churners
2. Monthly charge, total revenue, total refunds, and number of referrals for predicted churners

#### 🔹 Predicted Churner Profile

1. Gender distribution of predicted churners
2. Churn probability by:
   a. Age group
   b. Marital status
   c. Tenure group
   d. Payment method
   e. Contract type
   f. State

## 🔍 Key Business Insights Based on Predicted Churner Profile

1. Customers with a **month-to-month contract** show the highest churn rate, totaling **352 customers**, which accounts for **95% of overall churned customers**.  
2. **Credit card holders** represent the largest group of churned customers, with a total of **181**.  
3. The states with the highest churn rates are **Maharashtra, Uttar Pradesh, and Tamil Nadu**.  
4. Customers in the **tenure group of over 24 months**, particularly those aged **35-51**, exhibit the highest churn rate.
   

## 💡 Suggestions for Reducing Churn:

✔️ Introduce special loyalty offers or renewal discounts for female customers and credit card holders nearing 24 months of tenure.
 
✔️ Develop targeted retention programs for customers over 65, possibly by improving customer service and offering personalized plans.
 
✔️ Investigate and conduct a survey the high churn rate in **Jammu & Kashmir**, **Maharashtra, Uttar Pradesh, and Tamil Nadu**—potential issues like network quality, pricing, or service disruptions could be driving customers away.
 
✔️ Consider door-to-door outreach to assess whether customers face network issues, affordability concerns, or lack awareness about available plans.
 
✔️ Develop customized internet packages for non-internet users to encourage service adoption and reduce churn.

✔️ Simplify the payment process to encourage automatic payments.


![Image](https://github.com/user-attachments/assets/176969ac-b636-46ac-8fcc-077dc5980463)

## 🛠 Tools Used
1. Power BI – Data visualization and dashboard creation
2. MySQL  – EDA and Data preprocessing
3. DAX – Custom measures for KPIs and calculations
### 🚀 How to View the Dashboard
1. Download the Power BI file from this repository.
2. Open the file in Power BI Desktop.
3. Explore interactive visuals to gain insights.
