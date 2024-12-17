# Sales Forecasting Project (Excel)

## Project Overview
This project focuses on analyzing and forecasting sales data using Microsoft Excel. The dataset provides customer demographic details, product preferences, and transaction information, which are utilized for generating insights and predicting future sales trends.

---

## Dataset Description
The dataset includes the following columns:

1. **FirstName**: Customer's first name.  
2. **LastName**: Customer's last name.  
3. **Age**: Customer's age (in years).  
4. **City**: City of residence.  
5. **Gender**: Gender of the customer (Male/Female).  
6. **Income**: Customer's annual income in INR.  
7. **Products**: The product purchased by the customer.  
8. **Quantity**: Quantity of the product purchased.  
9. **DOB**: Date of Birth of the customer (format: DD-MM-YYYY).  
10. **Product_Price**: The price of the product in INR.  


---

## Operations Performed in Excel

### 1. **Data Cleaning**
- **Removed Duplicates**: Ensured there were no duplicate records in the dataset.  
- **Handled Missing Values**: Checked for missing values in key columns like `Income` and `Product_Price` and resolved them using appropriate strategies such as mean imputation or deletion of incomplete rows.  
- **Standardized Formats**:  
  - Reformatted the `DOB` column into a consistent `DD-MM-YYYY` date format.  
  - Ensured that numerical columns like `Age`, `Income`, and `Quantity` were in correct data types for analysis.  
- **Resolved Errors**: Identified and corrected inconsistencies in categorical columns such as `City` and `Gender`.

---

### 2. **Feature Engineering**
- **New Calculations**:  
  - Created a **Total Revenue** column using the formula:  
    `=Product_Price * Quantity`.  
  - Extracted **Year of Birth** from the `DOB` column using Excel date functions.  
- **Segmentation**: Added categories based on income levels (e.g., Low, Medium, High) using conditional formatting and IF functions.  

---

### 3. **Data Analysis and Visualization**
- **Customer Demographics**:
  - Created pivot tables to analyze data by age, gender, and city.  
  - Used bar charts to visualize customer distribution across cities and age groups.  
- **Revenue Insights**:
  - Identified top-selling products and their contribution to total revenue.  
  - Created pie charts to illustrate revenue distribution by city and gender.  

---

### 4. **Sales Forecasting**
- **Trend Analysis**:  
  - Analyzed historical sales trends using line charts.  
  - Performed a moving average calculation to smoothen seasonal sales patterns.  
- **Forecasting**:  
  - Used Excel’s built-in **Forecast Sheet** feature to predict future sales based on historical data trends.  
  - Evaluated seasonal patterns and their impact on product demand.  

---

## Key Outputs
- **Interactive Dashboards**: Developed dashboards to display customer demographics, product sales, and revenue insights.  
- **Sales Predictions**: Forecasted monthly sales for future periods, assisting in strategic planning and inventory management.  

---

## Tools Used
- **Microsoft Excel**: For data cleaning, analysis, visualization, and forecasting.  
- **Excel Features**:  
  - Pivot Tables  
  - Conditional Formatting  
  - Data Validation  
  - Forecast Sheet  
  - Excel Formulas (e.g., SUM, AVERAGE, IF, and VLOOKUP)  

---

## Conclusion
This project demonstrates how Excel can be leveraged to clean, analyze, and forecast sales data effectively. The resulting insights and forecasts provide valuable guidance for improving business decisions and planning future sales strategies.
