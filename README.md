# 📊 Customer Shopping Behavior Analysis

An end-to-end **Data Analytics** project that analyzes customer shopping behavior using **Python, PostgreSQL, SQL, and Power BI**. The project demonstrates the complete analytics workflow—from data cleaning and exploratory data analysis (EDA) to SQL-based business analysis, interactive dashboard development, and actionable business recommendations.

---

## 📌 Project Overview

Retail businesses collect large volumes of customer transaction data, but extracting meaningful insights from this data is challenging. This project analyzes customer shopping behavior to identify purchasing patterns, customer preferences, and revenue-driving factors that can support better business decisions.

### Objectives

- Clean and preprocess raw customer shopping data.
- Perform Exploratory Data Analysis (EDA).
- Engineer useful analytical features.
- Store cleaned data in PostgreSQL.
- Answer business questions using SQL.
- Build an interactive Power BI dashboard.
- Generate business insights and recommendations.

---

## 📂 Dataset

| Attribute | Details |
|-----------|---------|
| Records | **3,900** |
| Original Features | **18** |
| Cleaned Features | **19** |
| Missing Values | Review Rating (37 missing values handled) |
| Source | Customer Shopping Behavior Dataset (Kaggle) |

### Key Features

- Customer ID
- Age
- Gender
- Item Purchased
- Category
- Purchase Amount
- Location
- Size
- Color
- Season
- Review Rating
- Subscription Status
- Shipping Type
- Discount Applied
- Previous Purchases
- Payment Method
- Purchase Frequency
- Promo Code Used

---

# 🔄 Project Workflow

```text
Raw Dataset
      │
      ▼
Python Data Cleaning
      │
      ▼
Exploratory Data Analysis (EDA)
      │
      ▼
Feature Engineering
      │
      ▼
PostgreSQL Database
      │
      ▼
SQL Business Analysis
      │
      ▼
Power BI Dashboard
      │
      ▼
Business Insights
      │
      ▼
Business Recommendations
```

---

# 🛠 Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Data Cleaning & EDA |
| Pandas | Data Manipulation |
| NumPy | Numerical Operations |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| PostgreSQL | Database Management |
| SQL | Business Analysis |
| Power BI | Interactive Dashboard |
| Gamma AI | Project Report |

---

# 🐍 Exploratory Data Analysis (EDA)

EDA was performed to understand customer purchasing behavior and prepare the dataset for business analysis.

### Data Preparation

- Loaded dataset using Pandas
- Explored dataset structure
- Handled missing values
- Checked duplicate records
- Renamed columns
- Created new analytical features
- Removed redundant columns
- Exported cleaned dataset to PostgreSQL

### EDA Highlights

- Purchase Amount Distribution
- Revenue by Product Category
- Average Purchase by Gender
- Customer Age Distribution
- Revenue by Age Group
- Sales by Season
- Subscription Status Analysis
- Payment Method Analysis
- Shipping Type Analysis
- Review Rating Distribution
- Correlation Heatmap
- Top Revenue Locations

---

# 🗄 SQL Business Analysis

Business questions answered using SQL include:

- Total revenue by gender
- High-spending customers using discounts
- Top-rated products
- Shipping type comparison
- Subscriber vs Non-subscriber spending
- Products with highest discount usage
- Customer segmentation
- Top-selling products within categories
- Repeat buyer subscription analysis
- Revenue contribution by age group

Advanced SQL concepts used:

- Aggregate Functions
- CASE Statements
- Common Table Expressions (CTEs)
- Window Functions
- Subqueries
- GROUP BY
- ORDER BY
- Joins
- Filtering

---

# 📈 Power BI Dashboard

The interactive dashboard provides real-time insights into customer purchasing behavior.

### KPI Cards

- 👥 Number of Customers
- 💰 Average Purchase Amount
- ⭐ Average Review Rating

### Interactive Slicers

- Subscription Status
- Gender
- Category
- Shipping Type

### Dashboard Visualizations

- Customer Distribution by Subscription Status
- Revenue by Category
- Sales by Category
- Revenue by Age Group
- Sales by Age Group

### Dashboard Features

- Interactive filtering
- Dynamic KPI updates
- Business-focused visualizations
- Clean and responsive layout

---

# 💡 Key Insights

- Clothing generates the highest revenue among all product categories.
- Young Adult customers contribute the largest share of revenue.
- Customer spending is relatively consistent across genders.
- Most customers are non-subscribers.
- Standard shipping is the most preferred delivery method.
- Customer review ratings are generally positive.
- Medium-value purchases dominate customer transactions.
- Discount usage significantly influences purchasing behavior.
- Repeat customers contribute a substantial portion of sales.
- Revenue varies across customer demographics and product categories.

---

# 🚀 Business Recommendations

- Increase subscription adoption through exclusive member benefits.
- Launch loyalty programs for repeat customers.
- Promote high-performing product categories.
- Improve performance of low-selling categories.
- Optimize shipping strategies based on customer preferences.
- Personalize marketing campaigns using customer demographics.
- Increase customer retention through targeted offers.
- Monitor product ratings to improve customer satisfaction.
- Expand successful product categories.
- Continue tracking purchasing trends for better forecasting.

---

# 📁 Repository Structure

```text
customer-shopping-behavior-analysis/
│
├── data/
│   ├── raw/
│   └── cleaned/
│
├── python/
│   └── retail_analysis.ipynb
│
├── sql/
│   └── customer_analysis.sql
│
├── powerbi/
│   └── Customer_Behavior_Dashboard.pbix
│
├── reports/
│   └── Customer_Shopping_Behavior_Analysis.pdf
│
├── images/
│   ├── dashboard.png
│   ├── eda/
│   └── sql_results/
│
├── README.md
├── requirements.txt
└── LICENSE
```

---
# ▶️ How to Run

1. Clone this repository.

```bash
git clone https://github.com/zeeshanptn/customer-shopping-behavior-analysis.git
```

2. Install Python dependencies.

```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook.

```bash
jupyter notebook
```

4. Run the Python notebook for data cleaning and EDA.

5. Import the cleaned dataset into PostgreSQL.

6. Execute the SQL queries.

7. Open the `.pbix` file in Power BI Desktop to explore the interactive dashboard.

---

# 👨‍💻 Author

**Zeeshan Ahmad**

B.Tech Computer Science Engineering

- GitHub: https://github.com/zeeshanptn
- LinkedIn: https://www.linkedin.com/in/zeeshan-ahmad-b18551333/

---

⭐ If you found this project useful, consider giving the repository a **Star**.
