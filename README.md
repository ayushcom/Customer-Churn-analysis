## Customer Churn Analysis using Python

This project explores customer churn patterns using Python for data cleaning, visualization, and insights generation. The analysis identifies key factors influencing churn and offers actionable recommendations to improve customer retention.

📂 Dataset Information

Dataset: customer churn.csv

Contains customer details, contract information, and service usage patterns

🔧 Data Preparation

Handled missing values by replacing blanks in the TotalCharges column with zero and converted it to float.

Transformed SeniorCitizen values from binary (0/1) to 'Yes/No' for improved clarity.

Conducted data inspection using .info() and .describe() to understand structure and key statistics.

📊 Exploratory Data Analysis (EDA)

Visualizations Created:

Churn Count Plot: Displays the distribution of churned vs. non-churned customers.

Additional charts analyzing churn patterns based on:

Tenure

Contract Type

Payment Method

Service Usage

🔍 Key Insights

Overall Churn Rate: 26.54% of customers have churned.

Demographics: Senior citizens had a higher churn rate (~41.7%) compared to non-senior customers (~23.6%).

Tenure Analysis:

Customers with 1-2 months tenure faced ~60% churn.

Customers with 24+ months tenure had a churn rate below 10%.

Contract Types:

Month-to-month contracts: ~43.5% churn.

1-year contracts: ~11.4% churn.

2-year contracts: ~2.7% churn.

Service Impact:

Services like Phone Service, Internet Service (DSL), and Online Security had lower churn rates.

Customers without services like Online Backup, Tech Support, or Streaming TV experienced higher churn.

Payment Methods:

Electronic Check users had the highest churn (~45.8%).

💡 Recommendations

Focus on improving customer retention for month-to-month contract customers.

Strengthen onboarding strategies to engage new customers in their early tenure.

Promote value-added services such as Online Security and Tech Support.

Encourage customers to switch from Electronic Check to more stable payment methods like Credit Card or Bank Transfer.
