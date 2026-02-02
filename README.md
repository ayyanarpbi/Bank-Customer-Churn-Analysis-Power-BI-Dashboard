# Bank-Customer-Churn-Analysis-Power-BI-Dashboard
End-to-end Power BI dashboard for analyzing banking customer churn and retention insights.

🏦 Bank Customer Churn Analysis – Power BI
🔹 Project Overview

The Bank Customer Churn Analysis Dashboard is a Power BI project developed to analyze customer behavior and identify factors influencing customer churn in a banking environment.
The dashboard provides actionable insights to help the bank reduce churn, improve customer retention strategies, and increase long-term customer value.

🎯 Business Objective

The primary objective of this project is to analyze historical bank customer data and identify key drivers that lead customers to exit the bank.
This enables business teams to design targeted retention campaigns and loyalty programs based on customer behavior and risk patterns. 

DBS_BusinessRequirementDocument

🛠 Tools & Technologies

Microsoft Power BI Desktop , Power BI Service 

Microsoft Excel (Data Source)

DAX (Data Analysis Expressions)

Data Modeling

Banking Domain Analytics

📂 Data Sources

Data is collected from multiple banking-related tables:

ActiveCustomer

Bank_Churn

CreditCard

CustomerInfo

ExitCustomer

Gender

Geography 

DBS_BusinessRequirementDocument

These datasets are combined using relationships to build a unified customer churn model.

📊 Data Dictionary (Key Columns)

| Column          | Description                              |
| --------------- | ---------------------------------------- |
| CustomerId      | Unique customer identifier               |
| CreditScore     | Customer credit rating                   |
| Geography       | Customer location                        |
| Gender          | Male / Female                            |
| Age             | Customer age                             |
| Tenure          | Years with the bank                      |
| Balance         | Account balance                          |
| NumOfProducts   | Number of bank products                  |
| HasCrCard       | Credit card holder (1 = Yes, 0 = No)     |
| IsActiveMember  | Active status (1 = Active, 0 = Inactive) |
| EstimatedSalary | Customer salary                          |
| Exited          | Churn flag (1 = Exit, 0 = Retain)        |
| Bank DOJ        | Customer joining date                    |

📌 Key KPIs

1.Total Customers

2.Total Churned Customers

3.Churn Rate %

4.Active vs Inactive Customers

5.Average Credit Score of Churned Customers

6.Average Balance of Churned Customers

7.Product-wise Churn Rate

📈 Dashboard Features
1. Churn Overview

-Total customers vs exited customers

-Overall churn percentage

2. Demographic Analysis

-Churn by age group

-Churn by gender

-Churn by geography

3. Financial Behavior Analysis

-Churn by credit score category

-Churn by balance range

-Churn by estimated salary

4. Customer Engagement

-Churn by number of products

-Churn by credit card usage

-Churn by active/inactive status

🔍 Business Insights

Customers with low credit scores show higher churn probability

Inactive members are more likely to exit

Customers with fewer bank products tend to churn more

Lower balance and salary customers have higher churn rates

Certain geographic regions show higher churn risk

DBS_BusinessRequirementDocument

🚀 How to Use

1.Open the .pbix file in Power BI Desktop

2.Refresh the data

3.Use slicers for Geography, Gender, Age group

4.Analyze churn patterns interactively

📎 Project Files

-Bank_Customer_Churn.pbix

-bank_churn_data.xlsx

-End to end Banking project.pbix

-README.md

🔮 Future Enhancements

Add churn prediction using ML model

Integrate SQL Server / Azure data source

Create risk scoring system

Implement RLS for branch managers

Add automated retention alerts

👤 Author

Name: Ayyanar M
Role: Power BI Developer
Domain: Banking Analytics
Skills: Power BI, DAX, Excel, SQL, Data Modeling , Power BI Service.

⭐ Conclusion

This project demonstrates a real-world banking analytics use case where customer behavior is analyzed to reduce churn.
The dashboard enables decision-makers to identify high-risk customers and take proactive retention actions using data-driven insights.


