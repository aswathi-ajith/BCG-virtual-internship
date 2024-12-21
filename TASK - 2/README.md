# Exploratory Data Analysis for Customer Churn at PowerCo

This project aims to conduct a comprehensive exploratory data analysis (EDA) to uncover insights into customer churn for **PowerCo**, a major gas and electricity utility provider for small and medium-sized enterprises (SMEs). By analyzing historical data, this task focuses on identifying patterns, trends, and anomalies that influence customer retention.

## Objective
To leverage EDA techniques to:
- Understand the statistical properties and distributions of the provided datasets.
- Identify key factors contributing to customer churn.
- Prepare the data for subsequent predictive modeling tasks.

## Datasets
The client has provided three datasets for analysis:
1. **Historical Customer Data**: Includes customer information such as usage patterns, subscription dates, and forecasted consumption.
2. **Historical Pricing Data**: Contains details about variable and fixed pricing structures.
3. **Churn Indicator**: Specifies whether a customer has churned or not.

## Methodology
### 1. Data Overview
- Examine the data types of each column to ensure proper interpretation and handling.
- Generate summary statistics to describe central tendencies, variability, and data completeness.

### 2. Data Visualization
- Analyze the distributions of key variables (e.g., consumption, pricing, and churn).
- Use visualizations such as histograms, boxplots, and scatter plots to identify trends and potential outliers.
- Investigate relationships between churn and categorical variables such as sales channels, contract types, and subscription features.

### 3. Outlier Detection
- Use boxplots to identify outliers in critical numerical columns, such as consumption and forecasted usage.
- Assess the impact of outliers on overall data trends and consider appropriate treatments.

### 4. Churn Analysis
- Calculate churn rates across various dimensions to explore potential drivers.
- Compare churn distributions based on factors like sales channel, subscription type, and forecasted consumption.

## Key Findings
- **Churn Rate Distribution**: Initial visualizations indicate a churn rate of approximately 10%, which is considered low. Further analysis identifies patterns linked to specific sales channels and pricing structures.
- **Skewed Data**: Consumption data exhibits positive skewness, highlighting the need for transformation or outlier handling in future steps.
- **Insignificant Variables**: Preliminary analysis suggests that certain variables, such as contract type, may not significantly influence churn.




