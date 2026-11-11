# Oasis Infobyte Data Analytics Internship (OIBSIP)

## 📌 Project Overview
This repository contains projects completed as part of the Data Analytics Internship at Oasis Infobyte (OIBSIP). It covers Exploratory Data Analysis, Customer Segmentation, and Professional Data Cleaning.

---

## Task 1: Retail Sales Data Analysis

### 📌 Project Overview
Performs an **Exploratory Data Analysis (EDA)** on a retail sales dataset to uncover patterns in customer behavior, sales trends over time, product category performance, and correlation between variables.

### 📊 Dataset Information
- **Rows:** 1,000
- **Columns:** 9 (Date, Customer ID, Gender, Age, Product Category, Quantity, Price per Unit, Total Amount)
- **Missing Values:** None (Clean dataset)

### 🛠️ Tools & Libraries Used
- **Python** (Programming Language)
- **Pandas & NumPy** (Data Manipulation & Numerical Operations)
- **Matplotlib & Seaborn** (Data Visualization)
- **Jupyter Notebook** (Development Environment)

### 🔍 Key Insights & Findings
1. **Sales Trends:** Sales fluctuate throughout the year, peaking in **May** and **Q4 (October & December)**. September recorded the lowest sales.
2. **Customer Demographics:** 
   - Customer split by gender is nearly equal (510 females and 490 males).
   - The **46–55 age group** has the highest number of customers, whereas the **18–25 age group** spends the highest amount per order (approx. $500).
3. **Product Categories:** 
   - **Electronics** and **Clothing** generate the highest revenue (approx. $157k and $156k respectively).
   - **Beauty** generates the lowest revenue (approx. $144k) but has steady transaction counts.
4. **Correlation:** Total Amount is strongly correlated with Price per Unit ($0.85$), while Customer Age has little to no impact on spending amount.

### 💡 Business Recommendations
1. **Stock Preparation:** Increase inventory and run promotional campaigns ahead of peak months (May, October, December).
2. **Promote Beauty Category:** Introduce bundle offers or discounts on Beauty products combined with Clothing or Electronics to boost turnover.
3. **Targeted Marketing:** Focus marketing campaigns on the 18–25 age group to maximize average order value, as they spend the most per transaction.

## 🚀 How to Run the Code
1. Clone this repository or download the files.
2. Ensure you have Python and Jupyter Notebook installed along with required libraries (`pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`).
3. Open the respective `.ipynb` notebooks in Jupyter Notebook and run the cells.

---

## Task 2: Customer Segmentation Analysis (RFM)

### Project Objective
The objective of this project is to apply K-Means clustering algorithms to segment an e-commerce company's customer base into distinct groups based on purchasing behaviour (RFM Analysis), enabling targeted marketing strategies.

### Tech Stack Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-Learn (StandardScaler, KMeans)
- Jupyter Notebook (VS Code)

### Steps Performed
1. Loaded and inspected the e-commerce retail dataset.
2. Performed exploratory data analysis and checked descriptive statistics.
3. Extracted RFM (Recency, Frequency, Monetary) features for each unique customer.
4. Normalised features using `StandardScaler`.
5. Applied the Elbow Method to determine the optimal number of clusters ($K=3$).
6. Performed K-Means Clustering and visualised customer segments using scatter plots.
7. Profiled each cluster and generated business insights & marketing recommendations.

---

## Task 3: Data Cleaning and Preparation

### Project Objective
Demonstrate professional-level data cleaning skills by taking a messy dataset, producing a data quality report, handling missing values, removing duplicates, normalising formatting, detecting outliers, correcting data types, and producing a "Before vs After" summary.

### Tech Stack Used
- Python
- Pandas, NumPy
- Jupyter Notebook (VS Code)

### Steps Performed
1. **Data Quality Report:** Checked null values, duplicate rows, data types, and value range anomalies.
2. **Missing Data Handling:** Imputed missing values using appropriate strategies (median/mode) with proper justifications.
3. **Duplicate Removal:** Identified and removed duplicate rows from the dataset.
4. **Standardisation:** Normalised formatting (text capitalization, datetime conversion).
5. **Outlier Detection:** Used the IQR method to detect outliers in numeric columns.
6. **Data Type Correction:** Ensured all columns have correct data types.
7. **Summary & Export:** Produced a "Before vs After" summary table and saved the cleaned dataset to `cleaned_retail_sales_dataset.csv`.

---

## Task 4: Sentiment Analysis Model

### Project Objective
Build a machine learning model that classifies the sentiment of text data into positive, negative, or neutral categories, providing insights into customer feedback and public opinion.

### Tech Stack Used
- Python (Programming Language)
- Pandas, NumPy (Data Manipulation)
- NLTK (Text Preprocessing & Lemmatisation)
- Scikit-Learn (TF-IDF Vectorizer, Naive Bayes, Logistic Regression)
- Matplotlib, Seaborn, WordCloud (Data Visualisation)
- Jupyter Notebook (VS Code)

### Steps Performed
1. **Loaded & Inspected Dataset:** Loaded the Amazon Fine Food Reviews dataset, mapped ratings to sentiments (Positive, Neutral, Negative), and analyzed class distributions.
2. **Text Preprocessing Pipeline:** Cleaned text data by lowercasing, removing punctuation/stopwords, tokenising, and applying lemmatisation using NLTK.
3. **Feature Extraction:** Implemented **TF-IDF Vectorizer** to convert text documents into numerical feature vectors.
4. **Model Training & Evaluation:** Split data (80/20) and trained two classifiers (**Multinomial Naive Bayes** and **Logistic Regression**), evaluating them using accuracy, classification report, and confusion matrix.
5. **Visualisations:** Generated sentiment distribution bar charts and WordClouds for each sentiment class.
6. **Error Analysis & Conclusion:** Examined misclassified examples and highlighted real-world applications for automated customer feedback monitoring.

---

---

## Level 2 - Task 1: Predicting House Prices with Linear Regression

### Project Objective
Build and evaluate a linear regression model that predicts house prices based on various features. Developed end-to-end skills from data cleaning and exploratory data analysis (EDA) through to model training, evaluation, and coefficient interpretation.

### Tech Stack Used
- Python (Programming Language)
- Pandas, NumPy (Data Manipulation & Math)
- Scikit-Learn (California Housing Dataset, LinearRegression, Ridge, Metrics)
- Matplotlib, Seaborn (Data Visualisation & Heatmaps)
- Jupyter Notebook (VS Code)

### Steps Performed
1. **Loaded & Inspected Dataset:** Loaded the California Housing dataset from Scikit-learn, checked for null values, and viewed descriptive statistics.
2. **Exploratory Data Analysis (EDA):** Analyzed the distribution of the target variable (Median House Value) using histograms.
3. **Feature Selection & Correlation:** Computed the correlation matrix and visualized feature relationships using a correlation heatmap.
4. **Model Training:** Split data into 80/20 train/test sets and trained a **Linear Regression** model.
5. **Model Evaluation:** Evaluated performance using Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² Score.
6. **Visualisations:** Placed actual vs. predicted prices scatter plots and residual plots to verify model assumptions.
7. **Coefficient Analysis:** Analyzed feature coefficients to identify which variables had the highest positive/negative impact on house prices.
8. **Bonus Regularisation:** Compared Linear Regression against a Ridge regularised model.

---

**Author:** Yasmeen Akhter
