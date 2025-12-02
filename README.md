# 📊 Data Analytics Portfolio: E-commerce and Financial Performance Modeling

## 🧑‍🎓 Overview

This portfolio showcases comprehensive analytical competency across two distinct domains: **E-commerce Customer Relationship Management (CRM)** and **Corporate Financial Valuation**. All analyses were executed in Python, leveraging key libraries like **Pandas** for data wrangling, **NumPy** for numerical operations, and **Plotly Express** for dynamic, interactive visualization.

The projects demonstrate proficiency in transforming raw transactional and financial data into **actionable Key Performance Indicators (KPIs)** and **strategic business intelligence** deliverables.

***

## 🛒 Project 1: E-commerce Customer & Product Profitability Analysis

This project focuses on the strategic assessment of a retail company's performance by examining customer value and product contribution.

### 🔬 Methodology and Analytical Techniques

* **Data Quality Assessment:** Initial cleansing involved handling **missing value imputation** (for Customer IDs) and mitigating **data anomalies** (non-positive quantities).
* **Time Series Analysis (Temporal Trend):** Analysis of the **Gross Merchandise Value (GMV)** over monthly periods to identify **secular trends** and **seasonal components**, critical for resource forecasting.
* **Customer Segmentation (RFM Model):** Implementation of the **Recency, Frequency, Monetary (RFM)** model using a hybrid approach (**quantile-based discretization** for Recency/Monetary and **controlled binning** for highly skewed Frequency data). This technique successfully isolates **actionable customer cohorts** (e.g., Champions, At Risk) to inform **targeted marketing campaigns**.
* **Product Performance (Pareto Principle):** Aggregate analysis of **SKU contribution** to total GMV to support **inventory optimization** and **product lifecycle management**.

### 🔗 Data Provenance

The raw transactional data for this analysis was accessed via the **Kaggle platform** and is publicly available for validation. This ensures the **reproducibility** of the analytical pipeline.

* **Dataset Link:** [[Online Retail Dataset Link]](https://www.kaggle.com/datasets/carrie1/ecommerce-data)

### 💻 Key Deliverables

1.  **Monthly GMV Trend Chart:** Visualization of the sales trajectory over the analyzed period.
2.  **Customer Cohort Distribution:** Bar chart illustrating the cardinality and proportional size of the **RFM customer segments**.
3.  **Top 10 High-Contribution SKUs:** Bar chart demonstrating which products drive the majority of the firm's revenue.

***

## 💰 Project 2: Corporate Financial Valuation and Performance

This project applies core financial principles to a dataset of major global companies to conduct comparative corporate analysis.

### 🔬 Methodology and Analytical Techniques

* **Advanced Feature Engineering:** Calculation of critical **Profitability Ratios** (e.g., **Net Profit Margin**) and **Efficiency Metrics** (e.g., **Asset Turnover Ratio**) from raw financial statements (Revenue, Profits, Assets).
* **Data Transformation:** Implemented a robust function to clean and convert complex **monetary string formats** (e.g., those containing 'M' or 'B' for scale) into uniform numeric values, ensuring the **integrity of quantitative analysis**.
* **Bivariate Correlation Analysis:** Utilized a **scatter plot** on **log-transformed variables** (Revenue and Market Value) to visualize and assess the underlying **linear correlation** between operational scale and investor capitalization. This is a crucial step in **investor valuation models**.
* **Geospatial Analysis:** Creation of a **Choropleth map** to visualize the **spatial distribution of aggregate corporate assets**, providing insights into **geographic concentration** and **macroeconomic scale**.

### 🔗 Data Provenance

The corporate financial data for **peer benchmarking** and **valuation modeling** was sourced from a publicly accessible ranking dataset (e.g., Forbes Global 2000, or a similar Kaggle dataset).

* **Dataset Link:** [[Financial Data Ranking Link]](https://www.kaggle.com/datasets/jasmeet0516/largest-companies-in-world)

### 💻 Key Deliverables

1.  **Top 20 by Net Profit Margin:** Bar chart facilitating **peer benchmarking** against the profitability ratio.
2.  **Revenue vs. Market Capitalization Correlation:** Scatter plot showing the relationship between operational size and investor valuation.
3.  **Global Asset Concentration:** Choropleth map illustrating the geographical distribution of organizational assets.

***

## ⚙️ Technical Environment

* **Language:** Python 3.x
* **Libraries:** Pandas, NumPy, Plotly Express
* **Format:** Jupyter/Google Colab Notebooks
