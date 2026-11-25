# Bank Customer Churn Analysis & Retention Strategy

An end-to-end data analytics project exploring customer churn patterns in a banking dataset using Python and Power BI. The project identifies high-risk customer segments, examines churn trends, and translates analytical findings into actionable customer retention recommendations.

## Project Overview

Customer churn is a major challenge for banking institutions. Understanding which customer groups are more likely to leave helps businesses develop targeted retention strategies.

This project analyses 10,000 bank customer records to identify churn patterns across age groups, geographical regions, product holdings, and customer tenure.

## Objectives

- Analyse overall customer churn and retention rates.
- Identify customer segments with elevated churn rates.
- Examine churn patterns across geography, age, tenure, and product holdings.
- Identify segments contributing most to customer losses.
- Develop data-driven customer retention recommendations.
- Propose a 30-day customer monitoring framework.

## Tools & Technologies

- **Python:** Data cleaning, transformation and analysis
- **Pandas & NumPy:** Data manipulation and analysis
- **Matplotlib & Seaborn:** Data visualization
- **Jupyter Notebook:** Exploratory data analysis
- **Power BI:** Interactive dashboards and business intelligence

## Project Structure

```text
bank-customer-churn-analysis/
│
├── notebooks/
│   └── bank_customer_churn_analysis.ipynb
│
├── data/
│   └── Bank_Customer_Churn_Cleaned.csv
│
├── analysis/
│   ├── Age_Churn_Analysis.csv
│   ├── Geography_Churn_Analysis.csv
│   ├── Product_Churn_Analysis.csv
│   ├── Tenure_Churn_Analysis.csv
│   ├── Combined_Segment_Analysis.csv
│   ├── Churn_Contribution_Analysis.csv
│   ├── Retention_Strategy.csv
│   └── 30_Day_Monitoring_Framework.csv
│
├── power-bi/
│   └── Bank_Customer_Churn_Dashboard.pbix
│
├── requirements.txt
└── README.md
```

## Key Business Findings

- **Overall churn rate:** 20.37% across 10,000 customers.
- **Total churned customers:** 2,037.
- **Highest-risk age group:** Customers aged 45–54, with a churn rate of 48.15%.
- **Highest-risk geography:** Germany, with a churn rate of 32.44%.
- **Highest-risk product segment:** Customers holding four products showed 100% churn in this dataset, although this group contained only 60 customers.
- **Highest-priority segment:** Germany | Age 45–54 | Single Product, with a churn rate of 75.34%.

The four largest churn-contributing customer segments collectively account for 39.37% of all churned customers.

## Power BI Dashboard

The interactive dashboard contains three pages:

1. **Executive Overview** – Overall churn KPIs and churn distribution across customer dimensions.
2. **Customer Risk Analysis** – Customer segmentation, high-risk groups, and churn contribution analysis.
3. **Retention Strategy** – Priority customer segments, recommended retention actions, and a proposed 30-day monitoring framework.

## Retention Recommendations

- Prioritize targeted retention outreach for high-risk customer segments.
- Investigate customer dissatisfaction and reasons for account closure.
- Review product suitability and multi-product engagement.
- Monitor transaction activity, account balances, digital login frequency, complaints, and product engagement.

## Important Analytical Limitation

This project uses a static customer dataset without transaction timestamps or historical customer activity. Therefore, the analysis identifies historical churn patterns and associated risk segments; it does not build or validate a predictive churn model.

The 30-day monitoring framework represents proposed business monitoring activities, not measured future customer behaviour.

## How to Run the Project

1. Clone this repository.
2. Install the required Python libraries:

```bash
pip install -r requirements.txt
```

3. Open the notebook inside the `notebooks/` folder.
4. Update the dataset path if necessary.
5. Run the notebook cells to reproduce the analysis.

## Author

**Bank Customer Churn Analysis Project**

Developed as a Data Analytics portfolio project using Python and Power BI.
