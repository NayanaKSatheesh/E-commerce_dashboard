# E-commerce_dashboard
Data analysis project of data from e-commerce platforms. The project involves understanding the data that you are working with, data cleaning, sql queries and an interactive dashboard made using powerBI


## 🔍 Overview

This project analyzes customer shopping behavior using transactional data to uncover patterns in spending, customer segmentation, and product performance.

It demonstrates an end-to-end data analytics workflow including:

* Data cleaning and preprocessing (Python)
* Exploratory Data Analysis (EDA)
* SQL-based business analysis
* Interactive dashboard creation (Power BI)

---

 📁 Dataset

Records: 3,900 transactions
Columns: 18 features

Key Features:

* 👤 Customer: Age, Gender, Location, Subscription Status
* 🛍️ Purchase: Item, Category, Amount, Season, Size, Color
* 📊 Behavior: Discounts, Ratings, Purchase Frequency, Shipping Type

Data Cleaning:

* Handled missing values in *Review Rating*
* Standardized column names
* Removed redundant fields

---

 🛠️ Tech Stack

| Tool                   | Purpose                       |
| ---------------------- | ----------------------------- |
| Python (Pandas, NumPy) | Data cleaning & preprocessing |
| Matplotlib / Seaborn   | Data visualization            |
| PostgreSQL             | Data querying & analysis      |
| Power BI               | Dashboard creation            |
| Google colab           | Development environment       |

---

⚙️ Project Steps

 1️⃣ Data Preparation (Python)

* Loaded dataset using Pandas
* Checked structure and summary statistics
* Renamed columns (snake_case format)

 2️⃣ Data Cleaning

* Imputed missing values using median
* Removed duplicate/redundant columns
* Ensured consistency

 3️⃣ Feature Engineering

* Created age groups
* Derived purchase frequency metrics

4️⃣ Exploratory Data Analysis

* Customer demographics analysis
* Spending trends across categories
* Discount and rating insights

5️⃣ SQL Analysis

Performed business-driven queries such as:

* Revenue by gender
* Top-rated products
* Subscriber vs non-subscriber behavior
* Revenue by age group

---

 📊 Dashboard

Power BI Dashboard Highlights:

* Revenue trends & KPIs
*  Customer segmentation
*  Product performance
*  Shipping behavior insights



 Key Insights

* Loyal customers contribute significantly to revenue
* Discounts influence purchase behavior but need optimization
* Certain product categories consistently outperform others


---

 Business Recommendations

1. Improve subscription benefits
2. Introduce customer loyalty programs
3. Optimize discount strategies
4. Focus marketing on high-value segments

---
How to Run
1. Open project.ipynb
2. Upload customer_shopping_behavior.csv
3. Install Dependencies:
  pip install pandas numpy matplotlib seaborn psycopg2
4.Open Dashboard
  * Launch `.pbix` file in Power BI
  * Refresh dataset

 Future Improvements:

* Add predictive modeling (customer churn / sales forecasting)
* Automate ETL pipeline


