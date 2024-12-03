# E-commerce_Sales_Analysis

### Project Overview
This Data Analysis Project aims to provide insights into the sales performance of a Fintech based in Lagos, in the 2nd & 3rd quarters of the year 2021. By analysing various aspects of the sales data, we seek to identify trends, make data-driven recommendations and gain a deeper understanding of the company's performance.

### Data Source
The dataset used for this analysis is the "Service Provider New Version.xlsx" file[Service Provider New Version.xlsx](https://github.com/user-attachments/files/17993080/Service.Provider.New.Version.xlsx)


### Tools
- Excel - Data Cleaning
  - [Download here](https://microsoft.com)
- MySQL - Data Analysis
- PowerBI - Data Visualization

### Data Cleaning
In the preparation of the dataset for analysis, we performed the following tasks;
1. Removal of duplicates
2. Handled missing values with XLOOKUP
3. Changed values to the appropriate format

### Exploratory Data Analysis
The data was explored to answer key questions such as:
 - What was the monthly sales trend?
 - What were the top performing categories?
 - What were the peak sales periods?

   ### Data Analysis

   ```MYSQL
   SELECT payment_date, amount FROM service_provider_table
   WHERE category = 'betting'
   ```

   ### Dashboard
   ![screenshot of service provider](https://github.com/user-attachments/assets/308e5b2b-bb11-40cd-918e-1da37b824afa)

   ### Result/Findings

   ### Recommendations
