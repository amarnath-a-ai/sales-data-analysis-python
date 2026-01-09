# Week 2 – Sales Data Analysis Project

## 📌 Project Overview
This project demonstrates basic data analysis using Python and Pandas.  
A synthetic sales dataset is created and analyzed to extract meaningful business insights such as total revenue, product performance, category performance, and monthly sales trends.

The final processed dataset is exported as a CSV file for reporting purposes.

---

## 🧾 Objectives
- Create a sales dataset with at least 50 records
- Include order details such as product, category, quantity, price, and order date
- Calculate total sales amount for each order
- Generate overall sales summary
- Perform product-wise and category-wise sales analysis
- Perform monthly sales analysis
- Export the final dataset as a CSV file

---

## 🛠️ Technologies Used
- **Python**
- **Pandas**
- **Datetime module**

---

## 📂 Dataset Details
Each sales record contains the following fields:

| Column Name   | Description |
|--------------|------------|
| Order_ID     | Unique order number |
| Order_Date   | Date of order |
| Product      | Product name |
| Category     | Product category |
| Quantity     | Number of items sold |
| Price        | Price per unit |
| Total_Sales  | Quantity × Price |
| Month        | Month of the order |

---

## 🔄 Project Workflow

1. Generate a synthetic sales dataset with 50 records
2. Convert data into a Pandas DataFrame
3. Calculate total sales amount per order
4. Analyze:
   - Overall revenue and total orders
   - Product-wise sales performance
   - Category-wise sales performance
   - Monthly sales trends
5. Export the final dataset to a CSV file

---

## 📊 Key Analysis Performed

### Overall Sales Summary
- Total Revenue
- Total Number of Orders

### Product-wise Analysis
- Identifies top-performing products based on sales value

### Category-wise Analysis
- Compares revenue contribution across categories

### Monthly Sales Analysis
- Shows sales trends over different months

---

## 📁 Output File
- **`week2_sales_analysis_output.csv`**
  - Contains the final processed dataset with calculated total sales


---

## ▶️ How to Run the Project

1. Install required library:
   ```bash
   pip install pandas
