

🚲 Bikes Sales Dashboard using Excel 📊

The **Bikes Sales Dashboard** project provides an interactive and insightful dashboard built using **Excel** to visualize and analyze the sales data of bikes. It offers key performance indicators (KPIs), trends, and charts to help users understand the performance of bike sales, track monthly/annual sales, and make informed business decisions.

This project is designed for anyone who needs to track sales data in a simple yet efficient way using Excel. Whether you are managing a bike shop, an online marketplace, or simply looking to analyze bike sales trends, this dashboard offers a clean and user-friendly interface for all your reporting needs.

---

🧑‍💻 **Features**
- **Interactive Dashboard**: Dynamic charts and pivot tables to track sales performance.
- **Sales Insights**: Visualizations like total sales, sales per category, and regional sales breakdown.
- **Trends Analysis**: Displays sales trends over time (monthly, quarterly, and yearly).
- **KPIs**: Key metrics like total revenue, average sales per month, and sales growth percentage.
- **Filters**: Easily filter by regions, product categories, time periods, and more.

---

🔧 **Technologies Used**
- **Microsoft Excel**: The dashboard is built entirely using Excel features.
  - **Pivot Tables**: To aggregate and analyze the sales data.
  - **Charts/Graphs**: Line charts, bar charts, and pie charts to visualize the data.
  - **Formulas**: SUM, AVERAGE, COUNTIF, VLOOKUP, and other Excel functions.
  - **Conditional Formatting**: For highlighting key trends and performance indicators.
- **Excel Data Validation**: Used for user-friendly dropdowns and filters.

---

📊 **Data Structure**

The sales data file includes the following columns:

1. **Order ID**: Unique identifier for each sale.
2. **Product Name**: Name of the bike model.
3. **Product Category**: Type/category of the bike (e.g., Mountain, Road, Hybrid).
4. **Region**: The region where the bike was sold (e.g., North America, Europe).
5. **Sales Date**: The date the bike was sold.
6. **Units Sold**: The number of bikes sold.
7. **Unit Price**: The price per bike sold.
8. **Total Sales**: Automatically calculated as `Units Sold` × `Unit Price`.

---

🚀 **Getting Started**

To get started with the **Bikes Sales Dashboard** project, follow these steps:

1. Clone the repository:


git clone https://github.com/sidharth76/Bikes-Sales-Dashboard.git


2. Open the Excel file:

- Open the `Bikes_Sales_Dashboard.xlsx` file using Microsoft Excel.
- Ensure that macros and interactive elements are enabled in your Excel environment.

3. Data Input:

- **Input your sales data**: Replace the example data in the provided `Sales_Data` sheet with your own bike sales data.
- Ensure the data includes all the necessary columns mentioned in the **Data Structure** section above.

4. Review the Dashboard:

- Navigate to the **Dashboard** sheet, where you can find various interactive charts and KPIs.
- Use the dropdown filters to explore sales by category, region, or time period.
  
5. Customize (Optional):

- **Add New Categories**: If you have new bike categories or regions, simply add them to the data and refresh the pivot tables.
- **Modify KPIs**: You can edit the formulae used to calculate KPIs like total revenue, average sales, etc., based on your specific needs.

---

💡 **Features in Detail**

1. **Interactive Dashboard:**
   - The dashboard is designed to update automatically as you add or modify data.
   - It displays various charts that visualize sales over time, by region, and by bike category.

2. **Sales Breakdown:**
   - The **Sales Breakdown** chart shows how many bikes were sold by category (e.g., Mountain, Road, Hybrid).
   - Filter by region or time period to get a more detailed analysis.

3. **Performance KPIs:**
   - **Total Revenue**: Displays the total revenue generated from sales.
   - **Average Sales**: Shows the average sales per month or year.
   - **Sales Growth**: Measures the percentage growth in sales compared to the previous period.

4. **Dynamic Filters:**
   - Use the **Slicers** (Excel's interactive filter tool) to filter by region, category, and date range to get specific insights into your data.

---
📈 **Sample Excel Formulae**

Here are some examples of the formulas used in the dashboard:

1. **Total Sales**:
   ```excel
   =SUM(Units Sold * Unit Price)
   ```

2. **Average Monthly Sales**:
   ```excel
   =AVERAGEIFS(Total Sales, Sales Date, ">=1/1/2023", Sales Date, "<=12/31/2023")
   ```

3. **Growth Percentage**:
   ```excel
   =(Current Period Sales - Previous Period Sales) / Previous Period Sales * 100
   ```

---

📂 **File Structure**

- **Bikes_Sales_Dashboard.xlsx**: Main Excel file containing the dashboard, charts, and sales data.
- **Sales_Data**: The sheet where raw sales data is stored.
- **Dashboard**: The sheet where all the visualizations and KPIs are displayed.
- **Documentation**: A brief guide explaining how to use and customize the dashboard (optional).

---


## 🗣️ **Contact**

If you have any questions, suggestions, or feedback, feel free to open an issue or contact the repository owner directly.

- GitHub: [@Sidharth76](https://github.com/sidharth76)
```
