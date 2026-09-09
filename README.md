Ecommerce-Customer-Segmentation

````markdown
🛒 E-Commerce Customer Segmentation

📌 Project Overview

This project focuses on analyzing e-commerce customer purchasing behavior using RFM Analysis and K-Means Clustering.

The objective is to group customers based on their Recency, Frequency, and Monetary value, identify different customer segments, and generate insights for targeted marketing and customer retention.

🎯 Objectives

- Analyze customer purchasing behavior
- Perform RFM Analysis
- Segment customers using K-Means Clustering
- Identify high-value and inactive customers
- Analyze Customer Lifetime Value (CLV)
- Generate actionable business insights

🔍 Methodology

RFM Analysis

RFM analysis evaluates customers using:

- Recency – How recently a customer made a purchase
- Frequency – How often a customer makes purchases
- Monetary – How much a customer spends

 K-Means Clustering

K-Means Clustering is used to group customers with similar purchasing behavior.

StandardScaler is used for feature scaling, and the Elbow Method is used to determine the appropriate number of clusters.

 Customer Lifetime Value

CLV is analyzed to understand the potential value of different customer groups and help prioritize high-value customers.

 👥 Customer Segments

The analysis identifies five customer segments:

| Segment | Description |
|---|---|
| 🏆 Champions | Recent, frequent, and high-spending customers |
| 💙 Loyal Customers | Customers with consistent purchasing behavior |
| 💰 Big Spenders | High-value customers with lower purchase frequency |
| ⚠️ Need Attention | Customers showing reduced engagement |
| 💤 Lost / Hibernating | Inactive customers who may require reactivation |

 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- SQL
- Jupyter Notebook

 📂 Project Structure


Ecommerce-Customer-Segementation/
│
├── customer_segmentation_queries.sql
├── customer_segments_visualization.png
├── elbow_method.png
├── gitignore.txt
├── requirements.txt
├── rfm_analysis_and_segmentation.ipynb
└── README.md
````

🔄 Project Workflow

```
Transaction Data
       ↓
Data Cleaning & EDA
       ↓
RFM Analysis
       ↓
Feature Scaling
       ↓
Elbow Method
       ↓
K-Means Clustering
       ↓
Customer Segmentation
       ↓
CLV Analysis
       ↓
Business Insights
```

📈 Business Applications

Customer segmentation can help businesses:

* Identify high-value customers
* Improve customer retention
* Personalize marketing campaigns
* Increase repeat purchases
* Reactivate inactive customers
* Improve marketing strategies

 🚀 How to Run

Install the required libraries:

```bash
pip install -r requirements.txt
```

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```
rfm_analysis_and_segmentation.ipynb
```

Run the notebook cells sequentially to perform the analysis.

 📚 Learning Outcomes

This project provided practical experience in:

* Exploratory Data Analysis
* RFM Analysis
* Feature Engineering
* K-Means Clustering
* Unsupervised Machine Learning
* Data Visualization
* SQL Analysis
* Customer Lifetime Value Analysis

## 👩‍💻 Author

**Shreya Bagal**

Data Science | Python | SQL | Machine Learning

```

