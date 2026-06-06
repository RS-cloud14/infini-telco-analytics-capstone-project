# Infini Telco Customer Segmentation & Product Categorization

## Project Overview

This project analyzes B2B telecommunications transaction data to identify customer segments and high-performing product categories using Machine Learning and Pareto Analysis.

The project was developed as part of a Data Analytics Capstone project focused on helping Infini Telco improve its marketing, sales, customer retention, and product strategy through data-driven insights.

---

## Business Problem

Infini Telco faced several business challenges:

- Limited visibility into customer purchasing behavior
- Inadequate product insights across customer groups
- No streamlined analytical process
- Difficulty identifying high-value customers and products
- Limited ability to perform targeted marketing and cross-selling

This project aims to solve these challenges through:

- Customer Segmentation
- Product Categorization
- Revenue Contribution Analysis
- Strategic Business Recommendations

---

## Project Objectives

- Perform customer segmentation using K-Means Clustering
- Identify optimal clusters using Elbow Method and Silhouette Score
- Conduct Pareto Analysis for product contribution analysis
- Discover high-value customer segments
- Identify core and long-tail product categories
- Generate business insights and strategic recommendations

---


### Data Sources

- Transaction Data (1,2,3)
- Product Category Mapping
- Customer Type Mapping
- Customer Characteristics Data
-CustSegmentation_Tableau_input_

---

## Data Preparation & Transformation

The following preprocessing steps were performed:

- Combined multiple transaction datasets
- Removed duplicate and invalid records
- Applied logical and business filters
- Standardized data structure
- Integrated customer and product mapping tables
- Treated missing values
- Performed feature engineering
- Enriched datasets for clustering analysis

### Engineered Features

| Feature | Description |
|---|---|
| Invoice Flag | Customers with more than 3 invoices |
| SKU Flag | Measures product purchasing diversity |

---

## Analytical Methodology

### 1. Customer Segmentation
Technique Used:
- K-Means Clustering

Features Used:
- Gross Turnover
- Product Categories
- Invoice Flag
- SKU Flag
- Customer Spend

### 2. Product Categorization
Technique Used:
- Pareto Analysis

Purpose:
- Identify high-contributing product categories
- Analyze revenue concentration
- Detect core and long-tail products

### 3. Model Selection

#### Elbow Method
Used to determine suitable cluster ranges based on WCSS reduction.

#### Silhouette Score
Used to evaluate cluster cohesion and separation.

Final selected clusters:
- K = 10

### 4. Cluster Profiling
Performed descriptive analysis to understand:
- Spending behavior
- Product preferences
- Revenue contribution
- Customer purchasing patterns

---

## Key Findings

### Revenue Concentration
- Cluster 3 contributed more than 50% of total revenue
- Total company revenue exceeded RM931 million
- Top 20 VIP customers generated a significant portion of revenue

### Product Performance
- Core products generated RM522.41 million
- Approximately 8 product categories contributed around 80% of total turnover
- Postpaid mobile plans were the highest-performing category

### Customer Behavior
- Distinct purchasing behavior was identified across all 11 customer segments
- Lower-tier customer groups mainly purchased low-value or long-tail products
- Strong cross-selling opportunities were identified

---

## Business Recommendations

### Customer Retention Strategy
- White-glove VIP account management
- Predictive churn analytics
- Loyalty and retention programs

### Portfolio Optimization
- Audit low-performing products
- Reduce low-ROI product lines
- Reinvest in core product categories

### Personalized Marketing
- AI-driven marketing campaigns
- Cross-selling strategies
- Targeted campaigns for lower-tier clusters

---

## Technologies Used

### Programming & Analytics
- Python
- Pandas
- NumPy
- Scikit-learn

### Visualization
- Matplotlib
- Seaborn
- Power BI / Tableau

### Development Environment
- Jupyter Notebook

---

## Repository Structure

```plaintext
infini-telco-customer-segmentation/
│
├── README.md
├── requirements.txt
├── notebooks/
│   └── Final_Presentation_Source_Code.ipynb
│
├── presentation/
│   ├── Final_Presentation.pdf
│   └── Capstone_Brief.pdf
│
├── images/
│   ├── clustering_result.png
│   ├── elbow_method.png
│   ├── silhouette_score.png
│   └── dashboard_preview.png
│
└── data/
    └── sample_data_or_note.txt
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/infini-telco-customer-segmentation.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Future Improvements

- Deploy interactive dashboards online
- Build predictive churn models
- Implement recommendation systems
- Automate customer targeting workflows
- Integrate real-time business monitoring

---

## Authors

Group 5 Data Analytics Capstone Team

- Tham Ren Sheng
- Haikal Najmi
- Vithya Darshinie
- Muhammad Amanul Hakim
- Nurul Hidayah
- Danish Aiman
- Muhammad Syahmi
- Sofiah Hanis Batrisya

---

## Disclaimer

Dataset is not publicly uploaded due to confidentiality and file size limitations.

---

## License

This project is developed for educational and portfolio purposes.
