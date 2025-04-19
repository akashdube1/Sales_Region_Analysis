# Sales_Region_Analysis
This Excel project analyzes sales and profit data using formulas like SUM, AVERAGE, PRODUCT, UPPER, SUMIF, and SUMIFS. It includes data cleaning with TRIM, filtering by region, and visualizations such as line and pie charts. Aimed at beginners, it showcases key Excel skills for basic business data analysis.
# Excel Sales and Profit Analysis 📊

This project is an Excel-based data analysis of sales and profit figures. It includes basic data manipulation, formula usage, and chart visualization for better insights.

## 🔧 Features and Formulas Used

1. **Total Sales and Profit**
   - Used `SUM()` function to calculate total sales and profit.
   - Example: `=SUM(E2:E20)` for Sales, `=SUM(F2:F20)` for Profit.

2. **Filter by Region**
   - Applied filter to show only "North" and "East" regions for focused analysis.

3. **Double Sales Calculation**
   - Created a new column to calculate Sales * 2.
   - Example: `=E2*2`

4. **Average Sales Value**
   - Used `AVERAGE()` function to find the mean sales value.
   - Example: `=AVERAGE(E2:E20)`

5. **Convert Names to Uppercase**
   - Used `UPPER()` function to standardize name formatting.
   - Example: `=UPPER(D2)`

6. **Line Chart for Year-wise Analysis**
   - Used `SUMIFS()` to calculate total Sales and Profit per year.
   - Example: 
     - `=SUMIFS($E$2:$E$20, $A$2:$A$20, 2001)`
     - Created a Line Chart with Year on X-axis, Sales & Profit on Y-axis.

7. **Pie Chart for Region-wise Sales**
   - Used `TRIM()` to clean Region names, then `SUMIF()` for totals.
   - Example: `=SUMIF(C2:C20, "East", E2:E20)`

## 📁 File Details

- `Assingment.xlsx` – The main file containing all data, formulas, and charts.

## 📌 How to Use

1. Open the Excel file.
2. Review each column and chart to understand how formulas and filters are applied.
3. Use this as a reference for your own Excel-based analysis projects.

---

Made with 💻 + 📈 in Excel.
