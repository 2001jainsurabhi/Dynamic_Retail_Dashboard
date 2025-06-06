## 📊 Dynamic Retail Dashboard in Excel

### 🔍 Overview

The **Dynamic Retail Dashboard** is an interactive and data-driven tool built in Excel to visualize and analyze retail data. It connects to datasets hosted on GitHub, uses Power Query for data transformation, and presents insights through dynamic charts and KPIs. The dashboard addresses key business questions, enabling informed and strategic decision-making.

### 📁 Datasets Used

**1. Orders Table**
Contains details of customer orders including product, shipping, and financial metrics.

*Sample Data:*

| Order ID       | Returned | Order Date | Ship Date  | Ship Mode    | Customer Name | Segment   | Country       | Market | Sales   | Profit  | Discount |
| -------------- | -------- | ---------- | ---------- | ------------ | ------------- | --------- | ------------- | ------ | ------- | ------- | -------- |
| CA-2012-124891 | No       | 31-07-2020 | 31-07-2020 | Same Day     | Rick Hansen   | Consumer  | United States | US     | 2309.65 | 762.18  | 0        |
| IN-2013-77878  | Yes      | 05-02-2021 | 07-02-2021 | Second Class | Justin Ritter | Corporate | Australia     | APAC   | 3709.40 | -288.77 | 0.1      |
| IN-2013-71249  | No       | 17-10-2021 | 18-10-2021 | First Class  | Craig Reiter  | Consumer  | Australia     | APAC   | 5175.17 | 919.97  | 0.1      |

**2. Returns Table**
Tracks orders that have been returned, along with the associated markets.

*Sample Data:*

| Returned | Order ID        | Market        |
| -------- | --------------- | ------------- |
| Yes      | MX-2013-168137  | LATAM         |
| Yes      | US-2011-165316  | LATAM         |
| Yes      | ES-2013-1525878 | EU            |
| Yes      | CA-2013-118311  | United States |

**3. People Table**
Contains details about sales representatives and their respective regions.

*Sample Data:*

| Person            | Region  |
| ----------------- | ------- |
| Anna Andreadi     | Central |
| Chuck Magee       | South   |
| Kelly Williams    | East    |
| Matt Collister    | West    |
| Deborah Brumfield | Africa  |

### 📌 Problem Statements Solved

**1. Key Performance Indicators (KPIs)**
*Objective:* Calculate and display Total Sales, Total Profit, Total Quantity, Number of Orders, and Profit Margin dynamically.

**Steps:**

* Import Orders Table using Power Query
* Create calculated columns:

  * Profit Margin = Profit / Sales
  * Total Orders = Count of Order ID
* Use formulas to calculate total values
* Build a KPI table with symbols and formatting

**2. Sales and Profit Analysis**
*Objective:* Visualize trends over time to identify patterns.

**Steps:**

* Create Pivot Table grouped by Year & Month
* Add Sales and Profit as values
* Create a Line Chart for trends
* Add slicers for dynamic filtering

**3. Category-Wise Profit**
*Objective:* Analyze profitability across product categories.

**Steps:**

* Pivot Table: Category vs Profit
* Sort descending by Profit
* Create Bar Chart + slicers

**4. Segment-Wise Sales Share (%)**
*Objective:* Show sales proportion per customer segment.

**Steps:**

* Pivot Table: Segment vs Sales
* Calculate % share
* Create Pie/Donut Chart with labels

**5. Sales by Country**
*Objective:* Evaluate country-wise performance.

**Steps:**

* Pivot Table: Country vs Sales
* Sort descending
* Apply conditional formatting / heatmap

**6. Top 5 Subcategories**
*Objective:* Highlight top 5 performers.

**Steps:**

* Pivot Table: Sub-Category vs Sales
* Sort + filter top 5
* Create Column Chart

## 📌 Key Performance Indicators (KPIs)

The dashboard highlights essential metrics using symbols to improve clarity and design. Here is the KPI summary as shown in the dashboard:

| KPI Name         | Description             | Symbol | Unicode        |
|------------------|--------------------------|--------|----------------|
| **Total Sales**     | Overall revenue earned    | 📈     | `U+1F4C8` (📈)   |
| **Total Profit**    | Net earnings after costs  | 💰     | `U+1F4B0` (💰)   |
| **Total Quantity**  | Total units sold          | 📦     | `U+1F4E6` (📦)   |
| **No. of Orders**   | Total order count         | 🛒     | `U+1F6D2` (🛒)   |
| **Profit Margin**   | Profit-to-sales ratio     | 📊     | `U+1F4CA` (📊)   |

> These symbols are included using Excel’s `UNICHAR()` function or pasted directly, enhancing the readability and visual design of the KPI section.

### ⚙️ Dynamic Features

* **Dynamic Charts:** Real-time updates via slicers
* **Power Query:** Automates data cleanup and structure
* **KPI Table:** Instantly highlights key metrics

### 🚀 Next Steps / Extensions

* Return rate analysis by market/category
* Identify top & bottom customers
* Compare market performance
* Deep-dive into product-level metrics

### 💡 Significance

This dashboard empowers retail businesses to:

* Track performance using clean KPIs
* Understand trends by segment, category, geography
* Make smarter, data-driven decisions

It also showcases my skills in:

* Excel analytics & data visualization
* Data modeling & transformation
* Solving real-world business problems

### ✅ Conclusion

The Dynamic Retail Dashboard is a comprehensive, user-friendly tool that translates raw data into actionable insights. It demonstrates my ability to use Excel for practical business intelligence and deliver meaningful dashboards for stakeholders. This project is a strong example of how data analysis can drive strategic decisions in a retail environment.


