# Analysing Glassdoor Reviews: Impact of Job Satisfaction on Employee Retention and Firm Performance in the IT Industry

The goal here is to create **machine learning models** to help with the titular objective. We want to determine the impact of:
1. **Job satisfaction** on
1. **Employee retention** and
2. **Firm performance**
3. within the **IT industry** only.

Our data sources are **Glassdoor**, **Compustat** for retrieving measures of firm financial performance, and a **Ticker** dataset to match company names with their tickers, ensuring that financial data can be retrieved for the companies reviewed on Glassdoor. 

To achieve our goal, we'll follow these steps:
1. Scrape Glassdoor reviews
2. Clean Glassdoor data
3. Retrieve tickers of the **top public IT firms**, effectively restricting the scope to only companies within the IT Industry, and only those with publicly available financial data
4. Merge datasets
5. Clean merged data
6. Exploratory data analysis
7. Extract employee retention data from Glassdoor review data
8. Retrieve financial performance data
9. Merge into final dataset and prepare for linear regression
10. Visualise dataset relationships
11. Create ML models with **Job Satisfaction** predicting **Retention**
12. Create ML models with **Job Satisfaction** predicting **Market Cap**
13. Create ML models with **Job Satisfaction** predicting **Return on Assets**
