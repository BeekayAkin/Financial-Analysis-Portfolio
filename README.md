# Financial-Analysis-Portfolio

### Project Overview

This data analysis provides insight into the sales performance of a company for the year 2013 and 2014. By analyzing various aspects of the sales data, we seek to identify trends, make data driven recommendations, and gain a deeper understanding of the sales performance.

### Data Source

Financial sample Data: The primary dataset used for this analysis is the "Financial sample.xlsx" file, containing detailed information about each sales made by the company.

### Tools

- PowerBI (power query) -Data cleaning
- PowerBI -Creating reports

### Data Cleaning / Preparation

in the initial data preparation phase, i performed the following tasks:
- Data loading and inspection.
- Handling missing values.

### Exploratory Data Analysis

EDA involved exploring the HR data to answer key questions, such as:

1. What is the total amount of revenue?
2. What is the total amount of unit sold?
3. What is the gross profit?
4. Which country made the highest profit?
5. What is the sales percentage for each country?
6. Which product has the highest sales?
7. Which month was the highest sales recorded?

### Data Analysis

incude some DAX functions worked with

```
Total Revenue = SUM(financials[Gross Sales])

Total Unit Sold = SUM(financials[Units Sold])

Gross Profit = ([Net Sales]-[Cost OGS])
```

### Result / Findings
The analysis results are summerized as follows:
1. France have the highest profit.
2. The product Paseo is the most profitable.
3. United States have the highest amount of sales.
4. The highest profit was made in the month of October.

   






