# Retail Sales Data Analysis - Oasis Infobyte Internship (Level 1, Task 1)

## 📌 Project Overview
This project is part of the Data Analytics Internship at Oasis Infobyte (OIBSIP). It performs an **Exploratory Data Analysis (EDA)** on a retail sales dataset to uncover patterns in customer behavior, sales trends over time, product category performance, and correlation between variables.

---

## 📊 Dataset Information
- **Rows:** 1,000
- **Columns:** 9 (Date, Customer ID, Gender, Age, Product Category, Quantity, Price per Unit, Total Amount)
- **Missing Values:** None (Clean dataset)

---

## 🛠️ Tools & Libraries Used
- **Python** (Programming Language)
- **Pandas & NumPy** (Data Manipulation & Numerical Operations)
- **Matplotlib & Seaborn** (Data Visualization)
- **Jupyter Notebook** (Development Environment)

---

## 🔍 Key Insights & Findings
1. **Sales Trends:** Sales fluctuate throughout the year, peaking in **May** and **Q4 (October & December)**. September recorded the lowest sales.
2. **Customer Demographics:** 
   - Customer split by gender is nearly equal (510 females and 490 males).
   - The **46–55 age group** has the highest number of customers, whereas the **18–25 age group** spends the highest amount per order (approx. $500).
3. **Product Categories:** 
   - **Electronics** and **Clothing** generate the highest revenue (approx. $157k and $156k respectively).
   - **Beauty** generates the lowest revenue (approx. $144k) but has steady transaction counts.
4. **Correlation:** Total Amount is strongly correlated with Price per Unit ($0.85$), while Customer Age has little to no impact on spending amount.

---

## 💡 Business Recommendations
1. **Stock Preparation:** Increase inventory and run promotional campaigns ahead of peak months (May, October, December).
2. **Promote Beauty Category:** Introduce bundle offers or discounts on Beauty products combined with Clothing or Electronics to boost turnover.
3. **Targeted Marketing:** Focus marketing campaigns on the 18–25 age group to maximize average order value, as they spend the most per transaction.

---

## 🚀 How to Run the Code
1. Clone this repository or download the files.
2. Ensure you have Python and Jupyter Notebook installed along with required libraries (`pandas`, `numpy`, `matplotlib`, `seaborn`).
3. Open `YasmeenAkhter_Task1.ipynb` in Jupyter Notebook and run the cells.

---
**Author:** Yasmeen Akhter

## Task 2: Customer Segmentation Analysis (RFM)

### Project Objective
The objective of this project is to apply K-Means clustering algorithms to segment an e-commerce company's customer base into distinct groups based on purchasing behaviour (RFM Analysis), enabling targeted marketing strategies.

### Tech Stack Used
* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-Learn (StandardScaler, KMeans)
* Jupyter Notebook (VS Code)

### Steps Performed
1. Loaded and inspected the e-commerce retail dataset.
2. Performed exploratory data analysis and checked descriptive statistics.
3. Extracted RFM (Recency, Frequency, Monetary) features for each unique customer.
4. Normalised features using `StandardScaler`.
5. Applied the Elbow Method to determine the optimal number of clusters ($K=3$).
6. Performed K-Means Clustering and visualised customer segments using scatter plots.
7. Profiled each cluster and generated business insights & marketing recommendations.
