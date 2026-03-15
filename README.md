# Global Superstore Sales-Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools](#tools)
- [Data Cleaning/Preparation](#data-cleaning-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results/Findings](#results-findings)
- [Recommendations](#recommendations)
- [Limitations/Disclaimer](#limitations-disclaimer)

 ## Project Overview

This data Analysis aim to provide insights into the sales performance of Global Superstore company over a period of a year (2016). By analyzing various aspects of the sales data, we seek to identify trends, make the data driven recommendations and gain deeper understanding of the company’s performance.

### Data Source

Sales data: The primary dataset used for this analysis is the “ Google Spreadsheets dataset, Csv” file, containing detailed information about each sale made by the company.

### Tools

- Excel - Data Cleaning & Analysis
   - [Download_here](https://docs.google.com/spreadsheets/d/1oE5Mab7KBvIfHK8WFMZ4jNFm_QeJDG_Wql4zsGghcDY/edit?usp=sharing)
- SQL Server - Further Data Cleaning and Analysis
- PowerBI - Creating Reports

### Data Cleaning/ Preparation

In the initial phase, we performed the following tasks.
1. Data loading and inspection
2. Handling missing values
3. Removed duplicates
4. Data cleaning and formatting

### Exploratory Data Analysis

EDA involved exploring the sales data to answer the following questions, such as:
-	What is the overall sales trend?
- What products are top sellers?
- What are the peak sales periods?
- Which regions are more profitable?
- What is the impact of discounts on profitability?


### Data Analysis

Interesting code/features worked on
- Excel
  - Sales by region by category
  - Profit by Category
  - Sales by segment
  - Sales by customer

```SQL
  SELECT * FROM table 1
  WHERE cond = 2;
```

### Results/ Findings

The analysis results are summarized as follows:
1. The company’s sales have been steadily increasing over the years, with a noticeable peak during the holiday season.
2. Product category A is the best performing category in terms of sales and revenue.
3. Customer segment with high lifetime value (LTV) should be targeted for marketing efforts.

### Recommendations

Based on the analysis, we recommend the following actions:
- Invest in marketing and promotions during peak sales season to maximize revenue.
- Focus on expanding and promoting products in category A
- Implement a customer segmentation strategy to target high – LTV customers effectively.

### Limitations/ Disclaimer

[Any action taken on data that would affect the quality and accuracy of the analysis and results e.g. exclusion or removal of records that would affect accuracy of the results/report so that the person who is reviewing the report will have some context of the analysis]


I had to remove all zero values from the sales and revenue columns because they would have affected the accuracy of my calculations from the analysis. There are a few outliers even after the omissions but even then, we can still see that there is a positive correlation between both sales numbers and revenue.


### References

1. SQL for Business by Werty
2. [Stack overflow](https://stacl.com)
