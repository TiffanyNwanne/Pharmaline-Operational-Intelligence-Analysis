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
- This allowed for a consistent view of drug acquisition costs.
**Gross Profit Calculation**
- A **Gross Profit** column was introduced by subtracting the **Total Cost** from the **Total Sales** for each drug.
- This provided a preliminary measure of profitability before expenses.

### **Data Summarization and Validation**

**Pivot Table Analysis**
    - Pivot tables were used to aggregate the data and compute **Grand Totals** for sales, cost, and profit across all products.
    - These totals were compared against subtotal values grouped by drug categories to validate internal consistency. The values matched, confirming data accuracy.

### **Net Income Calculation**

- The **Total Cost of Drugs** derived from the Sales sheet was added to the **Expenses** recorded in the Expenses sheet.
- The **Net Income** for the month was calculated by subtracting total expenses (including cost of goods sold) from the total sales revenue.

### **Preparation for Visualization**

- The final results—including total sales, total cost, gross profit, and net income—were structured into a summary table.
- This output was formatted for export and further visualization using **Tableau**, to enable a clear and interactive presentation of the findings.
