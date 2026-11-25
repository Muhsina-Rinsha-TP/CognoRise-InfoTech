# CognoRise InfoTech – Data Science Internship

## Internship Overview

This repository contains the projects completed as part of my 30-day Data Science Internship at CognoRise InfoTech.

The internship focuses on developing practical skills in Python, data analysis, exploratory data analysis, machine learning, clustering, forecasting and data visualisation.

## Internship Projects

### Task 1: Netflix Content Analysis

**Project Overview**

This project focuses on analysing the Netflix content dataset to identify patterns, trends and insights related to movies and TV shows.

**Objectives**
- Analyse the distribution of Movies and TV Shows.
- Identify the top countries contributing to Netflix content.
- Explore popular genres and their trends.
- Analyse movie durations and TV Show seasons.
- Perform statistical analysis to identify relationships in the dataset.

**Technologies Used**
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook

**Key Findings**
- Movies represent approximately 69.6% of the Netflix catalogue, while TV Shows account for 30.4%.
- The United States contributes the highest number of titles, followed by India and the United Kingdom.
- International Movies is the most frequently listed genre, followed by Dramas and Comedies.
- The average movie duration is approximately 99.6 minutes.
- TV Shows have an average of 1.8 seasons.

**Statistical Analysis**
- Chi-square test
- Spearman correlation
- Mann-Whitney U test

**Project Files:** [Task 1 – Netflix Content Analysis](./Task-1-Netflix-Content-Analysis/)

**Standalone Repository:** [Netflix Content Analysis](https://github.com/Muhsina-Rinsha-TP/netflix-content-analysis)

---

### Task 2: Customer Segmentation Analysis

**Project Overview**

This project focuses on customer segmentation using K-Means clustering to identify different customer groups based on their age, annual income and spending score.

The objective is to help businesses understand customer behaviour and develop targeted marketing strategies.

**Objectives**
- Explore customer demographics and spending behaviour.
- Perform exploratory data analysis.
- Apply feature scaling using StandardScaler.
- Determine the optimal number of clusters using the Elbow Method and Silhouette Score.
- Implement K-Means clustering.
- Visualise and interpret customer segments.
- Develop marketing recommendations for each segment.

**Dataset**
- Dataset: Mall Customers Dataset
- Total Records: 200
- Features: CustomerID, Gender, Age, Annual Income and Spending Score.

**Technologies Used**
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

**Project Workflow**
1. Data Loading and Inspection
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Selection and Scaling
5. Optimal Cluster Selection
6. K-Means Clustering
7. Cluster Visualisation
8. Customer Segment Profiling
9. Marketing Recommendations

**Key Results**
- Identified six distinct customer segments using K-Means clustering.
- Achieved a Silhouette Score of approximately 0.427.
- Used Elbow Method and Silhouette Score to evaluate the clustering results.
- Developed customer profiles and marketing recommendations for each segment.

**Customer Segments**
1. Affluent Low-Spending Customers
2. Older Moderate-Spending Customers
3. Young High-Spending Customers
4. Premium VIP Customers
5. Young Moderate-Spending Customers
6. Low-Income Low-Spending Customers

**Project Files:** [Task 2 – Customer Segmentation](./Task-2-Customer-Segmentation/)

**Standalone Repository:** [Customer Segmentation Analysis](https://github.com/Muhsina-Rinsha-TP/customer-segmentation-analysis)

---

### Task 3: Retail Sales Forecasting

**Project Overview**

This project focuses on retail sales forecasting by analysing historical sales data to identify trends, seasonal patterns and factors influencing retail sales.

The project involves exploratory data analysis, visualisation, forecasting and model comparison to understand retail sales patterns and predict future sales.

**Objectives**
- Analyse historical retail sales data.
- Identify overall sales trends and patterns.
- Explore seasonal variations in sales.
- Analyse the impact of holidays on retail sales.
- Examine sales patterns across different store types and departments.
- Investigate the influence of external factors on sales.
- Compare forecasting models.
- Evaluate actual sales against predicted sales.
- Analyse feature importance and forecasting errors.

**Dataset**
- Retail sales dataset.
- Training data: `train.csv.zip`
- Features data: `features.csv.zip`
- Store information: `stores.csv`
- Test predictions: `test_predictions.csv`

**Project Workflow**
1. Data Loading and Inspection
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Total Sales Trend Analysis
5. Seasonality Analysis
6. Holiday Effect Analysis
7. Store Type and Size Analysis
8. External Factors Analysis
9. Forecasting Model Comparison
10. Actual vs Forecast Analysis
11. Feature Importance Analysis
12. Error Analysis

**Visualisations and Outputs**

The project includes the following visualisations:

- Retail Sales Dashboard
- Total Sales Trend
- Seasonality Analysis
- Holiday Effect Analysis
- Store Type and Size Analysis
- Top Stores and Departments
- External Factors Analysis
- Model Comparison
- Actual vs Forecast
- Feature Importance
- Error Analysis

**Project Files:** [Task 3 – Retail Sales Forecasting](./Task-3-Retail-Sales-Forecasting/)

---

## Repository Structure

```text
CognoRise-InfoTech/
│
├── Task-1-Netflix-Content-Analysis/
│   ├── README.md
│   ├── netflix_content_analysis.ipynb
│   ├── netflix_titles.csv
│   └── outputs/
│
├── Task-2-Customer-Segmentation/
│   ├── README.md
│   ├── customer_segmentation.ipynb
│   ├── Mall_Customers.csv
│   └── outputs/
│
├── Task-3-Retail-Sales-Forecasting/
│   ├── retail_sales_forecasting.ipynb
│   ├── train.csv.zip
│   ├── features.csv.zip
│   ├── stores.csv
│   ├── test_predictions.csv
│   └── outputs/
│       ├── 00_dashboard.png
│       ├── 01_total_sales_trend.png
│       ├── 02_seasonality.png
│       ├── 03_holiday_effect.png
│       ├── 04_store_type_size.png
│       ├── 05_top_stores_depts.png
│       ├── 06_external_factors.png
│       ├── 07_model_comparison.png
│       ├── 08_actual_vs_forecast.png
│       ├── 09_feature_importance.png
│       └── 10_error_analysis.png
│
├── .gitignore
└── README.md
```

## Internship Details

**Organization:** CognoRise InfoTech  
**Domain:** Data Science  
**Duration:** 30 Days  
**Internship Period:** 1 November 2026 – 1 December 2026

## Author

**Muhsina Rinsha T P**

[GitHub Profile](https://github.com/Muhsina-Rinsha-TP)
