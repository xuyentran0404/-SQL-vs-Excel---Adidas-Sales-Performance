# [SQL vs Excel] Unveiling the Adidas Sales Database 2020/2021

---

## 1. Introduction

In this project, we analyze sales data from Adidas to gain insights into product performance, regional trends, and operational efficiency. The primary goal is to extract data-driven insights that can support decision-making in marketing, inventory planning, and sales strategy.

---

## 2. Database Access

- **Dataset**: Adidas Sales Data (CSV format)  
- **Source**: Internal company export / online resource *(replace with your actual source if needed)*  
- **Tool**: SQL Server Management Studio (SSMS)  

---

## 3. Exploring the Dataset

In this project, I write **9 SQL queries** in SQL Server Management Studio to explore insights from the database:

**Query 01: Seasonal Sales Trend Analysis. Calculate total units sold, revenue, total cost, total profit, and profit margin for each month in 2020–2021.**
-  SQL code 
![image](https://github.com/user-attachments/assets/5b78229e-77e6-492d-b92f-99b2e0d851b6)

- Query results
![image](https://github.com/user-attachments/assets/35ecfeb2-40c3-4599-9ff5-cddf4eef1cb1)

**Query 02: Retrieve sales quantity, profit of each product by month, and product ranking by total_sold for each month.**
- SQL code
![image](https://github.com/user-attachments/assets/1a527336-45ea-4811-9722-a0ae6308fe9a)


- Query results
![image](https://github.com/user-attachments/assets/e90d79ea-e49c-4c3c-b662-7655128f6aa9)


**Query 03: Calculate total Sales, Units Sold, Profit, Cost by product, order by revenue .**
- SQL code
![image](https://github.com/user-attachments/assets/702636b3-a5ec-48c4-b801-f4514a451f3f)

- Query results
![image](https://github.com/user-attachments/assets/def01d5b-6741-4d44-a6b8-bb868cf158c0)

**Query 04: Top 3 highest revenue products in each region.**
- SQL code
![image](https://github.com/user-attachments/assets/2a01b056-98b3-4562-a4f9-b362c13d642b)

- Query results
![image](https://github.com/user-attachments/assets/96fe6060-e846-4390-b715-6e679873e123)

**Query 05: Retailer Performance Ranking.**
- SQL code
![image](https://github.com/user-attachments/assets/38c8665e-b9bd-456f-bceb-2b07b7a3fca5)

- Query results
![image](https://github.com/user-attachments/assets/e6608dcb-6d39-487e-a46c-ab1df0f6ea66)

**Query 06: Sales_Method Performance Ranking .**
- SQL code
![image](https://github.com/user-attachments/assets/47df321f-4a52-47f6-9104-a58c48fb63f4)

- Query results
![image](https://github.com/user-attachments/assets/3d08acc3-5df8-4e9e-89c9-9e3d936437d8)


## 4. Data Visualization
**Overview Dashboard**  
![image](https://github.com/user-attachments/assets/4755907d-641e-4bf3-b826-927123b53519)

**Product Dashboard**
![image](https://github.com/user-attachments/assets/df849bf9-3bad-4d3e-93df-05ee52565fa9)

## 5. Insights
- **Seasonal Sales Trend Analysis**: Significant revenue and profit growth observed in the second half of 2021, with December reaching the highest figures (**$77.8M** in revenue and **$28.9M** in profit). Profit margins improved notably in 2021, ranging from **34.8%** to **40.2%**, indicating better cost efficiency. June 2020 recorded the lowest performance, with both revenue and profit at their minimum.
- **Men’s Street Footwear** leads in both revenue (**$208.8M**) and profit ($82.8M), with the highest margin (**40%**). **Women's Apparel** follows closely with strong revenue (**$179M**) and high profitability (**38%**).
- **Men’s Street Footwear** also ranks #1 in all regions for revenue, with strong profit margins (37–42%). 

## 6. Recommendations
- **Seasonal Sales Trend Analysis**: Prioritize investment during peak months **(May–December)** through increased marketing and inventory planning. Implement promotional strategies in off-peak months **(e.g., June)** to stimulate demand and reduce idle inventory. Sustain and enhance profit margins by expanding high-margin product lines and maintaining cost discipline.
- Continue promoting top-performing categories, especially **Men’s Street Footwear** and **Women’s Apparel**. 
- Prioritize **Men’s Street Footwear** in all regions due to its top revenue and solid profitability.
- Expand **Women's Apparel** marketing in **the South** and **Southeast**, where margins are especially strong.
