# Oasis Infobyte Data Analytics Internship (OIBSIP)

## 📌 Project Overview
This repository contains projects completed as part of the Data Analytics Internship at Oasis Infobyte (OIBSIP). It covers Exploratory Data Analysis, Customer Segmentation, and Professional Data Cleaning.

---

## Level 1 - Task 1: Retail Sales Data Analysis

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

---

## Level 1 - Task 2: Customer Segmentation Analysis (RFM)

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

## Level 1 - Task 3: Data Cleaning and Preparation

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

## Level 1 - Task 4: Sentiment Analysis Model

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

## Level 2 - Task 2: Wine Quality Prediction

### Project Objective
Train and compare multiple classification models to predict the quality score of wine based on its physicochemical properties, handling class imbalance, feature engineering, stratification, and model evaluation.

### Tech Stack Used
- Python (Programming Language)
- Pandas, NumPy (Data Manipulation & Preprocessing)
- Scikit-Learn (Random Forest, SGD, SVC, StandardScaler, Metrics)
- Matplotlib, Seaborn (Data Visualisation & Correlation Heatmaps)
- Jupyter Notebook (VS Code)

### Steps Performed
1. **Loaded & Inspected Dataset:** Loaded the Wine Quality dataset, checked missing values, and analyzed the class distribution of quality scores.
2. **Exploratory Data Analysis (EDA):** Computed correlation matrices and visualized feature relationships using heatmaps.
3. **Class Imbalance & Feature Engineering:** Discussed class distribution challenges and converted multi-class quality scores into a binary classification problem (`Good` vs `Bad` wine) for better model stability.
4. **Stratified Train/Test Split & Scaling:** Split the dataset (80/20) using stratification to preserve class ratios and normalized features using `StandardScaler`.
5. **Model Training:** Trained three distinct classifiers: **Random Forest**, **Stochastic Gradient Descent (SGD)**, and **Support Vector Classifier (SVC)**.
6. **Model Evaluation:** Evaluated models using accuracy, classification reports (precision, recall, F1-score), and confusion matrices.
7. **Feature Importance:** Visualized the most impactful chemical properties using the Random Forest feature importance chart.
8. **Conclusion & Deployment:** Compared all models side-by-side and concluded that Random Forest is the most suitable choice for deployment due to its superior handling of non-linear features and stability.

---

## Level 2 - Task 3: Fraud Detection using Machine Learning

### Project Objective
Build a robust machine learning pipeline to detect fraudulent financial transactions from a heavily imbalanced dataset, addressing class imbalance as a core challenge using SMOTE and advanced evaluation metrics.

### Tech Stack Used
- Python (Programming Language)
- Pandas, NumPy (Data Manipulation & Preprocessing)
- Scikit-Learn (Logistic Regression, RandomForest, StandardScaler, Metrics)
- Imbalanced-Learn (SMOTE for oversampling)
- Matplotlib, Seaborn (Data Visualisation & ROC Curves)
- Jupyter Notebook (VS Code)

### Steps Performed
1. **Loaded & Inspected Dataset:** Loaded the Credit Card Fraud dataset and calculated the exact percentage of fraudulent transactions (~0.17%), highlighting severe class imbalance.
2. **Exploratory Data Analysis (EDA):** Analyzed transaction amounts using boxplots and log-scale distributions for fraud vs. non-fraud cases.
3. **Metric Discussion:** Explained why standard accuracy is deeply misleading for imbalanced datasets and why Precision, Recall, and AUC-ROC are necessary.
4. **SMOTE Oversampling & Stratified Split:** Split data using stratification and applied **SMOTE** on the training set to balance minority fraud cases.
5. **Model Training:** Trained **Logistic Regression** (with feature scaling and convergence optimization) and **Random Forest Classifier** on the resampled data.
6. **Model Evaluation:** Evaluated performance using Precision, Recall, F1-Score, Confusion Matrices, and AUC-ROC curves.
7. **Recall vs. Precision Trade-off:** Discussed why Recall is critical in fraud detection to prevent missed fraudulent transactions (False Negatives).
8. **Scalability Discussion:** Outlined cloud architectures (PySpark, Kafka, Kubernetes) for scaling the model to 1 million transactions per hour in production.

---

## Level 2 - Task 4: Unveiling the Android App Market (Google Play Store Analysis)

### Project Objective
Perform a comprehensive data analysis of the Google Play Store ecosystem by cleaning messy real-world data, exploring app categories, analyzing ratings and pricing trends, and conducting sentiment analysis on user reviews to derive actionable developer insights.

### Tech Stack Used
- Python (Programming Language)
- Pandas, NumPy (Data Cleaning & Manipulation)
- Matplotlib, Seaborn (Data Visualisation & Distribution Plots)
- NLTK VADER (Sentiment Analysis on User Reviews)
- Jupyter Notebook (VS Code)

### Steps Performed
1. **Loaded Datasets:** Loaded the Google Play Store apps dataset and the user reviews dataset separately.
2. **Data Cleaning:** Cleaned messy real-world strings (e.g., removing '+', ',', '$' signs in Installs and Price columns), handled null values, and removed duplicates.
3. **Category Analysis:** Visualized app distribution across categories to identify the most saturated app sectors on the Play Store.
4. **Ratings & Size Analysis:** Examined the overall distribution of app ratings and analyzed correlations between app reviews and user installs.
5. **Pricing Analysis:** Compared free vs. paid app distributions and evaluated monetisation trends.
6. **Sentiment Analysis on User Reviews:** Implemented NLTK's VADER Sentiment Intensity Analyzer to classify user reviews into Positive, Negative, and Neutral categories without training models.
7. **Developer Insights:** Concluded with 3 data-driven insights regarding app saturation, monetisation strategies, and the critical importance of monitoring user feedback to maintain high ratings.

---

## Level 2 - Task 5: Autocomplete and Autocorrect Data Analytics

### Project Objective
Analyze the efficiency and accuracy of autocomplete and autocorrect algorithms using NLP techniques, implementing a frequency-based n-gram model and an edit-distance correction system.

### Tech Stack Used
- Python (Programming Language)
- Pandas, NLTK (Corpus loading, tokenisation, n-grams)
- Pyspellchecker (Levenshtein distance spelling correction)
- Matplotlib, Seaborn (Frequency distributions)
- Jupyter Notebook (VS Code)

### Steps Performed
1. **Loaded Corpus & Preprocessed:** Downloaded the Project Gutenberg text corpus, tokenised words, converted to lowercase, and removed punctuation.
2. **Frequency Distribution:** Visualized the top 20 most frequent words in the text corpus using a Seaborn bar chart.
3. **Autocomplete Implementation:** Built a frequency-based bigram model and tested predictions across multiple input prefixes.
4. **Autocorrect Implementation:** Implemented edit-distance spelling correction on deliberately misspelled words, achieving high accuracy metrics.
5. **Evaluation & Comparison:** Discussed performance metrics (precision/recall) and highlighted core limitations of static n-gram models compared to production-grade neural keyboards like Gboard.

---

## 🚀 How to Run the Code
1. Clone this repository or download the files.
2. Ensure you have Python and Jupyter Notebook installed along with required libraries (`pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `imbalanced-learn`, `pyspellchecker`).
3. Open the respective `.ipynb` notebooks in Jupyter Notebook / VS Code and run the cells.

---
**Author:** Yasmeen Akhter
