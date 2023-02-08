**Case Study: Analyzing Customer Churn in Power BI**
---
![image](https://user-images.githubusercontent.com/121925698/217402366-9bf089a4-b22e-4299-9382-dc0386b18a2a.png)

Summary of case study
---
This case study is for the purpose of applying skills developed through the Power Bi course offered by Data Camp using a real-world problem.

The Problem:
---

The task is to solve customer churn for a Telecom provider called Databel where I will be using a fictitious churn dataset. I will be analyzing why customers are churning and the churn rate.

Defining churn
---

A good definition is the one from Investopedia: “The churn rate, also known as the rate of attrition or customer churn, is the rate at which customers stop doing business with an entity.”

![image](https://user-images.githubusercontent.com/121925698/217403165-b5f713a7-4208-4eb6-b874-9de4c1ae9033.png)

Calculating churn
---

The simplified formula for churn is to divide customers lost by the total number of customers.

Churn rate = customers lost/total number of customers

Example:
Churn rate = 10/100 = 10%

There are multiple methods to calculate churn, and depending on the industry. A traditional e-commerce platform might consider a certain customer a churner if he or she hasn’t made a purchase in the last 12 months.

The data
---

Key Characteristics:

*One big table with 29 different columns with one row per customer.
*Snapshot of the database at a specific moment in time, meaning there is no time dimension.
*The dataset contains more than just dimensions. Here is a view of the [metadata] (https://assets.datacamp.com/production/repositories/5993/datasets/c55ad82061b13bc07f6516e51cba9883a90bfa27/Metadata%20-%20Case%20Study_Analyzing%20Customer%20Churn%20in%20Power%20BI.pdf)

Data check
---

The first step in any analysis is doing a data check. I will create two measures to check if the count of customer ids is equal to the count of unique customer ids. This check is particularly important to prevent double-count costs later incase of duplicates.
