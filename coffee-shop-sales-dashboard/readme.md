# ☕ Coffee Shop Sales Dashboard

An interactive Excel dashboard developed to analyze coffee shop sales performance, product demand, store performance, and purchasing patterns.

The project uses Microsoft Excel features such as PivotTables, PivotCharts, calculated columns, slicers, and dashboard design techniques to transform raw sales data into an interactive business dashboard.

---

## 🎯 Project Objective

The objective of this project is to analyze coffee shop sales data and identify important patterns in:

- Overall sales performance
- Store-level performance
- Product category performance
- Monthly sales trends
- Weekday sales patterns
- Time-of-day sales
- Top-performing products

The dashboard is designed to help understand **when, where, and what customers are purchasing** and provide data-driven recommendations for improving business performance.

---

## 📊 Dashboard KPIs

The dashboard tracks four key performance indicators:

| KPI | Description |
|---|---|
| **Total Sales** | Total revenue generated |
| **Total Orders** | Total number of transactions |
| **Total Items** | Total quantity of items sold |
| **Average Transaction Value** | Average sales value per transaction |

### Current Dashboard Values

- **Total Sales:** $698.81K
- **Total Orders:** 149,116
- **Total Items:** 214,470
- **Average Transaction Value:** $4.69

---

## 📈 Dashboard Visualizations

The dashboard contains six main visualizations:

### 1. Monthly Sales Trend
A line chart showing how sales change across the months and helping identify periods of increasing or decreasing sales.

### 2. Sales by Store
Compares sales performance across the three store locations:

- Astoria
- Hell's Kitchen
- Lower Manhattan

### 3. Sales by Product Category
Shows the revenue contribution of different product categories such as Coffee, Tea, Bakery, and other categories.

### 4. Sales by Weekday
Analyzes sales performance across the days of the week to identify stronger and weaker sales days.

### 5. Top 10 Products
A horizontal bar chart showing the highest-performing products based on sales.

### 6. Sales by Time Period
Analyzes sales across different parts of the day:

- Morning
- Noon
- Evening
- Night

---

## 🎛️ Interactive Filters

The dashboard contains interactive Excel slicers for:

- **Store Location**
- **Month**
- **Product Category**

These slicers are connected to the dashboard's PivotTables/PivotCharts, allowing users to dynamically filter the entire analysis.

For example, users can select a particular store and category to analyze the sales performance of that combination.

---

## 🛠️ Tools & Excel Features Used

- Microsoft Excel
- Excel Tables
- Excel formulas
- Calculated columns
- PivotTables
- PivotCharts
- Slicers
- Data formatting
- Conditional formatting
- Dashboard design
- Data visualization

---

## 🔍 Key Insights

Based on the dashboard:

- **Coffee is the leading product category** by sales.
- **Hell's Kitchen** records the highest sales among the three store locations.
- **Morning** is the strongest sales period.
- **Barista Espresso** is the highest-selling product among the Top 10 products.
- Sales show an overall upward trend across the months in the dataset, with the highest sales occurring toward the later months.
- Sales vary across weekdays, indicating differences in customer demand throughout the week.

---

## 💡 Recommendations

Based on the observed sales patterns:

1. **Maintain sufficient inventory of high-performing products**, particularly coffee products and the leading individual products.

2. **Focus staffing and operational resources during peak periods**, especially during the morning when sales are highest.

3. **Study the performance of high-performing stores** to identify operational practices that could potentially be applied to lower-performing locations.

4. **Use targeted promotions during weaker periods or days** to improve sales during lower-demand time slots.

5. **Continue monitoring monthly sales trends** to identify seasonal patterns and support inventory and staffing decisions.

---

## 📁 Project Structure

```text
coffee-shop-sales-dashboard/
│
├── README.md
├── Coffee-Shop-Sales-Dashboard.xlsx
│
├── data/
│   └── coffee_shop_sales.csv
│
├── images/
│   └── dashboard-preview.png
│
└── docs/
    └── project-report.pdf