# 📊 Customer Behavior Analysis & RFM Segmentation

![Python](https://img.shields.io/badge/Language-Python-blue?style=for-the-badge&logo=python)
![Data Analysis](https://img.shields.io/badge/Focus-Customer_Segmentation-orange?style=for-the-badge)
![RFM](https://img.shields.io/badge/Method-RFM_Analysis-green?style=for-the-badge)

## 📌 Project Overview
This project analyzes customer transaction data to understand purchasing behavior, segment customers using **RFM Analysis** (Recency, Frequency, Monetary), and identify engagement and churn risks.

The project was completed as part of a **Data Analytics Internship task at Alfido Tech**.

---

## 🎯 Objectives
* **Analyze Behavior:** Understand customer transaction patterns and trends.
* **Segment Customers:** Apply the RFM methodology to categorize customers.
* **Identify Value:** Distinguish between High-Value, Mid-Value, and Low-Value customers.
* **Strategic Insights:** Provide actionable business recommendations to improve retention and engagement.

---

## 📂 Dataset
* **Source:** [Kaggle - Customer Behavior Analysis Dataset](https://www.kaggle.com/datasets/bhanupratapbiswas/customer-behavior-analysis)
* **Volume:** The dataset contains over **135,000 transaction records**.
* **Note:** Two datasets were provided. After cross-dataset validation, only the raw transaction dataset was used to ensure customer identity consistency.

---

## 🛠 Tools & Technologies
* **Language:** Python
* **Libraries:** Pandas, NumPy (Data Manipulation), Matplotlib, Seaborn (Visualization)
* **Environment:** Jupyter Notebook / Google Colab
* **Version Control:** GitHub

---

## 🔍 Methodology
The project followed a structured data analytics pipeline:

1.  **Data Loading & Understanding:** Initial inspection of the dataset structure and variables.
2.  **Data Cleaning:** Handled missing values (imputed Returns with 0), converted dates to datetime objects, and removed duplicates.
3.  **Feature Engineering:** Aggregated transaction-level data to the **customer level** to calculate:
    * *Recency:* Days since last purchase.
    * *Frequency:* Total number of orders.
    * *Monetary:* Total spending amount.
4.  **RFM Segmentation:** Scored customers based on RFM quartiles to create segments.
5.  **Visualization:** Analyzed purchase patterns and retention trends using bar charts and histograms.

---

## 📊 Customer Segments & Insights
Using RFM scores, customers were classified into three distinct segments. Key metrics for each group include:

### 💎 High-Value Customers
* **Characteristics:** Purchase frequently, spend the most, and have visited recently.
* **Metrics:** Average Recency of **~102 days** and Average Spending of **₹21,690**.
* **Insight:** This group generates the highest revenue per capita and demonstrates high loyalty.

### 🌟 Mid-Value Customers
* **Characteristics:** The largest customer base with moderate activity.
* **Metrics:** Average Recency of **~208 days** and Average Spending of **₹13,280**.
* **Insight:** Represent the biggest opportunity for growth; they are engaged but have potential for upselling.

### ⚠️ Low-Value Customers
* **Characteristics:** Infrequent buyers with long gaps between purchases.
* **Metrics:** Average Recency of **~499 days** (high churn risk) and Average Spending of **₹7,006**.
* **Insight:** These customers are at high risk of churning and require re-engagement efforts.

---

## 💡 Business Recommendations
Based on the segmentation analysis, the following strategies are proposed:

* **For High-Value:** Focus on retention through **exclusive loyalty programs** and early access to new products.
* **For Mid-Value:** Drive growth by **upselling** with targeted offers and personalized promotions to increase their purchase frequency.
* **For Low-Value:** Launch **re-engagement campaigns** (e.g., "We miss you" emails with discounts) to reduce churn.
* **General Strategy:** Shift from one-size-fits-all marketing to **segment-based strategies** and monitor customer activity regularly.

---

## 📄 Project Report
For a detailed walkthrough of the code and analysis, please refer to the project report:
📎 `Customer_Behavior_Analysis_Report.pdf`

---

## 👤 Author
**Manish Kumar**
*Data Analytics Intern – Alfido Tech*
