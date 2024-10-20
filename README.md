# Warehouse-Retail-Sales-Analysis---PBI
This project aims to provide a comprehensive analysis of warehouse sales by revealing trends, performance metrics, and sales distributions across different dimensions. This analysis helps in strategic decision-making to optimize inventory management, supplier performance, and sales strategies.


**Project Objective:**
This project aims to provide a comprehensive analysis of warehouse sales by revealing trends, performance metrics, and sales distributions across different dimensions. This analysis helps in strategic decision-making to optimize inventory management, supplier performance, and sales strategies.

**Dashboard Overview:**
The dashboard visually represents warehouse sales performance by analyzing various sales metrics and trends. Key metrics include total sales, retail sales, warehouse sales, and the distribution of sales by item type, supplier, and month.

### Data Fields:

- **Item Description**
- **Item Type**
- **Month**
- **Retail Sales**
- **Retail Transfer**
- **Supplier**
- **Warehouse Sales**
- **Year**

### Dashboard Components:

1. **Overview:**
   - **Total Sales:** Display the aggregate of retail sales, retail transfers, and warehouse sales.
   - **Total Retail Sales:** Show the sum of all retail sales.
   - **Total Retail Transfers:** Sum of all retail transfers.
   - **Total Warehouse Sales:** Sum of all warehouse sales.

2. **Total Sales by Item Type:**
   - **Chart Type:** Column Chart
   - **X-axis:** Item Type
   - **Y-axis:** Total Sales
   - **Values:** Sum of Total Sales
   - **Legend:** Item Type

3. **Total Warehouse Sales and Total Retail Sales by Month:**
   - **Chart Type:** Line and Column Chart
   - **X-axis:** Month
   - **Column Y-axis:** Total Warehouse Sales
   - **Line Y-axis:** Total Retail Sales
   - **Values:** Sum of Total Warehouse Sales, Sum of Total Retail Sales
   - **Legend:** Sales Type (Retail Sales, Warehouse Sales)

4. **Total Retail Sales by Supplier:**
   - **Chart Type:** Pie Chart
   - **Values:** Sum of Total Retail Sales
   - **Legend:** Supplier

5. **Total Retail Transfers by Item Type:**
   - **Chart Type:** Donut Chart
   - **Values:** Sum of Total Retail Transfers
   - **Legend:** Item Type

6. **Total Retail Sales by Item Description:**
   - **Chart Type:** Bar Chart
   - **X-axis:** Item Description
   - **Y-axis:** Total Retail Sales
   - **Values:** Sum of Total Retail Sales
   - **Legend:** Item Description

7. **Total Sales by Month:**
   - **Chart Type:** Waterfall Chart
   - **Category:** Month
   - **Values:** Sum of Total Sales

8. **Total Warehouse Sales by Supplier:**
   - **Chart Type:** Map
   - **Location Data:** Supplier
   - **Values:** Sum of Total Warehouse Sales

### Tools and Technologies:
- **Power BI:** For data visualization and dashboard creation.
- **DAX (Data Analysis Expressions):** For creating measures and calculated columns.

### Implementation in Power BI:

1. **KPI Cards:** Create cards for displaying Total Sales, Total Retail Sales, Total Retail Transfers, and Total Warehouse Sales.
2. **Column Chart:**
   - **Data Fields:** Item Type on X-axis, Total Sales on Y-axis.
   - **Aggregation:** Sum of Total Sales.
   - **Legend:** Item Type.
3. **Line and Column Chart:**
   - **Data Fields:** Month on X-axis, Total Warehouse Sales on Column Y-axis, Total Retail Sales on Line Y-axis.
   - **Aggregation:** Sum of Total Warehouse Sales, Sum of Total Retail Sales.
   - **Legend:** Sales Type.
4. **Pie Chart:**
   - **Data Fields:** Supplier as Legend, Total Retail Sales as Values.
   - **Aggregation:** Sum of Total Retail Sales.
5. **Donut Chart:**
   - **Data Fields:** Item Type as Legend, Total Retail Transfers as Values.
   - **Aggregation:** Sum of Total Retail Transfers.
6. **Bar Chart:**
   - **Data Fields:** Item Description on X-axis, Total Retail Sales on Y-axis.
   - **Aggregation:** Sum of Total Retail Sales.
   - **Legend:** Item Description.
7. **Waterfall Chart:**
   - **Data Fields:** Month as Category, Total Sales as Values.
   - **Aggregation:** Sum of Total Sales.
8. **Map:**
   - **Data Fields:** Supplier as Location Data, Total Warehouse Sales as Values.
   - **Aggregation:** Sum of Total Warehouse Sales.


![WAN](https://github.com/user-attachments/assets/7e59483d-14eb-4c34-ad7f-d293887abf34)


### Summary:

This dashboard provides a detailed and interactive view of warehouse sales performance, helping stakeholders make informed decisions by analyzing sales trends, supplier performance, and item-wise sales distribution.

