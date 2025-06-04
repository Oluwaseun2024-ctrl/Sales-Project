# Sales-Project
### INTRODUCTION
An Excel project analyzing a year's worth of sales from a fictitious pizza sales place. The dataset encompasses details such as pizza type, size, quantity, price, and ingredients. The goal is to derive actionable insights to inform strategic decisions and optimize overall operational effectiveness.

**Table of Contents**
- [Project Overview](https://github.com/Oluwaseun2024-ctrl/Sales-Project#project-objectives)
- Project Scope
- [Project Objectives](https://github.com/Oluwaseun2024-ctrl/Sales-Project#project-objectives)
- Expected Outcome
- Document Purpose
- Use Case
- [Data Source](https://github.com/Oluwaseun2024-ctrl/Sales-Project#data-source)
- Data Cleaning and Processing
- Data Analysis
- Data Visualization
- Recommendation
- Conclusion

### Project Overview

This project involves an in-depth analysis of a year's worth of sales data from a fictitious pizza place. The analysis is performed using Excel, providing valuable insights to drive strategic decisions and optimize operational effectiveness.

### Project Objectives

The primary objectives of this analysis are:
- **Sales Analysis:** Understand sales patterns over the year, identifying peak times and high-demand periods.
- **Product Performance:** Evaluate which types and sizes of pizzas are most popular and generate the most revenue.
- **Customer Preferences:** Analyze ingredient popularity and preferences to refine the menu offerings.
- **Operational Insights:** Uncover inefficiencies and areas for improvement in operations and supply chain management.


### Data Source

The dataset for this project is sourced from [Maven Analytics website](https://app.mavenanalytics.io/datasets?dataStructure=Multiple+tables&accessType=open&search=PIZZ) designed specifically for practice purposes. It is presented in an Excel file with four tables (Order Details, Orders, Pizza Types, and Pizzas) comprising 48,620, 21,350, 32, and 96 rows respectively, and 4, 3, 4, and 4 columns respectively. The dataset includes key attributes essential for a comprehensive analysis, such as:

![](https://github.com/Oluwaseun2024-ctrl/Sales-Project/blob/main/Number%20of%20Customers%20Per%20Day.png)

``` SQL
SELECT 
	[Year],
COUNT 
	(Complaint_ID) AS [Total No of Complaints]
FROM 
	Financial_Consumer_Complaints
GROUP BY 
	[Year]
ORDER BY 
	[Year] ASC
```

``` PYTHON
# Initialize and fit the model
regressor = LinearRegression()
regressor.fit(X_train, y_train)
# Coefficients
print("Coefficients:", regressor.coef_)
print("Intercept:", regressor.intercept_)
```

| Product | Price | Profit |
|---------|-------|--------|
| Fanta   | 23    | 76     |
| Coke    |  65   | 88     |



| Product                                                                 | Total No of Complaints |
|-------------------------------------------------------------------------|-------------------------|
| Checking or savings account                                             | 24,814                  |
| Credit card or prepaid card                                             | 16,197                  |
| Credit reporting, credit repair services, or other personal consumer reports | 7,710              |
| Mortgage                                                                | 6,601                   |
| Money transfer, virtual currency, or money service                      | 3,453                   |
| Debt collection                                                         | 2,736                   |
| Vehicle loan or lease                                                   | 633                     |
| Payday loan, title loan, or personal loan                               | 333                     |
| Student loan                                                            | 39                      |

_Sekinat_
