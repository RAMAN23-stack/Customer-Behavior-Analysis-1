# 📊 Customer Behavior Analysis – Power BI Project

This project analyzes customer purchase behavior using interactive data visualizations in **Power BI**. The goal is to understand customer demographics, sales trends, payment preferences, and overall purchasing patterns.

---

## 🚀 Project Overview
This dashboard was created as part of an internship task to perform:
- Data Cleaning  
- Exploratory Data Analysis (EDA)  
- Visualization & Dashboard Creation  
- Insight Generation  

The dataset contains customer purchase details, demographic information, and payment behavior.

---

## 🛠 Tools & Technologies
- Power BI Desktop  
- Power Query  
- DAX  
- GitHub  

---

## 📁 Files in This Repository
| File Name | Description |
|----------|-------------|
| `Customer_Behavior_Analysis.pbix` | Main Power BI dashboard |
| `Customer_Behavior_Dashboard.pdf` | PDF export of the dashboard |
| `Insights.txt` | Insights summary |
| `README.md` | Project documentation |

---

## 📊 Dashboard Features

### 1. KPI Cards
- Total Sales  
- Total Customers  
- Average Rating  
- Total Transactions  

### 2. Category-wise Sales (Bar Chart)
Shows which customer categories contribute the most revenue.

### 3. Payment Method Analysis (Pie/Donut Chart)
Displays the most preferred payment types (Credit Card, PayPal, etc.).

### 4. Monthly Sales Trend (Line Chart)
Shows seasonality and peak sales months.

### 5. Gender-wise Purchases (Donut Chart)
Compares male vs female buying behavior.

### 6. Top 5 Customer Segments / Categories
Shows the highest-value customer groups using Top N filters.

---

## 🔍 Key Insights
- **Home category** generated the highest total purchase amount.  
- **Credit Card** is the most preferred payment method.  
- Sales peak during the **May–August** period.  
- **Female customers** purchase slightly more than male customers.  
- Customer ratings indicate overall satisfaction.

---

## 🧼 Data Cleaning Steps (Power Query)
- Removed empty rows  
- Removed duplicates  
- Converted data types  
- Handled missing values  
- Created new calculated columns if needed  

---

## 📈 Sample DAX Measures

```DAX
Total Sales = SUM('Table'[Total Purchase Amount])
Total Customers = DISTINCTCOUNT('Table'[Customer ID])
Average Rating = AVERAGE('Table'[Rating])

📝 How to Use This File

Download the .pbix file

Open it in Power BI Desktop

Connect to the same dataset if needed

Explore the interactive visuals

👨‍💻 Author

RAMAN.K
B.Tech Artificial Intelligence & Data Science
GitHub: https://github.com/RAMAN23-stack
