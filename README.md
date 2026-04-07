# 🏠 Harbour & Home Direct – Dispatch Delays & Returns Analysis

## 📌 Project Overview

This project analyses order and return activity for a UK-based e-commerce homewares retailer.  
The objective is to identify key drivers of revenue, dispatch delays, and product returns, and provide actionable business recommendations.

---

## 🎯 Objectives

- Analyse sales performance by channel and product category  
- Identify patterns in dispatch delays  
- Evaluate refund trends across products  
- Determine whether delayed orders drive returns  
- Provide business recommendations for operational improvement  

---

## 🛠️ Tools & Technologies

- Python (Pandas, NumPy)
- Data Cleaning & Transformation
- Exploratory Data Analysis (EDA)
- Matplotlib (Data Visualisation)
- Jupyter Notebook

---

## 📂 Dataset Description

The dataset includes:

- **order_lines.csv** → transactional order data  
- **customers_lookup.csv** → customer information  
- **products_lookup.csv** → product and category data  
- **returns.csv** → return and refund records  

---

## 🧹 Data Cleaning & Preparation

Key steps performed:

- Standardised column names and text values  
- Removed duplicate records  
- Converted data types (dates, numeric fields)  
- Handled missing values using business logic  
- Standardised categorical values (e.g., region names)  
- Created calculated fields:
  - `line_revenue`
  - `late_dispatch_flag`

---

## 📊 Key Insights

### 💰 Revenue Performance
- Web channel generated the highest revenue  
- Home Storage and Lighting were the top-performing categories  

### 🚚 Dispatch Delays
- Most delays occurred in London and South East regions  
- Indicates potential operational bottlenecks  

### 💸 Refund Analysis
- Highest refunds came from Home Storage and Lighting  
- Suggests possible product quality or fulfilment issues  

### 🔥 Critical Insight
- **Delayed orders had ~92% return rate**
- **On-time orders had 0% return rate**

👉 Dispatch delays are the primary driver of returns

---

## 📈 Visualisations

(Add screenshots here if possible)

---

## ✅ Business Recommendations

1. Improve dispatch and fulfilment processes  
2. Investigate high-refund product categories  
3. Focus on high-performing sales channels  
4. Improve product data quality and classification  
5. Enhance customer communication for delivery expectations  

---

## 🧠 Conclusion

This analysis highlights that operational inefficiencies in dispatch significantly impact customer satisfaction and return rates.  
Reducing delays should be the top priority to protect revenue and improve customer experience.

---

## 📌 Author

**Jumma Mohammad Teli**  
- Data Analyst | Python | SQL | Power BI  
- [LinkedIn](https://www.linkedin.com/in/jumma-mohammad/)  
- [GitHub](https://github.com/jumma786)
