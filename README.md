# 📊 Bank Customer Churn Analysis (Excel Project)

## 📌 Project Overview
This project analyzes a dataset of 500 bank customers to understand the key factors influencing customer churn. The analysis was conducted using Microsoft Excel, including data cleaning, Pivot Tables, and statistical testing with the Data Analysis ToolPak.

The goal of this project is to uncover patterns in customer behavior and generate data-driven insights.

---

## 🗂 Dataset Description

The dataset contains the following variables:

- **CustomerID** – Unique identifier for each customer  
- **Surname** – Customer’s last name  
- **CreditScore** – Creditworthiness score (350–850)  
- **Geography** – France, Spain, Germany  
- **Gender** – Male / Female  
- **Age** – Customer age  
- **Tenure** – Number of years with the bank  
- **Balance** – Bank account balance  
- **NumOfProducts** – Number of banking products used  
- **HasCrCard** – Credit card ownership (1 = Yes, 0 = No)  
- **IsActiveMember** – Active membership status (1 = Active, 0 = Inactive)  
- **EstimatedSalary** – Estimated annual salary  
- **Churn** – Customer exit status (1 = Yes, 0 = No)

---

## 🧹 Data Cleaning

- Identified missing values in **EstimatedSalary**
- Detected inconsistent values in **Balance**
- Replaced missing and inconsistent values using the **average method**
- Verified dataset consistency before performing analysis

---

## 📈 Pivot Table Analysis

The following analytical questions were addressed using separate Pivot Tables:

1. Average credit score for each geography  
2. Average account balance by gender within each country  
3. Distribution of active vs non-active members based on credit card ownership  
4. Customer churn rate per number of products used  
5. Average credit score of churned vs retained customers across different tenure  

Each Pivot Table includes a brief summary of findings.

---

## 📊 Statistical Analysis (Data Analysis ToolPak)

**Significance Level: 0.05**

### Research Question 1  
Is there a significant difference in average salary between churned and non-churned customers?

- Method Used: Two-Sample t-Test  
- Decision based on p-value comparison with 0.05  

### Research Question 2  
Is there a significant difference in average credit scores among geographic locations?

- Method Used: ANOVA (Single Factor)  
- Decision based on p-value comparison with 0.05  

---

## 📎 Project Files

- Excel Dataset  
- Excel Analysis File (Pivot Tables + Hypothesis Testing)  
- PowerPoint Presentation  
- README Documentation  

---

## 🛠 Tools Used

- Microsoft Excel  
- Pivot Tables  
- Data Analysis ToolPak  

---

## 🎯 Conclusion

This project demonstrates practical application of Excel for data cleaning, exploratory data analysis, and hypothesis testing to derive meaningful business insights from customer churn data.

---
👩‍💻 Created by Nega Sri Radhakrishnan
