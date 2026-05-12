# E-commerce-Sales-Analysis

### Project Overview

To analyze e-commerce sales data and understand performance across stores, products, and customers.

### Data Source

Sales Dataset : The primary dataset used for this analysis is the "Ecommerce_Sales_Dataset.xlsx" file, containing detailed information about stores, products and customers.

### Tools

Google Sheets : Data cleaning, Data Analysis and Creating reports.

### Data Cleaning/Preparation

In the initial data preparation phase, we performed the following tasks:

1. Data loading and Inspection.
2. Handling missing values.
3. Data Cleaning and Formatting.

### Exploratory Data Analysis

EDA involved exploring the sales data to answer key questions, such as:

- Which 10 stores generates most revenue?
- Which is highest selling product and generates most revenue as well as lowest revenue generating product?
- Which gender is the maximum buyer?
- What is the average monthly sales?
- Who among all the customer's is the top buyer?

### Data Analysis

- Formula Used to clean and Standardize the column's in the dataset ```TRIM(PROPER(Column_name))```
- To extract month name from date column we used ```TEXT(date, "mmm")```
- To fill the null cells in the sheet we used ```IF(ISBLANK(value), value_if_true, value_if_false)```
- We used ```AVERAGEIF(criteria_range, criterion, [average_range])``` function to to find the missing values.
- Created conditional column using ```IFS(condition1, value1, [condition2, …], [value2, …])```
- Created Pivot table to summarize the data.
- To find the top 10 in google sheets we used ```QUERY(data, query, [headers])```
- To look for the value in the dataset we used
  - ```XLOOKUP(search_key, lookup_range, result_range, [missing_value], [match_mode], [search_mode])```
  - ```VLOOKUP(search_key, range, index, [is_sorted])```
  - ```INDEX(reference, [row], [column])```
  - ```MATCH(search_key, range, [search_type])```

### Results/Findings

1. Store named "Bean, Jones and Park" has highest earnings (₹158,971.46) which is 7.3% among all the stores, Rest all stores has 1 lakh or above earnings except Shelton PLC, Black-Horn, Mann-Austin, Aguirre-Keller, Rivera-Warner and Gray Ltd, These stores earns less than 1 lakh, And Gray Ltd has the lowest earning (₹81,343.59) among all the 20 stores.
2. The product "Men's Graphic T-Shirt" is the highest earning product among 100 different product generating total sales of ₹61,150.33, And "Portable Power Bank" is 2nd highest earning product generating total sales of ₹57,518.36. While,  "Makeup Brush Set" is the lowest earning product among all different product generating total sales of ₹7,948.39.
3. The average sales in November 2024 generated highest average sales, And in month of May 2024, average sales was the lowest.
4. Male's are maximum buyers campared to Female's, Male buyers are slightly more than Female buyer, having difference of only 6.63%.
5. Customer whose name is "Jordan Wells" is the top buyer among all the customer (₹17,147.71), While "Eric Davis" is lowest buyer among all the customer (₹36.03).

### Recommendations
1. "Bean, Jones and Park" has the highest earnings so focus marketing efforts on high-performing stores and "Gray Ltd" has the very lowest earnings, so focus on that store and promote the store to earn more.
2. Maintain high stock in the inventory for the most selling products.
3. Males are buying more products than female, so increase products which was used by females also to improve the sales.
4. From dashboard we find that nearly 10 customers are buying in the range of 11k to 17k, so try to increase the customers like them.

