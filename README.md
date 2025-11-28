# 📊 Marketing Campaign Analysis

Understanding customer behavior to improve campaign acceptance and revenue strategy

![Customer Segment Insight](images/shap_summary.png)

## 🧾 Project Overview

This project analyzes customer profiles and purchasing behavior to identify
which segments are most likely to accept marketing campaigns.  
The study includes:

- Data quality check & preprocessing
- Exploratory Data Analysis
- Feature engineering
- Predictive modeling using Random Forest & Logistic Regression
- SHAP interpretability
- Business insights and recommendations

## 📁 Repository Structure

Marketing-Campaign-Analysis/

│

├── dataset/               # Raw & cleaned dataset

├── notebooks/             # Jupyter notebooks used for analysis & modeling

├── images/                # Visualization outputs (EDA, SHAP, etc.)

├── report/                # Insight summary & final PDF report

├── requirement.txt        # Project dependencies

└── README.md              # Project documentation


## 🔑 Key Insights

✔️ Customers who spent **> $1,000** are significantly more likely to accept campaigns  
✔️ **Wines** generate the highest revenue among all products  
✔️ Best performing channel: **Store purchases**  
✔️ Underperforming channel: **Catalog purchases**  
✔️ Customers in **Mexico & Spain** show the highest campaign acceptance rate  


![Best Products](images/best_products.png)

## 🤖 Model Performance

| Model                   | ROC-AUC |
|------------------------|--------|
| Logistic Regression    | 0.74   |
| Random Forest          | 0.901   ✔️ Best model

## 🧠 What Drives Campaign Acceptance?

![SHAP](images/shap_summary.png)

Top feature impact:
- Recency and Customer Tenure have the strongest influence on acceptance

## 🚀 Business Recommendations

- Fokuskan campaign pada pelanggan dengan pengeluaran > $1,000
- Buat program loyalitas untuk pelanggan lama (high tenure)
- Kurangi biaya campaign via catalog (low conversion)
- Optimalkan channel store & web purchases

