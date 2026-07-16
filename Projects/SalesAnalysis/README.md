# 📊 Sales Data Analysis

A complete exploratory data analysis of retail sales data using **Python, Pandas, NumPy, and Matplotlib**, covering everything from data cleaning to actionable business insights.

---

## 📌 Overview

This project analyzes a retail **Superstore** sales dataset to uncover trends across products, categories, customers, regions, and time. It walks through the full analytics workflow — data cleaning, feature engineering, exploratory analysis, and visualization — inside a single Jupyter Notebook.

## 🗂️ Dataset

The dataset contains order-level retail transactions with the following key fields:

| Field | Description |
|---|---|
| Order ID / Date / Ship Date | Order tracking information |
| Customer ID / Name / Segment | Customer details |
| City / State / Region | Location details |
| Category / Sub-Category / Product Name | Product details |
| Sales / Quantity / Discount / Profit | Transaction metrics |

## 🧹 Data Cleaning & Feature Engineering

- Removed redundant columns (`Row ID`, `Postal Code`, `Country`)
- Converted `Order Date` and `Ship Date` to datetime format
- Engineered new features:
  - `Shipping Days` — delivery time per order
  - `Month`, `Year`, `Quarter`, `Weekday` — for time-based analysis
  - `Selling Price`, `Original Price`, `Discount Amount` — for pricing analysis

## 📈 Analysis Performed

| Module | Key Questions Answered |
|---|---|
| **Overall Sales** | Total sales, profit, orders, and profit margin |
| **Product Analysis** | Best/worst selling and most/least profitable products |
| **Category & Sub-Category** | Sales, profit, and quantity trends by category |
| **Customer Analysis** | Top customers by sales/profit, repeat buyers |
| **Segment Analysis** | Performance across Consumer, Corporate, Home Office |
| **Regional Analysis** | Sales and profit by region, state, and city |
| **Time Analysis** | Monthly, quarterly, yearly, and weekday sales trends |
| **Discount Analysis** | Impact of discounts on profitability |
| **Profit Analysis** | Loss-making orders and top profit contributors |

## 🛠️ Tech Stack

- **Python 3**
- **Pandas** & **NumPy** — data manipulation
- **Matplotlib** — data visualization
- **Jupyter Notebook** — interactive analysis

## 📁 Project Structure

```
├── Notebook.ipynb        # Complete analysis notebook
├── Sales_Data.csv         # Raw dataset (not included / add your own)
└── README.md              # Project documentation
```

## 🚀 Getting Started

1. Clone the repository
   ```bash
   git clone https://github.com/nikhilkanbarkar/data-science-and-machine-learning/Projects/SalesAnalysis.git
   cd sales-data-analysis
   ```

2. Install dependencies
   ```bash
   pip install pandas numpy matplotlib jupyter
   ```

3. Add your dataset (`Sales_Data.csv`) to the project folder

4. Launch the notebook
   ```bash
   jupyter notebook Notebook.ipynb
   ```

## 💡 Key Insights

- Identifies the best-selling and most profitable products, categories, and customers
- Highlights regions and states driving the most revenue vs. loss
- Reveals seasonal sales trends across months and weekdays
- Quantifies how discounting affects overall profitability

## 📄 License

This project is open source and available for personal and educational use.

---

⭐ If you found this project useful, consider giving it a star on GitHub!