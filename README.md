# Banking-Customer-Churn
This project aimed to analyze customer churn in a banking dataset to uncover patterns, identify high-risk groups, and predict churn using SQL, Python, and Power BI. The analysis was divided into two parts: exploratory analysis using SQL and predictive modeling using Python. Visualizations in Power BI further supported the insights.
## Key Findings from Exploratory Analysis (SQL)
### Churn Rate: Only 20.37% of customers have churned, while the majority remain active.
### Demographics:
Females are more likely to churn than males across all three countries.
Adults aged 31–55 have the highest churn rates among both genders.
### Balances and Salaries:
Customers with high balances churn the most, irrespective of their salary bracket.
Significant churn is observed among customers with no or low balances but high salaries.
### Credit Scores:
Customers with credit scores between 300–739 have a higher churn rate.
The least churn occurs for scores between 749–799.
### Tenure:
Long-tenured customers (3+ years) churn 74% more than new customers (0–2 years).
### Bank Products:
Customers with a single product are more likely to churn than those with multiple products.
## Predictive Analysis Using Python
Various machine learning models were evaluated, including Logistic Regression, Random Forest, and XGBoost.
Random Forest was the best-performing model with an accuracy of 86.34% and a mean cross-validation score of 0.86087.
A pipeline was constructed to streamline preprocessing (standard scaling and one-hot encoding) and model training, ensuring efficiency and scalability.
The predictive model effectively identifies at-risk customers, enabling proactive retention strategies.

## Conclusion
This project successfully combined exploratory analysis, predictive modeling, and visualization to address customer churn. The insights emphasize the need for targeted retention strategies focusing on high-risk demographics, high-balance customers, and those with single bank products. The predictive model adds value by identifying at-risk customers with high accuracy, allowing for timely intervention. By leveraging these findings, the bank can reduce churn, improve customer satisfaction, and drive long-term profitability. This analysis demonstrates the importance of data-driven strategies in enhancing customer retention and operational efficiency.
