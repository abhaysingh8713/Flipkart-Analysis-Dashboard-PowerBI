# 📊 Flipkart Product Analysis Dashboard

📅 **Date:** 28/07/2026  
📁 **Project Type:** End-to-End Data Analytics Project  

---

## 📋 Project Overview
This project demonstrates an end-to-end data analytics workflow using a Flipkart product dataset. It covers:
* **Data cleaning & transformation** in Excel
* **Data modeling & analysis** in SQL
* **Interactive dashboard creation** in Power BI

The goal is to uncover business insights such as top-selling products, discount trends, seller performance, and stock levels, and to present them in a clean and interactive Power BI report.

---

## ⚙️ Step 1: Data Cleaning (Excel)
* Downloaded the raw dataset from Kaggle.
* Removed duplicates, fixed formatting, and ensured column names matched SQL naming conventions.
* Saved as `.csv` for database import.
* 📁 *Cleaned Data Folder attached above.*

---

## 🗄️ Step 2: SQL Database Integration (pgAdmin/PostgreSQL)
* Imported the cleaned CSV into PostgreSQL using pgAdmin 4.
* Created a table named `flipkart_products`.
* Designed and executed SQL queries to extract key business insights.
* 📁 *SQL Folder attached above.*

### 📜 8 SQL View Creation Scripts:
1. `Top_Selling_Products` View
2. `Category_total_Sales` View
3. `Top_Rated_Products` View
4. `Category_Avg_Discount` View
5. `Return_Policy_Distribution` View
6. `Low_Stock_Products` View
7. `Popular_Subcategory` View
8. `Seller_With_Most_Products` View

---

## 📈 Step 3: Dashboard in Power BI
* Imported SQL views into Power BI using Import mode.
* Created 4 interactive report pages.
* 📁 *Power BI Folder & Screenshots attached above.*

### 🏠 Page 1: Home
Project Title, Description, and Tools Used.

### 📊 Page 2: Sales Overview
* **KPI Cards:** Total Products, Total Units Sold, Average Price
* **Slicers:** Main Category, Sub-Category
* **Charts:** Top Selling Products (Bar chart), Category Total Sales (Donut chart), Subcategory Popularity (Column chart)

### 🏷️ Page 3: Discounts & Ratings Overview
* **KPI Cards:** Average Discount %, Average Rating
* **Slicer:** Main Category
* **Visuals:** Top Rated Products (Table), Average Discount by Category (Column chart)

### 📦 Page 4: Sellers And Return Policy Overview
* **KPI Card:** Total Sellers
* **Slicers:** Return Policy, Seller
* **Charts:** Low Stock Products (Bar chart), Return Policy Distribution (Pie chart), Sellers with Most Products (Column chart)

---

## 💻 Tools & Technologies Used
* **Excel** – Data Extraction, Cleaning, & Transformation
* **PostgreSQL (pgAdmin 4)** – SQL Analysis & Views 
* **Power BI** – Dashboard & Visualization

---

## 💡 Key Learnings
* How to clean raw data for accurate analysis.
* How to write analytical SQL queries and generate logical views.
* How to visualize complex insights in Power BI.
* How to successfully structure an end-to-end data analytics project.

---

## 👨‍💻 Author
**Abhay Singh**  
* 📧 **Email:** Abhaysingh8713@gmail.com  
* 💻 **GitHub:** [github.com/abhaysingh8713](https://github.com/abhaysingh8713)  
* 🔗 **LinkedIn:** [www.linkedin.com/in/abhaysingh8713]
