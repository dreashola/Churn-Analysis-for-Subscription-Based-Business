# Churn Analysis for Subscription-Based Business
![Introduction](intro.png)

## Objective
The primary objective of this project is to conduct a comprehensive analysis of customer churn data from Databel, a subscription-based Telecom company. The analysis aims to identify the underlying factors contributing to customer churn and provide actionable insights to mitigate churn rates, thereby enhancing customer retention and business sustainability.

## Data Source

The dataset utilized for this project was sourced from [Kaggle](https://www.kaggle.com/datasets/yichienchong/databel-telecom-customer-churn-dataset/data). It comprises various attributes, including customer information, contract details, subscription types, charges, and churn status over a specified period. This comprehensive dataset provides a robust foundation for analyzing the factors contributing to customer churn.

## Data Preparation

- **Formatting**: 
  - Transformed the dataset into a structured tabular format to facilitate efficient data manipulation and analysis.

- **Cleaning**: 
  - Identified and removed duplicate records utilizing Excel’s "Remove Duplicates" feature to ensure data integrity.

- **Transformation**: 
  - Converted the churn label into a binary column (1 for Yes, 0 for No) using an IF statement in Excel:
    - `=IF([@[Churn Label]] = "Yes", 1, 0)`

![Transformed Data](transformed.png)
## Data Exploration and Analysis
- **Summary Statistics**: 
  - Generated pivot tables to calculate the total number of customers and those who churned using Excel’s built-in functions.
  - Determined the churn rate by dividing the number of churned customers by the total number of customers.

  ![Pivot Table](pivot1.png) |  ![Pivot Table](pivot2.png)

- **Visualizations**: 
  - Created pivot tables to summarize data by key dimensions such as age group, subscription plan, and churn reason.
  - Utilized bar charts to illustrate the distribution of churn categories and churn reasons across the dataset.
  - Developed a combo bar and line chart to visualize the distribution of customers and churn rates across different age groups.

  ![Dashboard](dashboard.png)  

- **Key Findings**:
  - A total of 1,796 customers have churned.
  - The overall churn rate is approximately 27%.
  - The senior customer category exhibits the highest churn rate at 39%.
  - Customers on an unlimited plan are more prone to churn.
  - The predominant reasons for customer churn are competitor-related, with better offers and devices being the top causes for customer loss to competitors.
  

## Methodology

- **Techniques Used**: Employed Excel formulas, pivot tables, and conditional formatting for thorough data analysis.

## Results
- **Churn Rate**: The overall churn rate is approximately 27%.
- **Insights**:
  - Customers with subscription lengths shorter than two years exhibited a churn rate exceeding 29%.
  - The churn rate for customers on a month-to-month contract was notably high at 74%, whereas it stood at only 3% for customers on a two-year contract.
  - Customers aged above 68 years, although constituting the lowest customer segment, displayed the highest churn rate.
  - Customers subscribed to the unlimited data plan and utilizing less than 5GB are more susceptible to churn compared to their counterparts on the same plan.
  - Customers enrolled in the international call plan demonstrated a higher likelihood of churn.
  - Customers subscribed to the international call plan residing in specific states (California, Indiana, New Hampshire, Louisiana and Kentucky) exhibited a churn rate exceeding 50%.


## Conclusion
In summary, the analysis of customer churn data from Databel reveals several key insights:
- The primary drivers of customer churn are competitor-related, particularly due to better offers and devices.
- Customers on month-to-month contracts exhibit a significantly higher churn rate of 74%, contrasting starkly with the low 3% churn rate observed for those on two-year contracts.
- Subscription lengths shorter than two years correlate with higher churn rates exceeding 29%.
- Although constituting a smaller customer segment, senior customers aged above 68 years demonstrated the highest churn rate at 39%.
- Customers subscribed to unlimited data plans who use less than 5GB of data monthly are predisposed to churn.
- Notably, customers enrolled in international call plans, especially in states such as California, Indiana, New Hampshire, Louisiana, and Kentucky, exhibit churn rates exceeding 50%.

## Recommendations

Based on the insights derived from the analysis, the following recommendations are proposed to mitigate churn rates and enhance customer retention at Databel:

1. **Promote Long-Term Contracts**: Develop and market offers incentivizing customers to transition from month-to-month contracts to longer-term contracts, such as two-year plans, to reduce the high churn rates associated with short-term contracts.

2. **Tailored Retention Strategies for Seniors**: Implement retention strategies tailored to senior customers, including special discounts, personalized loyalty programs, and dedicated customer support, to address their unique needs and concerns and mitigate their high churn rates.

3. **Review Unlimited Data Plans**: Evaluate the pricing and benefits of unlimited data plans, particularly for low-usage customers, and consider offering alternative plans or personalized recommendations to ensure customers perceive value for their money.

4. **Address International Call Plan Churn**: Investigate the reasons behind the high churn rates for international call plans in states such as California, Indiana, New Hampshire, Louisiana, and Kentucky. Revise these plans to offer better rates or additional benefits to retain customers in these regions.

5. **Competitive Pricing and Features**: Conduct a comprehensive analysis of competitor offerings and develop competitive pricing and feature packages. Ensure marketing campaigns highlight the unique value propositions and benefits of remaining with Databel.

6. **Targeted Marketing Campaigns**: Develop targeted marketing campaigns aimed at customers approaching the end of their contract period or showing signs of potential churn. Offer tailored incentives to renew their subscriptions and foster loyalty.

7. **Collect Customer Feedback**: Implement mechanisms to collect detailed customer feedback to identify specific pain points. Address these issues through service improvements, product enhancements, and enhanced customer support to improve overall customer satisfaction and retention.

## Tools and Technologies
- Microsoft Excel: Utilized for data cleaning, analysis, and visualization, leveraging its robust features such as formulas, pivot tables, and conditional formatting to conduct comprehensive data exploration and generate insightful visualizations.




