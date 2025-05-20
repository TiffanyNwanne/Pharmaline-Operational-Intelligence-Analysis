# Methodology

This section outlines the steps taken to clean, analyze, and interpret the January sales data for a pharmacy using Microsoft Excel. The dataset comprised two sheets: **Sales** and **Expenses** for the month of January.

### **Data Preparation and Cleaning**

**Dataset Structure**

- The *Sales* sheet contained item-level sales data, including fields such as drug name, units sold, unit price, and unit cost.
[![](https://github.com/TiffanyNwanne/Pharmaline-Operational-Intelligence-Analysis/blob/main/images/methodology/1.png)](https://github.com/TiffanyNwanne/Pharmaline-Operational-Intelligence-Analysis/blob/main/images/methodology/1.png)
    
- The *Expenses* sheet listed various operational and administrative costs incurred during the same month.
[![](https://github.com/TiffanyNwanne/Pharmaline-Operational-Intelligence-Analysis/blob/main/images/methodology/2.png)](https://github.com/TiffanyNwanne/Pharmaline-Operational-Intelligence-Analysis/blob/main/images/methodology/2.png)
 
**Data Cleaning**
    - The dataset was reviewed for completeness and consistency.
    - Missing values were addressed, and data types were verified to ensure accurate calculations.

### **Sales and Cost Calculation**

**Total Sales Calculation**

- A new column was added to the *Sales* sheet to compute the **Total Sales** for each drug by multiplying the **Units Sold** by the **Unit Price**.

[![](https://github.com/TiffanyNwanne/Pharmaline-Operational-Intelligence-Analysis/blob/main/images/methodology/3.png)](https://github.com/TiffanyNwanne/Pharmaline-Operational-Intelligence-Analysis/blob/main/images/methodology/3.png)

- The formula was applied across all rows to derive total sales figures for each product.

[![](https://github.com/TiffanyNwanne/Pharmaline-Operational-Intelligence-Analysis/blob/main/images/methodology/4.png)](https://github.com/TiffanyNwanne/Pharmaline-Operational-Intelligence-Analysis/blob/main/images/methodology/4.png)

**Total Cost Calculation**

- Similarly, a column was created to calculate the **Total Cost** of each drug using the **Unit Cost** multiplied by the **Units Sold**.

 [![](https://github.com/TiffanyNwanne/Pharmaline-Operational-Intelligence-Analysis/blob/main/images/methodology/5.png)](https://github.com/TiffanyNwanne/Pharmaline-Operational-Intelligence-Analysis/blob/main/images/methodology/5.png) 

- This allowed for a consistent view of drug acquisition costs.
**Gross Profit Calculation**
 [![](https://github.com/TiffanyNwanne/Pharmaline-Operational-Intelligence-Analysis/blob/main/images/methodology/6.png)](https://github.com/TiffanyNwanne/Pharmaline-Operational-Intelligence-Analysis/blob/main/images/methodology/6.png) 

- A **Gross Profit** column was introduced by subtracting the **Total Cost** from the **Total Sales** for each drug.

 [![](https://github.com/TiffanyNwanne/Pharmaline-Operational-Intelligence-Analysis/blob/main/images/methodology/7.png)](https://github.com/TiffanyNwanne/Pharmaline-Operational-Intelligence-Analysis/blob/main/images/methodology/7.png) 

- This provided a preliminary measure of profitability before expenses.
[![](https://github.com/TiffanyNwanne/Pharmaline-Operational-Intelligence-Analysis/blob/main/images/methodology/8.png)](https://github.com/TiffanyNwanne/Pharmaline-Operational-Intelligence-Analysis/blob/main/images/methodology/8.png)

### **Data Summarization and Validation**

**Pivot Table Analysis**

- Pivot tables were used to aggregate the data and compute **Grand Totals** for sales, cost, and profit across all products.

[![](https://github.com/TiffanyNwanne/Pharmaline-Operational-Intelligence-Analysis/blob/main/images/methodology/9.png)](https://github.com/TiffanyNwanne/Pharmaline-Operational-Intelligence-Analysis/blob/main/images/methodology/9.png)

- These totals were compared against subtotal values grouped by drug categories to validate internal consistency. The values matched, confirming data accuracy.
  
[![](https://github.com/TiffanyNwanne/Pharmaline-Operational-Intelligence-Analysis/blob/main/images/methodology/10.png)](https://github.com/TiffanyNwanne/Pharmaline-Operational-Intelligence-Analysis/blob/main/images/methodology/10.png)  

### **Net Income Calculation**

- The **Total Cost of Drugs** derived from the Sales sheet was added to the **Expenses** recorded in the Expenses sheet.

[![](https://github.com/TiffanyNwanne/Pharmaline-Operational-Intelligence-Analysis/blob/main/images/methodology/11.png)](https://github.com/TiffanyNwanne/Pharmaline-Operational-Intelligence-Analysis/blob/main/images/methodology/11.png) 

- The **Net Income** for the month was calculated by subtracting total expenses (including cost of goods sold) from the total sales revenue.
  
[![](https://github.com/TiffanyNwanne/Pharmaline-Operational-Intelligence-Analysis/blob/main/images/methodology/12.png)](https://github.com/TiffanyNwanne/Pharmaline-Operational-Intelligence-Analysis/blob/main/images/methodology/12.png)  

[![](https://github.com/TiffanyNwanne/Pharmaline-Operational-Intelligence-Analysis/blob/main/images/methodology/13.png)](https://github.com/TiffanyNwanne/Pharmaline-Operational-Intelligence-Analysis/blob/main/images/methodology/13.png)

### **Preparation for Visualization**

- The final results—including total sales, total cost, gross profit, and net income—were structured into a summary table.

[![](https://github.com/TiffanyNwanne/Pharmaline-Operational-Intelligence-Analysis/blob/main/images/methodology/14.png)](https://github.com/TiffanyNwanne/Pharmaline-Operational-Intelligence-Analysis/blob/main/images/methodology/14.png) 

- This output was formatted for export and further visualization using **Tableau**, to enable a clear and interactive presentation of the findings.
