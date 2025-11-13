# 🛍️ Shoplyze — Customer Purchase Behaviour Analytics

> **Shoplyze** is a data-driven project that uncovers how customers shop, what influences their spending, and how their behavior can predict future trends.  
> Using **Python**, **Machine Learning**, and **Power BI**, it analyzes customer transactions to generate insights on loyalty, churn, and purchasing patterns.

---

## 🧠 Project Overview

**Objective:**  
Understand and predict customer purchase behavior using e-commerce data — from raw transactions to actionable business insights.

**Key Goals:**
- Identify **high-value and loyal customers**
- Discover **spending patterns** and **frequency trends**
- Segment customers using **RFM (Recency, Frequency, Monetary)** metrics
- Build **predictive models** for churn and engagement
- Create a **Power BI dashboard** for interactive business insights

---

## 🧩 Tech Stack

| Layer | Tools & Technologies |
|-------|----------------------|
| **Data Cleaning & Processing** | Python, Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn, Plotly |
| **Modeling & Analytics** | Scikit-learn, SciPy |
| **Dashboarding** | Power BI Desktop (.pbit) |
| **Documentation** | Jupyter Notebook, HTML Reports |

---

## ⚙️ Project Workflow

```
graph TD
A[Raw Customer Data (CSV)] --> B[Data Cleaning]
B --> C[Feature Engineering (RFM, CLV, Cohorts)]
C --> D[Exploratory Data Analysis]
D --> E[Machine Learning Models (Clustering, Churn)]
E --> F[Insights & Recommendations]
F --> G[Power BI Dashboard (Shoplyze.pbit)]
```
---

## 📁 Folder Structure

```
Shoplyze/
│
├── notebooks/                     # All Jupyter Notebooks
│   ├── 00_dataset_download.ipynb
│   ├── 01_data_exploration.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_feature_engineering.ipynb
│   ├── 04_eda_analysis.ipynb
│   └── 05_ml_models.ipynb
│
├── dataset/
│   ├── raw/                       # Original data (E-commerce Customer Behavior)
│   └── processed/                 # Cleaned / ML-ready / Scaled datasets
│
├── outputs/
│   └── figures/                   # Saved charts and analysis visuals
│
├── dashboard/
│   ├── shoplyze_dashboard.pbit    # Power BI template
│   └── shoplyze_summary.pdf       # Static exported report
│
├── requirements.txt
├── .gitignore
└── README.md
```
---

## 🧾 Data Source

The dataset represents anonymized e-commerce customer transactions containing:

- Customer ID
- Order date and frequency
- Purchase amount
- Device and region
- Channel (web / mobile)

---

## 🧮 Analytical Approach

### 1️⃣ Data Cleaning

- Handle missing and duplicate values
- Standardize data types and date formats
- Filter relevant columns (customer ID, purchase details)

### 2️⃣ Feature Engineering

- Create RFM (Recency, Frequency, Monetary) metrics
- Compute Customer Lifetime Value (CLV)
- Derive tenure, purchase frequency, and AOV (Average Order Value)
- Encode categorical variables and scale numerical features

### 3️⃣ Exploratory Data Analysis
- Distribution of spending and order frequency
- Retention and repeat purchase patterns
- RFM segmentation visualization
- Correlation heatmaps & cohort analysis

### 4️⃣ Machine Learning Models

- K-Means Clustering: customer segmentation
- Classification Models: churn prediction (optional)
- Evaluation: silhouette score, feature importance

### 5️⃣ Dashboard & Insights

- Built in Power BI
Shows:
- Top customer segments
- Revenue contribution
- Churn probability
- RFM segmentation summary
- Monthly and regional sales performance

---

## 💡 Key Insights

- 🧩 Top 20% of customers generate over 65% of total revenue
- 📆 Customers with shorter recency (<30 days) show 3× higher retention
- 💸 RFM segmentation highlights four key groups:
- Champions, Loyal Customers, At Risk, Lost
- 🔍 Clustering revealed clear behavioral groupings based on order frequency and spend value

---

>[Click here to see the analysis](https://github.com/sharmap21/git-demo/blob/main/dashboard/purchase_behaviour_analysis.pdf)


---

## 🚀 How to Run This Project

```
git clone https://github.com/<your-username>/<your-repo-name>.git
cd Shoplyze

python -m venv venv
source venv/bin/activate        # Mac / Linux
venv\Scripts\activate           # Windows

pip install -r requirements.txt

jupyter notebook
# Open 00_dataset_download.ipynb → run in order

Open Dashboard
- Launch Power BI Desktop
- Open dashboard/shoplyze_dashboard.pbit
- Connect it to dataset/processed/scaled_ml_data.csv
- Interact with visuals (filters, slicers, trends)
```

---

## 🧠 Learnings

- Data preprocessing and feature engineering for real-world datasets
- RFM modeling and customer segmentation
- Scaling and clustering for marketing analytics
- Power BI storytelling and dashboard design
- End-to-end data project workflow management

---




