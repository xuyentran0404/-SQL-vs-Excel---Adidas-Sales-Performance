# [SQL vs Excel] Adidas Sales Performance Insights

---

## 1. Introduction

In this project, we analyze sales data from Adidas to gain insights into product performance, regional trends, and operational efficiency.  
The primary goal is to extract data-driven insights that can support decision-making in marketing, inventory planning, and sales strategy.

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

**Query 02: Identify which products to promote, review, or retire based on their sales volume and profitability.**
- SQL code
![image](https://github.com/user-attachments/assets/19fdfab8-cc96-4906-9541-bf2851267cf1)

- Query results
![image](https://github.com/user-attachments/assets/dc02f058-3ee8-4a8a-88e8-ec00c3d76826)

**Query 03: Top 3 highest revenue products in each region.**
- SQL code
![image](https://github.com/user-attachments/assets/70b98a1d-044a-4785-b93c-e2aa67ca1766)

- Query results
![image](https://github.com/user-attachments/assets/8fa75ca6-f0ec-4f53-8a4f-feddab34028c)

**Query 04: Retailer Performance Ranking.**
- SQL code
![image](https://github.com/user-attachments/assets/60559108-bf35-4df7-972e-d8b9697194f9)

- Query results
![image](https://github.com/user-attachments/assets/f60ad8e3-36d0-498d-b451-ecbcc41f5b67)

**Query 05: Sales_Method Performance Ranking .**
- SQL code
![image](https://github.com/user-attachments/assets/50e50636-3b48-407b-a254-02414f895f28)

- Query results
![image](https://github.com/user-attachments/assets/8cd89c78-1eda-4b3c-8acd-f6042f71f749)

## 4. Data Visualization
- Overview Dashboard
- Product Dashboard
## 5. Insights
- Seasonal Sales Trend Analysis: Significant revenue and profit growth observed in the second half of 2021, with December reaching the highest figures ($77.8M in revenue and $28.9M in profit). Profit margins improved notably in 2021, ranging from 34.8% to 40.2%, indicating better cost efficiency. June 2020 recorded the lowest performance, with both revenue and profit at their minimum.
- Men’s Street Footwear leads in both revenue ($208.8M) and profit ($82.8M), with the highest margin (40%). Women's Apparel follows closely with strong revenue ($179M) and high profitability (38%).
- Men’s Street Footwear also ranks #1 in all regions for revenue, with strong profit margins (37–42%). 

## 6. Recommendations
