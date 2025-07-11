<p align="center">
  <img src= "https://github.com/user-attachments/assets/c2444c9b-f7b0-46bc-b5c6-06ff811fb160" width="100%">
</p>

<h1>👥⚠️ User Churn Analysis in SuperStore Retail company with PowerBI</h1>
Author: Phuong Dasen<br>
Tool: PowerBI

## 📌 Table of Contents
- [📌 Background & Overview](#-background--overview)
- [📁 Dataset Description & Data Structure](#-dataset-description--data-structure)
- [🧠 Design Thinking Process](#-design-thinking-process)
- [📊 Key Insights & Visualizations](#-key-insights--visualizations)
- [🔍 Final Conclusion & Recommendations](#-final-conclusion--recommendations) 
  
## [📌 Background & Overview](#-background--overview)

## 🔍 What is this project about?<br>
- This project analyzes user churn using Power BI through Superstore Sales dataset - a global detail company in consumer, technoloy, furniture to uncover patterns, behaviors, and reasons behind customer attrition.<br>
- It visualizes key indicators such as demographic profiles, service usage, contract types, and churn reasons to support strategic decision-making.<br>

## 👤 Who is this project for?<br>
- Operational, Customer Service and Marketing Manager.<br>  

## ❓ Business questions<br>
- Who are the customers most at risk of churning?<br>
- Why are customers leaving the company?<br>
- What actions can reduce customer churn and improve retention?<br>

## [📁 Dataset Description & Data Structure](#dataset-description--data-structure)
## 📌 Data Source
* Source : Superstore Sales dataset<br>
* Size:<br>
        - The Orders table contains 51,290 records<br>
        - The People table contains 13 records<br>
        - The Returns table contains 1,172 records<br>
        - Format: .csv<br>
        
## 📊 Data Structure & Relationships<br>
## 1️⃣ Tables Used:
The dataset consists of three tables:
<details>
<summary>🔽 Table 1: Orders - Contains detailed transaction and customer information</summary>
<img width="2800" alt="Screenshot 2025-07-02 at 8 37 03 PM" src="https://github.com/user-attachments/assets/c020dce8-b8da-4125-87ab-4edeb0f111a9" />
<br>
</details>
<details>
<summary>🔽 Table 2: Returns – Stores data on returned orders</summary>
<img width="1500" alt="Screenshot 2025-07-02 at 8 38 03 PM" src="https://github.com/user-attachments/assets/3fc1168d-6c3a-4249-b3b6-223d735fb081" />
<br>
</details>
<details>
<summary>🔽 Table 3: People – Holds information about sales representatives</summary>
<img width="1500" alt="Screenshot 2025-07-02 at 8 38 28 PM" src="https://github.com/user-attachments/assets/1a60b3da-e5f5-4083-bf3d-eca8ed202f13" />
<br>
</details>
<details>
<summary>🔽 Data Dictionary</summary>
<img width="1000" alt="Screenshot 2025-07-02 at 8 38 28 PM" src= "https://github.com/user-attachments/assets/39e9f4b3-8e71-453c-abd8-3384d7b1bb0b" />
/>
<br>
</details>

## 2️⃣ Data Relationships:
<img width="1500" alt="Screenshot 2025-07-02 at 8 49 25 PM" src="https://github.com/user-attachments/assets/58e02e22-a7ed-48d4-86a9-162d1bc386ca" /><br>
---
## [🧠 Design Thinking Process](#-design-thinking-process)

<b>Here are the five steps of design thinking:</b>

<h3>Step 1 - Empathize</h3>
<img width="1000" alt="Screenshot 2025-05-22 at 09 18 20" src="https://github.com/user-attachments/assets/00ddc19a-57fb-42fa-8e5b-0b5de45fc272" />
<h3>Step 2 - Define</h3>
<img width="1000" alt="Screenshot 2025-05-22 at 09 18 30" src="https://github.com/user-attachments/assets/0a958352-800a-44cb-8452-121cc618df35" />
<h3>Step 3 - Ideate</h3>
<img width="1000" alt="Screenshot 2025-05-22 at 09 18 43" src="https://github.com/user-attachments/assets/5e44e451-2e8a-44f4-8e04-68bc7b31f4e7" />
<h3>Step 4 - Prototype</h3>
<img width="1000" alt="Screenshot 2025-05-22 at 09 18 52" src="https://github.com/user-attachments/assets/8ea64593-f592-4e34-b560-71a455561171" />
<h3>Step 5 - Review</h3>
<img width="1000" alt="Screenshot 2025-05-22 at 09 19 02" src="https://github.com/user-attachments/assets/66d9673b-7383-4167-88d1-188ebb6fa831" />

## [📊 Key Insights & Visualizations](#-key-insights--visualizations)
<h3>1. Customer Churn Overview</h3>
<img width="1550" height="700" alt="Screenshot 2025-07-11 at 5 27 50 PM" src="https://github.com/user-attachments/assets/4157f599-a41a-46ab-99d1-a29c99b564b2" /><br>
 
### 🔍 Key Insights

🟢 Customer Profile (Left Side)<br>
	•	👤 Age Group: 81% of customers are over 30 years old, showing a mature user base.<br>
	•	📈 Customer Tenure: 26% of customers joined within the last 10 months, suggesting steady acquisition.<br>
	•	🌍 Service Usage: UDP service has the highest usage at 67%, followed by DP&OB at 34%.<br>
	•	💳 Payment Preference: 55% of customers use Direct Debit, making it the most common payment method.<br>
	•	📄 Contract Type: Over half (51%) are on month-to-month contracts—indicating lower long-term commitment.<br>

⸻

🔴 Churner Profile (Right Side)<br>
	•	⚠️ Tenure Risk: 49% of churners left within the first 10 months—early churn is a major issue.<br>
	•	🧾 Contract Type: A striking 87.92% of churners were on month-to-month contracts.<br>
	•	🧍 Demographic: 84% of churners are over 30, slightly higher than the general population.<br>
	•	💳 Payment Shift: 71% of churners used Direct Debit—despite being the dominant method, it’s not sticky.<br>
	•	📉 Service Dissatisfaction: Higher churn rates correlate with UDP (80%) and Intl Active (49%) services.<br>
 
<h3>2. Customer Detail Profiles</h3>
<img width="1550" height="700" alt="Screenshot 2025-07-11 at 5 31 05 PM" src="https://github.com/user-attachments/assets/8f39d93e-b18e-4a73-a1d7-f38fa5736edc" />
<br>

### 🔎 Customer Detail Profile – Deep Dive into Churn Reasons<br>

📉 Churn Reason Breakdown<br>
	•	🥇 Top Reason: 45.51% churned due to competitors, primarily due to better offers or devices.<br>
	•	😤 Support Issues: 16.22% cited poor attitude from support staff—highlighting a customer service gap.<br>
	•	😒 Dissatisfaction: 16.17% left due to general service dissatisfaction.<br>
	•	💸 Price Sensitivity: 11.31% churned due to pricing issues, despite average monthly charge being low.<br>
	•	❓ Unknown Causes: 10.8% churned for “Other/Unknown” reasons—suggesting missing data or unclear survey results.<br>
## ✅ Recommendations for Action

- 📦 **Introduce Loyalty Incentives**: Convert more customers to annual or biannual contracts to reduce early churn.
- ☎️ **Upgrade Support Services**: Train support staff and implement satisfaction surveys to improve customer experience.
- 💼 **Competitive Benchmarking**: Regularly monitor competitors’ offers to stay competitive in pricing and device quality.
- 📊 **Segment Targeting**: Focus retention strategies on new customers and those on UDP/Intl Active plans.
- ❓ **Enrich Exit Surveys**: Enhance churn feedback collection to reduce “unknown” churn reasons and tailor future strategies.
