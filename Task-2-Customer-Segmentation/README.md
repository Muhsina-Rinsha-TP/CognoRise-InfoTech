# Customer Segmentation Analysis using K-Means

## Project Overview
This project was completed as part of my Data Science and Machine Learning internship at **CognoRise InfoTech**.

The objective is to segment mall customers based on their age, annual income and spending score using the K-Means Clustering algorithm. The analysis helps identify different customer groups and recommend suitable marketing strategies for each segment.

## Dataset
- **Dataset:** Mall Customer Segmentation Data
- **Source:** Kaggle
- **Total Records:** 200 customers
- **Features:** CustomerID, Gender, Age, Annual Income and Spending Score.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

1. **Data Loading and Inspection:** Loaded the dataset and examined its structure, data types and statistical summary.
2. **Data Cleaning:** Checked missing values, duplicate records, valid ranges and outliers.
3. **Exploratory Data Analysis:** Analysed customer demographics, income and spending behaviour using visualisations.
4. **Feature Selection and Scaling:** Selected Age, Annual Income and Spending Score and applied StandardScaler.
5. **Optimal Cluster Selection:** Used the Elbow Method and Silhouette Score to determine the number of clusters.
6. **Model Building:** Applied K-Means clustering to group customers.
7. **Cluster Visualisation:** Visualised customer segments using scatter plots, PCA and 3D plots.
8. **Customer Profiling:** Analysed each cluster and developed marketing recommendations.

## Model Results

- **Algorithm:** K-Means Clustering
- **Optimal Number of Clusters:** 6
- **Silhouette Score:** 0.427
- **Number of Customers:** 200

The final model identified six customer segments based on age, annual income and spending score.

## Customer Segments

The analysis identified different customer groups, including:

- Affluent Low-Spending Customers
- Older Moderate-Spending Customers
- Young High-Spending Customers
- Premium VIP Customers
- Low-Income, Low-Spending Customers

Different marketing strategies were suggested for each segment, including personalised recommendations, loyalty rewards, discounts and premium services.

## Visualisations

The project includes:
- Age, income and spending score distributions.
- Gender-wise customer analysis.
- Correlation heatmap and pairplot.
- Elbow Method and Silhouette Score graphs.
- Customer clusters based on income and spending score.
- PCA and 3D cluster visualisations.
- Customer segment profiles.

All generated visualisations are available in the `outputs` folder.

## Project Structure

```text
Task-2-Customer-Segmentation/
│
├── customer_segmentation.ipynb
├── Mall_Customers.csv
├── outputs/
│   ├── 01_distributions.png
│   ├── 02_by_gender.png
│   ├── 03_correlation.png
│   ├── 04_pairplot.png
│   ├── 05_elbow_silhouette.png
│   ├── 06_clusters_income_spending.png
│   ├── 07_clusters_pca.png
│   ├── 08_clusters_3d.png
│   ├── 09_cluster_profiles.png
│   └── customers_with_segments.csv
│
└── README.md
```

## How to Run the Project

1. Clone this repository.
2. Open the project folder in VS Code.
3. Install the required libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

4. Open `customer_segmentation.ipynb`.
5. Run all notebook cells.

Make sure `Mall_Customers.csv` is in the same folder as the notebook.

## Limitations

- The dataset contains only 200 customer records.
- The spending score is assigned by the mall and does not represent actual transaction data.
- K-Means is sensitive to feature scaling and initial cluster positions.
- The identified customer segments represent the available dataset and may change with new customer data.

## Conclusion

This project demonstrates how unsupervised machine learning can be used to identify meaningful customer segments. By applying K-Means clustering and analysing customer profiles, businesses can better understand customer behaviour and develop targeted marketing strategies.