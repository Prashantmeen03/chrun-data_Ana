# Customer Churn Data Analysis

This repository contains an analysis of customer churn behavior based on various demographic and usage metrics. The goal is to explore the data, identify key factors contributing to customer churn, and gain actionable insights.

## Repository Contents

*   **`churn_analysis.ipynb` / `chrun.ipynb`**: Jupyter Notebooks containing the exploratory data analysis (EDA), visualizations, and data processing steps.
*   **`customer_churn_dataset-training-master.csv`**: The training dataset used for analysis and modeling.
*   **`customer_churn_dataset-testing-master.csv`**: The testing dataset used to validate models.
*   **`customer_churn.db`**: SQLite database containing the customer churn data.

## Dataset Features

The dataset includes the following customer information:
*   `CustomerID`: Unique identifier for each customer
*   `Age`: Customer's age
*   `Gender`: Customer's gender
*   `Tenure`: Duration of the customer's relationship with the company
*   `Usage Frequency`: How often the customer uses the service
*   `Support Calls`: Number of support calls made by the customer
*   `Payment Delay`: Delays in payment (in days)
*   `Subscription Type`: Type of subscription (e.g., Basic, Standard, Premium)
*   `Contract Length`: Length of the contract (e.g., Monthly, Quarterly, Annual)
*   `Total Spend`: Total amount spent by the customer
*   `Last Interaction`: Days since the last interaction
*   `Churn`: Target variable indicating whether the customer churned (1) or not (0)
