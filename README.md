# 📊 Sales Data Analysis Project (E-commerce Dataset)

## 📌 Project Overview

This project focuses on analyzing an e-commerce sales dataset to uncover meaningful business insights. The objective is to understand sales trends, product performance, customer segments, and regional distribution using data analysis techniques.

The analysis is performed using Python, with a focus on data cleaning, exploratory data analysis (EDA), and business storytelling.

---

## 🎯 Objectives

* Analyze sales performance over time
* Identify top-performing products and categories
* Evaluate regional sales distribution
* Understand customer segmentation
* Generate actionable business insights

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook / VS Code

---

## 📂 Dataset

* Source: Kaggle (Superstore Sales Dataset)
* Data includes:

  * Order details (Order ID, Order Date, Ship Date)
  * Customer information (Segment, Customer Name)
  * Product details (Category, Sub-category, Product Name)
  * Sales data (Revenue)

---

## 🧹 Data Cleaning Steps

* Handled missing values (Postal Code)
* Converted date columns to proper datetime format
* Removed duplicate records
* Created new features:

  * Year
  * Month
  * Month Name

---

## 📊 Exploratory Data Analysis (EDA)

### 📈 Sales Trend Analysis

* Sales showed a decline in 2016 followed by strong growth in 2017 and 2018

### 🛍️ Category Performance

* Technology category generated the highest revenue
* Furniture and Office Supplies contributed significantly but slightly lower

### 🌍 Regional Analysis

* West region achieved the highest sales
* South region showed the lowest performance, indicating growth opportunity

### 👥 Customer Segment Insights

* Consumer segment contributed the largest share of total sales

---

## 💡 Key Insights

* Business experienced strong recovery and growth after 2016
* Technology products are the primary revenue drivers
* Regional imbalance suggests potential for targeted marketing in underperforming regions
* Sales distribution follows a pattern where a few categories contribute heavily to total revenue

---

## 📁 Project Structure

```
sales-dashboard-project/
│
├── data/
│   └── raw_data.csv
│
├── notebooks/
│   └── analysis.ipynb
│
├── scripts/
│   └── data_cleaning.py
│
└── README.md
```

---

## 🚀 How to Run the Project

1. Clone the repository
2. Install required libraries:

   ```
   pip install pandas numpy matplotlib
   ```
3. Open the notebook:

   ```
   notebooks/analysis.ipynb
   ```
4. Run all cells to reproduce analysis

---

## 🔮 Future Improvements

* Build an interactive dashboard using Power BI
* Perform sales forecasting using time series models
* Implement customer segmentation (RFM analysis)
* Add profit analysis with enhanced dataset

---

## 📌 Conclusion

This project demonstrates how raw sales data can be transformed into actionable business insights using Python. It highlights the importance of data-driven decision-making in improving sales performance and identifying growth opportunities.

---

## 👤 Author

**Sakshi Pandey**

---
