# 📊 Superstore Sales Analysis — CodeAlpha Data Analytics Internship

## 📌 Project Overview

This project was completed as part of the **CodeAlpha Data Analytics Internship**.

The objective is to perform **Exploratory Data Analysis (EDA)** and **Data Visualization** on a Superstore sales dataset to identify patterns in sales, profitability, discounts, customer segments, products, and regional performance.

The dataset contains **10,194 records and 21 original features**.

---

## 🎯 Objectives

- Understand the structure and quality of the dataset
- Clean and preprocess the data
- Analyze overall sales and profitability
- Compare product categories and sub-categories
- Investigate the relationship between discounts and profit
- Analyze regional and customer segment performance
- Examine sales and profit trends over time
- Identify highly profitable and loss-making products
- Generate actionable business insights

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- VS Code

---

## 📊 Key Business Metrics

| Metric | Result |
|---|---:|
| Total Sales | $2.33M |
| Total Profit | $292.30K |
| Overall Profit Margin | 12.56% |
| Quantity Sold | 38,654 |
| Unique Orders | 5,111 |

---

## 🔍 Key Insights

- **Technology** generated the highest category sales and profit.
- **Furniture** generated substantial sales but comparatively low profit.
- **Tables** were the most loss-making sub-category, with approximately **-$17.75K** in profit.
- **Copiers** were the most profitable sub-category, generating approximately **$56.09K** in profit.
- Discount and profit showed a **weak negative correlation (-0.22)**.
- Every observed discount group of **30% or above generated negative total profit**.
- The **West** region led in sales, profit, and profit margin.
- The **Central** region had the lowest regional profit margin at **7.92%**.
- Annual profit increased consistently from **2023 to 2026**.
- The **Consumer** segment generated the highest total sales and profit.
- The **Home Office** segment achieved the highest segment profit margin at **14.02%**.

---

## 💡 Business Recommendations

1. Review transactions involving high discount levels, particularly discounts of 30% and above.
2. Investigate the weak profitability of Furniture, especially Tables and Bookcases.
3. Examine pricing and discount patterns for major loss-making products.
4. Study the factors contributing to the strong profitability of Copiers and other high-performing products.
5. Investigate the relatively low profitability of the Central region.
6. Evaluate business performance using both revenue and profitability rather than sales alone.

---

## 📁 Project Structure

    CodeAlpha_internship/
    │
    ├── data/
    │   └── sample_-_superstore.csv
    │
    ├── notebooks/
    │   └── EDA_Superstore.ipynb
    │
    ├── images/
    ├── reports/
    ├── README.md
    ├── requirements.txt
    └── .gitignore

---

## 🚀 How to Run

1. Clone this repository.
2. Install the required Python packages:

       pip install -r requirements.txt

3. Open:

       notebooks/EDA_Superstore.ipynb

4. Run the notebook cells sequentially.

---

## 📌 Conclusion

The analysis shows that high sales do not necessarily translate into high profitability. Product mix, discount levels, customer segments, and regional performance all contribute to business outcomes.

The project demonstrates how exploratory data analysis and visualization can transform transactional data into meaningful business insights.