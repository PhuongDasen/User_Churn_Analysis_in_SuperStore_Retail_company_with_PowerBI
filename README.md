<p align="center">
  <img src= "https://github.com/user-attachments/assets/c2444c9b-f7b0-46bc-b5c6-06ff811fb160" width="100%">
</p>

<h1>👥⚠️ User Churn Analysis by PowerBI</h1>
Author: Phuong Dasen<br>
Tool: PowerBI

## 📌 Table of Contents
- [📌 Background & Overview](#-background--overview)
- [📁 Dataset Description & Data Structure](#-dataset-description--data-structure)
- [🧠 Design Thinking Process](#-design-thinking-process)
- [📊 Key Insights & Visualizations](#-key-insights--visualizations)
- [🔍 Final Conclusion & Recommendations](#-final-conclusion--recommendations) 
  
## 📌 Background & Overview

## 🔍 What is this project about?<br>
- Analyzes company-wide sales data to assess performance across products, regions, and customer segments.<br>
- Deliver actionable insights through a Power BI dashboard for strategic decision-making and market expansion.<br>

## 👤 Who is this project for?<br>
- Senior management, including sales and regional directors.<br>  

## ❓ Business questions<br>
	1.	Who are the customers most at risk of churning?<br>
	2.	Why are customers leaving the company?<br>
	3.	What actions can reduce customer churn and improve retention?<br>

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
<img width="1000" alt="Screenshot 2025-07-02 at 8 38 28 PM" src="https://github.com/user-attachments/assets/e4c9474f-1c34-4264-af36-dcdbf2351208" />
<br>
</details>




## 2️⃣ Data Relationships:
<img width="1500" alt="Screenshot 2025-07-02 at 8 49 25 PM" src="https://github.com/user-attachments/assets/58e02e22-a7ed-48d4-86a9-162d1bc386ca" /><br>
---
## [🧠 Design Thinking Process](#design-thinking-process)
<h2>1️⃣ Step 1 - Empathize </h2><br>

<img width="1000" alt="Screenshot 2025-05-05 at 13 03 14" src="https://github.com/user-attachments/assets/99136c62-2ea9-41ec-97e8-287d2b1cbafb" /><br>

<h2>2️⃣ Step 2 - Define Point of view </h2><br>
<img width="1000" alt="Screenshot 2025-05-05 at 13 04 50" src="https://github.com/user-attachments/assets/16d38903-b9f1-4aa9-be32-26a3f364d93b" /><br>
<img width="1000" alt="Screenshot 2025-05-05 at 13 05 01" src="https://github.com/user-attachments/assets/52b600ee-0673-4a9f-b40f-dab14569248a" /><br>

<h2>3️⃣ Step 3 - Ideate </h2><br>
<img width="1000" alt="Screenshot 2025-05-05 at 13 14 52" src="https://github.com/user-attachments/assets/0791bd41-c793-48e1-85bf-294b56aaea19" /><br>
<img width="1000" alt="Screenshot 2025-05-05 at 13 12 49" src="https://github.com/user-attachments/assets/16b99573-0804-4684-9848-39da613a4d14" /><br>

## [📊 Key Insights & Visualizations](#key-insights--visualizations)

<h2>1. Profit Analysis </h2>
<img width="1804" alt="Screenshot 2025-05-05 at 13 22 42" src="https://github.com/user-attachments/assets/cc3c214d-02ae-47bb-ac66-3535be5fa4e7" /><br>
<h2>2. Best-selling product </h2>
<img width="1807" alt="Screenshot 2025-05-05 at 13 21 02" src="https://github.com/user-attachments/assets/090fc931-ab95-4173-b81f-e7656926dd2a" /><br>
<h2>3. Person and ship </h2>
<img width="1801" alt="Screenshot 2025-05-05 at 13 21 14" src="https://github.com/user-attachments/assets/ed09f462-bc86-41b8-ab36-af1459e7232d" /><br>
<h1>IV. Insights and strategic recommendations</h1>
<h3>💡 Insights </h3>
<b>1. Company Sales Situation Over the Years</b><br>
- YoY Growth: 52% increase in profit<br>
- Profit trend is strongly upward, especially from Q3 2013 to Q4 2014.<br>
<b>2. Regional Sales Situation</b><br>
- Top Performing Region: Central - clearly leading in profit<br>
- Other Strong Regions: North America (North, US) and EU<br>
- Top Seller: Anna Andreadi - 37% of total sales.<br>
<b>3. Best/Worst-Selling Product Categories</b><br>
      + Top Category by Quantity: Office Supplies - 108,182 units sold.<br>
      + Top Subcategories: Binders (21,429 units -> Successful: 20,007 units), Storage (16,917 units), Art (16,301 units) <br>
- Worst Performing Sub-Category (based on return). Binders )1,422 units returned) <br>
<b>4. Conclusion</b><br>
- According to profit: <br>
      + Technolodgy is the most profitable category.<br>
      + Consumer is the most profitable segment. -> APAC is the market where we have the highest profit - 0.44M and Central EU is the Market region with the highest profit.<br>
- According to Return of Sales (ROS)<br>
      + Technology and Office supplies bring the highest ROS <br>
      + As for Segment, it's the same about ROS<br>
      + Canada is the market that brings the highest ROS<br>
  <h3>🚀 Recommendations </h3>
<b>1. Expansion Suggestions:</b><br>
- Focus expansion in Central and North regions due to high profit volumes.<br>
- APAC and Canada are highly profitable markets - worth reinforcing or expanding further.<br>

<b>2. Product Focus:</b><br>
- Invest in Phones and Copiers<br>
- Maintain strong push on Office Supplies category.<br>
- Consider reviewing and improving the quality or return policy for Binders, given the high retuen rate <br>

  









<h2>I. Introduction</h2>
<h3>1. Introduction to Dataset</h3>
<ul>
  <li>User churn refers to the phenomenon of customers or users of a product or service disengaging or ceasing to use it over time, which can be detrimental to the business.</li>
  <li>Understanding the reasons why users churn can help companies develop strategies to retain their customers and improve their overall product or service.</li>
  <li>The dataset includes a dim table containing information about users of a telecommunications network company, including fields of demographic information and information related to the user's churn.</li>
</ul>
<h3>2. Data Dictionary</h3>
<img width="900" alt="Screenshot 2025-05-14 at 13 35 48" src="https://github.com/user-attachments/assets/5cd2f378-a6a2-4718-9a21-54ce075a3741" />
<h3>3. Business Questions</h3>
<ul>
  <li>Create an overview dashboard for managers that displays the churn status of users and helps identify which users are part of th churn group.</li>
  <li>Develop solutions to improve the situation and reduce user churn.</li>
</ul>
<h2>II. Design Thinking Method</h2>
<b>Here are the five steps of design thinking:</b>
<h3>Step 1 - Empathize</h3>
<img width="825" alt="Screenshot 2025-05-22 at 09 18 20" src="https://github.com/user-attachments/assets/00ddc19a-57fb-42fa-8e5b-0b5de45fc272" />
<h3>Step 2 - Define</h3>
<img width="827" alt="Screenshot 2025-05-22 at 09 18 30" src="https://github.com/user-attachments/assets/0a958352-800a-44cb-8452-121cc618df35" />
<h3>Step 3 - Ideate</h3>
<img width="827" alt="Screenshot 2025-05-22 at 09 18 43" src="https://github.com/user-attachments/assets/5e44e451-2e8a-44f4-8e04-68bc7b31f4e7" />
<h3>Step 4 - Prototype</h3>
<img width="830" alt="Screenshot 2025-05-22 at 09 18 52" src="https://github.com/user-attachments/assets/8ea64593-f592-4e34-b560-71a455561171" />
<h3>Step 5 - Review</h3>
<img width="829" alt="Screenshot 2025-05-22 at 09 19 02" src="https://github.com/user-attachments/assets/66d9673b-7383-4167-88d1-188ebb6fa831" />
<h2>III. Visualization</h2>
<h3>1. Customer churn overview</h3>
<img width="1000" alt="Screenshot 2025-05-14 at 13 50 05" src="https://github.com/user-attachments/assets/ff453069-5099-4349-8a0c-becb7ab06e3d" />
<h3>2. Customer dashboard: personal details, contract, Service, Churn details</h3>
<img width="1000" alt="Screenshot 2025-05-14 at 09 40 1" src="https://github.com/user-attachments/assets/a75c2a79-710c-4592-8431-02dc611dc3a5" />
<h3>3. Churn reasons </h3>
<img width="1000" alt="Screenshot 2025-05-14 at 09 40 29" src="https://github.com/user-attachments/assets/75772cbc-aaea-429e-a2bf-acc550a6c888" />
<h3>4. Ask a question related to the data</h3>
<img width="1000" alt="Screenshot 2025-05-14 at 09 40 53" src="https://github.com/user-attachments/assets/94b68734-de27-4802-a4b1-77f84acb8b73" />
<h2>IV. Insights</h2>
<ul>
  <li>Competitors have better offers + prices than our company.</li>
  <li>Our customer service is not good, churn customers have a much higher avg customer service call rate = 2.4 than average.</li>
  <li>Customers who use 0-10 gb of monthly download and subscribe to Unlimited Data plan have a higher churn rate than teh rest of the group.</li>
  <li>Customers with "month to minth" contracts have a high churn rate of almost 90%.</li>
</ul>
<h2>V. Recommendations</h2>
<ul>
  <li>Need to improve customer service: optimize the problem-solving process: quickly for customers, avoid the situation that customsers call many times without solving the problem.</li>
  <li>It is necessary to have online + phone consultants to solve the problems that customers encounter.</li>
  <li>Customers who sign up for a month to month contract need to have incentives for: top up, preferential data packages to retain this group of customers.</li>
  <li>Need to improve the unlimited data package in terms of price or create a really preferential data package for the group of customers who need to use from 0 to 10 gb monthly.</li>
  <li>Create great offers for new customers, but also have incentives and gratitude for loxal cuatomers, but customers churn because competitors are better than our company 45% of the reason for churn.</li>
</ul>
