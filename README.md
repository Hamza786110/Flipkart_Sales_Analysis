# Flipkart Sales Analysis

---

##  Project Overview

This project performs **Exploratory Data Analysis (EDA)** on Flipkart sales data to uncover valuable insights into sales trends, product performance, pricing strategies, discounts, and customer behavior.

Using Python, the analysis helps:
- Identify top-selling products and categories
- Understand the impact of pricing and discounts on sales
- Detect seasonal and monthly sales patterns
- Generate actionable business recommendations for e-commerce optimization

---

##  Key Objectives

| Objective | Description |
|-----------|-------------|
| Data Cleaning | Handle missing values, duplicates, and incorrect data types |
| EDA | Perform comprehensive Exploratory Data Analysis |
| Visualization | Create insightful charts using Matplotlib and Seaborn |
| Business Insights | Extract key insights on products, categories, and sales performance |

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| **Python 3** | Core programming language |
| **Pandas** | Data manipulation and analysis |
| **Matplotlib** | Data visualization |
| **Seaborn** | Statistical data visualization |
| **Jupyter Notebook** | Interactive development environment |

---

## Project Structure

```
Flipkart_Sales_Analysis/
├── README.md
└── Flipkart Sales Project/
    ├── Flipkart_Sales_Analysis.ipynb     # Main Jupyter Notebook (EDA)
    ├── data/                             # Raw & processed datasets
    ├── images/                           # Exported visualizations
    └── requirements.txt                  # Project dependencies
```

---

## Analysis Performed

### 1. Data Cleaning
- Handling missing values and duplicates
- Fixing incorrect data types
- Feature engineering for analysis-ready columns

### 2. Descriptive Statistics
- Summary of sales, quantity, pricing, and discounts
- Central tendency and spread across key metrics

### 3. Univariate Analysis
- Distribution of price, quantity, category, and discount fields
- Frequency counts and percentage breakdowns

### 4. Bivariate & Multivariate Analysis
- Relationship between price, discount, sales, and categories
- Correlation heatmaps across numerical features

### 5. Category & Product Performance
- Top-performing products and categories by revenue and volume
- Lowest-performing segments identified for business action

### 6. Pricing & Discount Analysis
- Impact of discount percentage on sales volume and revenue
- Optimal discount range identification

### 7. Time-based Trends
- Monthly and seasonal sales patterns
- Peak sales periods and troughs

---

##  Key Insights

-  **Total Sales reached ₹75.2M** with a total profit of **₹15M** across all product categories
-  **3K units sold** with an **average customer rating of 3.01** — indicating room for product quality improvement
-  **Electronics** leads profit at **₹34,61,434**, followed by Clothing (**₹30,22,877**) and Books (**₹29,57,151**)
-  **Home & Kitchen** has the lowest profit contribution (**₹26,65,041**) — an opportunity for better pricing or promotions
-  **Profit peaks in June–July** and dips sharply in August–September, revealing clear seasonal buying patterns
-  **Discount and Sales trends move inversely** mid-year — strong sales even with lower discounts suggests growing brand loyalty
-  **Sales channels are evenly balanced**: Retail (33%), Online (33.9%), and Wholesale (33.1%) — a healthy multi-channel mix
-  **Top products by volume**: Education Supplies, Laptops, and Table Lamps — **lowest**: Bedsheets and Comic Books
-  **August shows a significant profit dip** — ideal window for targeted promotional campaigns
-  Dashboard includes a **Region filter** for location-based performance drill-down

---

##  Dashboard Preview

![Flipkart Sales Analysis Dashboard](Flipkart%20Sales%20Project/Dashboard%20Image.png)

> **Dashboard highlights:** KPI cards showing Total Profit (₹15M), Quantity Sold (3K), Avg Customer Rating (3.01), and Total Sales (₹75.2M). Includes charts for Sales by Product, Sales vs Discount trend, Customer Segment distribution (Retail / Online / Wholesale), Monthly Profit trend, and Category-wise Profit breakdown.

---

##  How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/Hamza786110/Flipkart_Sales_Analysis.git
cd Flipkart_Sales_Analysis
```

### 2. Install Dependencies

```bash
pip install pandas matplotlib seaborn jupyter
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 4. Open the Main Notebook

Navigate to `Flipkart Sales Project/` and open `Flipkart_Sales_Analysis.ipynb`. Run all cells to view the complete analysis and visualizations.

---

##  Author

**Hamza Nathwala** — Data Analyst & Python Developer

<p>
  <a href="https://github.com/Hamza786110">
    <img src="https://img.shields.io/badge/GitHub-Hamza786110-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"/>
  </a>
</p>

---

<p align="center">
  ⭐ If you found this project helpful, please consider giving it a star!
</p>
